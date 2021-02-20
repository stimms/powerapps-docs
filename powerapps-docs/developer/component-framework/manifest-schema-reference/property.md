---
title: Property Element | Microsoft Docs
description: 
keywords:
ms.author: nabuthuk
manager: kvivek
ms.date: 04/23/2019
ms.service: "powerapps"
ms.suite: ""
ms.tgt_pltfrm: ""
ms.topic: "article"
ms.assetid: 45f4872d-c1d2-4c5a-8721-251b96ede370
---

# property element

[!INCLUDE[cc-beta-prerelease-disclaimer](../../../includes/cc-beta-prerelease-disclaimer.md)]

[!INCLUDE [property-description](includes/property-description.md)]

## Attributes

|Name|Description|Type|Required|
|--|--|--|--|
|`name`|Name of the property|`string`|Yes|
|`display-name-key`|Used in the customization screens as localized strings that describes the name of the property.|`string`|Yes|
|`of-type`|Defines the data type of the property|See [Remarks](#remarks)|Optional|
|`usage`|The usage attribute identifies if the property is meant to represent an entity attribute that the component can change (bound) or read-only values (input)|`bound` or `input`|Optional|
|`required`|Whether the property is required or not|`boolean`|Optional|
|`of-type-group`|Name of the type-group as defined in manifest|`string`|Optional|
|`description-key`|Used in the customization screens as localized strings that describes the description of the property.|`string`|Optional|

### Remarks

The `of-type` attribute value must be one of the following:

[!INCLUDE [type-table](includes/type-table.md)]

## Parent Elements

|Element|Description|
|--|--|
|[manifest](manifest.md)|[!INCLUDE [manifest-description](includes/manifest-description.md)]|


## Example

```xml
<property name="myFirstProperty" display-name-key="myFirstProperty_Display_Key" 
description-key="myFirstProperty_Desc_Key" of-type="SingleLine.Text" usage="bound" required="true" />
```

### Related topics

[PowerApps component framework Manifest Schema Reference](index.md)<br/>
[PowerApps component framework API Reference](../reference/index.md)<br/>
[PowerApps component framework Overview](../overview.md)
