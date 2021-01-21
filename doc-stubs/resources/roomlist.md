---
title: "roomList resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: resourcePageType
---

# roomList resource type

Namespace: microsoft.graph

**TODO: Add Description**


Inherits from [place](../resources/place.md).

## Methods
|Method|Return type|Description|
|:---|:---|:---|
|[List roomLists](../api/roomlist-list.md)|[roomList](../resources/roomlist.md) collection|Get a list of the [roomList](../resources/roomlist.md) objects and their properties.|
|[Create roomList](../api/roomlist-create.md)|[roomList](../resources/roomlist.md)|Create a new [roomList](../resources/roomlist.md) object.|
|[Get roomList](../api/roomlist-get.md)|[roomList](../resources/roomlist.md)|Read the properties and relationships of a [roomList](../resources/roomlist.md) object.|
|[Update roomList](../api/roomlist-update.md)|[roomList](../resources/roomlist.md)|Update the properties of a [roomList](../resources/roomlist.md) object.|
|[Delete roomList](../api/roomlist-delete.md)|None|Deletes a [roomList](../resources/roomlist.md) object.|
|[List spaces](../api/roomlist-list-spaces.md)|[space](../resources/space.md) collection|Get the space resources from the spaces navigation property.|
|[Create space](../api/roomlist-post-spaces.md)|[space](../resources/space.md)|Create a new space object.|

## Properties
|Property|Type|Description|
|:---|:---|:---|
|address|[physicalAddress](../resources/physicaladdress.md)|**TODO: Add Description** Inherited from [place](../resources/place.md)|
|displayName|String|**TODO: Add Description** Inherited from [place](../resources/place.md)|
|emailAddress|String|**TODO: Add Description**|
|geoCoordinates|[outlookGeoCoordinates](../resources/outlookgeocoordinates.md)|**TODO: Add Description** Inherited from [place](../resources/place.md)|
|id|String|**TODO: Add Description** Inherited from [entity](../resources/entity.md)|
|phone|String|**TODO: Add Description** Inherited from [place](../resources/place.md)|

## Relationships
|Relationship|Type|Description|
|:---|:---|:---|
|rooms|[room](../resources/room.md) collection|**TODO: Add Description**|
|spaces|[space](../resources/space.md) collection|**TODO: Add Description**|

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "keyProperty": "id",
  "@odata.type": "microsoft.graph.roomList",
  "baseType": "microsoft.graph.place",
  "openType": false
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.roomList",
  "id": "String (identifier)",
  "displayName": "String",
  "geoCoordinates": {
    "@odata.type": "microsoft.graph.outlookGeoCoordinates"
  },
  "phone": "String",
  "address": {
    "@odata.type": "microsoft.graph.physicalAddress"
  },
  "emailAddress": "String"
}
```
