---
title: "teamsTemplate resource type"
description: "Describes teamsTemplate entity."
author: "nkramer"
ms.localizationpriority: medium
ms.prod: "microsoft-teams"
doc_type: resourcePageType
---

# teamsTemplate resource type

Namespace: microsoft.graph

A team template is a blueprint for creating a [team](../resources/team.md) in Microsoft Teams. A template specifies the structure, settings, and even content that should be provisioned in a new team created using the template. Microsoft provides a suite of base templates and customers can save their own custom templates.

## Properties

| Property            | Type     | Description |
|:------------------- |:-------- |:----------- |
| id                  | String   | Unique identifier of the template. Cannot be null. |

## JSON representation

<!-- {
  "blockType": "resource",
  "@odata.type": "microsoft.graph.teamsTemplate",
  "baseType": "microsoft.graph.entity"
}-->

```json
{
  "id": "string"
}
```

## Related content

- [team](team.md)


