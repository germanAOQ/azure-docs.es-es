---
author: DCtheGeek
ms.service: azure-policy
ms.topic: include
ms.date: 02/09/2021
ms.author: dacoulte
ms.custom: generated
ms.openlocfilehash: 5c1857372eb4aad2bf87e4078bae5e1fc41412a8
ms.sourcegitcommit: 24f30b1e8bb797e1609b1c8300871d2391a59ac2
ms.translationtype: HT
ms.contentlocale: es-ES
ms.lasthandoff: 02/10/2021
ms.locfileid: "100091903"
---
|Nombre |Descripción |Directivas |Versión |
|---|---|---|---|
|[Implementación: configuración de los requisitos previos para habilitar Azure Monitor y agentes de seguridad de Azure en máquinas virtuales](https://github.com/Azure/azure-policy/blob/master/built-in-policies/policySetDefinitions/Monitoring/AzureMonitoring_Prerequisites.json) |Configure las máquinas para instalar automáticamente los agentes de seguridad de Azure y Azure Monitor. Security Center recopila eventos de los agentes y los usa para proporcionar alertas de seguridad y tareas de protección personalizadas (recomendaciones). Cree un grupo de recursos y un área de trabajo de Log Analytics en la misma región que la máquina para almacenar los registros de auditoría. Esta directiva solo se aplica a las máquinas virtuales en algunas regiones. |5 |1.0.0-preview |
|[Habilitar Azure Monitor para conjunto de escalado de máquinas virtuales](https://github.com/Azure/azure-policy/blob/master/built-in-policies/policySetDefinitions/Monitoring/AzureMonitor_VMSS.json) |Se habilita Azure Monitor para los conjuntos de escalado de máquinas virtuales en el ámbito especificado (grupo de administración, suscripción o grupo de recursos). Usa el área de trabajo de Log Analytics como parámetro. Nota: Si establece upgradePolicy del conjunto de escalado en Manual, debe aplicar la extensión a todas las máquinas virtuales del conjunto mediante una llamada a la actualización. En la CLI, se usaría az vmss update-instances. |6 |1.0.1 |
|[Habilitar Azure Monitor para VM](https://github.com/Azure/azure-policy/blob/master/built-in-policies/policySetDefinitions/Monitoring/AzureMonitor_VM.json) |Se habilita Azure Monitor para las máquinas virtuales en el ámbito especificado (grupo de administración, suscripción o grupo de recursos). Usa el área de trabajo de Log Analytics como parámetro. |10 |2.0.0 |
