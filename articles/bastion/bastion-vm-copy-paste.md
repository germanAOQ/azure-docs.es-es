---
title: 'Copiado y pegado entre máquinas virtuales: Azure Bastion'
description: Aprenda con este artículo a copiar y pegar entre máquinas virtuales de Azure al usar Bastion.
services: bastion
author: cherylmc
ms.service: bastion
ms.topic: how-to
ms.date: 05/04/2020
ms.author: cherylmc
ms.openlocfilehash: 50f7906992aa19daa205a30f71ce21456bafe558
ms.sourcegitcommit: a92fbc09b859941ed64128db6ff72b7a7bcec6ab
ms.translationtype: HT
ms.contentlocale: es-ES
ms.lasthandoff: 10/15/2020
ms.locfileid: "92079163"
---
# <a name="copy-and-paste-to-a-virtual-machine-azure-bastion"></a>Copiado y pegado entre máquinas virtuales: Azure Bastion

Este artículo le ayuda a copiar y pegar texto entre máquinas virtuales cuando se usa Azure Bastion. Antes de trabajar con una máquina virtual, asegúrese de que ha seguido los pasos indicados en [Creación de un host de Bastion](./tutorial-create-host-portal.md). Después, conéctese a la máquina virtual con la que quiere trabajar mediante [RDP](bastion-connect-vm-rdp.md) o [SSH](bastion-connect-vm-ssh.md).

En exploradores que admiten el acceso avanzado de la API de Portapapeles, puede copiar y pegar texto entre el dispositivo local y la sesión remota de la misma manera que copia y pega entre aplicaciones en el dispositivo local. En otros exploradores, puede utilizar la paleta de herramientas de acceso al Portapapeles de Bastion.

>[!NOTE]
>Actualmente solo se admiten operaciones de copiado y pegado de texto.
>

   ![Autorización del Portapapeles](./media/bastion-vm-manage/allow.png)

Solo se admiten operaciones de copiado y pegado de texto. En operaciones de copiado y pegado directo, es posible que el explorador le pida acceso al Portapapeles al inicializar la sesión de Bastion. Pulse **Permitir** para que la página web puede acceder al Portapapeles.

## <a name="copy-to-a-remote-session"></a><a name="to"></a>Copiado en una sesión remota

Después de conectarse a la máquina virtual mediante [Azure Portal](https://portal.azure.com), complete los siguientes pasos:

1. Copie el texto/contenido del dispositivo local al Portapapeles local.
1. Durante la sesión remota, inicie la paleta de herramientas de acceso al Portapapeles de Bastion seleccionando las dos flechas. Las flechas se encuentran en la parte central izquierda de la sesión.

   ![Captura de pantalla que muestra las flechas de inicio de la paleta de herramientas resaltadas en el lado izquierdo de la ventana.](./media/bastion-vm-manage/left.png)

   ![Captura de pantalla que muestra un Portapapeles con el texto copiado en Bastion.](./media/bastion-vm-manage/clipboard.png)
1. Normalmente, el texto copiado se muestra automáticamente en la paleta de copiado y pegado de Bastion. Si el texto no se encuentra allí, péguelo en el área de texto de la paleta.
1. Cuando el texto esté en el área de texto, podrá pegarlo en la sesión remota.

   ![Captura de pantalla que muestra el botón de copiado y pegado resaltado y una cadena de texto de ejemplo copiada en la sesión remota.](./media/bastion-vm-manage/local.png)

## <a name="copy-from-a-remote-session"></a><a name="from"></a>Copiado desde una sesión remota

Después de conectarse a la máquina virtual mediante [Azure Portal](https://portal.azure.com), complete los siguientes pasos:

1. Copie el texto/contenido de la sesión remota al Portapapeles remoto (con Ctrl-C).

   ![paleta de herramientas](./media/bastion-vm-manage/remote.png)
1. Durante la sesión remota, inicie la paleta de herramientas de acceso al Portapapeles de Bastion seleccionando las dos flechas. Las flechas se encuentran en la parte central izquierda de la sesión.

   ![Portapapeles](./media/bastion-vm-manage/clipboard2.png)
1. Normalmente, el texto copiado se muestra automáticamente en la paleta de copiado y pegado de Bastion. Si el texto no se encuentra allí, péguelo en el área de texto de la paleta.
1. Cuando el texto esté en el área de texto, podrá pegarlo en el dispositivo local.

   ![pegar](./media/bastion-vm-manage/local2.png)
 
## <a name="next-steps"></a>Pasos siguientes

Lea el artículo sobre [preguntas frecuentes de Bastion](bastion-faq.md).
