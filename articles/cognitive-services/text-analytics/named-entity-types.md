---
title: Categorías admitidas para Reconocimiento de entidades con nombre
titleSuffix: Azure Cognitive Services
description: Obtenga información sobre las categorías de entidad admitidas en Text Analytics API.
services: cognitive-services
author: aahill
manager: nitinme
ms.service: cognitive-services
ms.subservice: text-analytics
ms.topic: article
ms.date: 01/22/2021
ms.author: aahi
ms.openlocfilehash: 883c5a20612f4dab44c0d06776ee287b27174ab9
ms.sourcegitcommit: b4e6b2627842a1183fce78bce6c6c7e088d6157b
ms.translationtype: HT
ms.contentlocale: es-ES
ms.lasthandoff: 01/30/2021
ms.locfileid: "99097310"
---
# <a name="supported-entity-categories-in-the-text-analytics-api-v3"></a>Categorías de entidad admitidas en Text Analytics API v3.

Use este artículo para buscar las categorías de entidad que [Reconocimiento de entidades con nombre](how-tos/text-analytics-how-to-entity-linking.md) (NER) puede devolver. NER ejecuta un modelo predictivo para identificar y categorizar entidades con nombre a partir de un documento de entrada.

También está disponible una versión preliminar de NER v3.1, que incluye la capacidad de detectar información personal (`PII`) y de salud (`PHI`). Además, haga clic en la pestaña de **estado** para ver una lista de las categorías admitidas en Text Analytics para el estado. 

Puede encontrar una lista de los tipos devueltos por la versión 2.1 en la [guía de migración](migration-guide.md?tabs=named-entity-recognition).

## <a name="entity-categories"></a>Categorías de entidad

#### <a name="general"></a>[General](#tab/general)

[!INCLUDE [supported entity types - general](./includes/entity-types/general-entities.md)]

#### <a name="pii"></a>[PII](#tab/personal)

[!INCLUDE [supported entity types - personally identifying information](./includes/entity-types/personal-information-entities.md)]

#### <a name="health"></a>[Estado](#tab/health)

[!INCLUDE [biomedical entity types](./includes/entity-types/health-entities.md)]

**_

## <a name="next-steps"></a>Pasos siguientes

_[Uso del reconocimiento de entidades con nombre en Text Analytics](how-tos/text-analytics-how-to-entity-linking.md)
