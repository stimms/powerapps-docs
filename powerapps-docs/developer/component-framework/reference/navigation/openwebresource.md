---
title: openWebResource | Microsoft Docs
description: 
keywords:
ms.author: nabuthuk
manager: kvivek
ms.date: 04/23/2019
ms.service: "powerapps"
ms.suite: ""
ms.tgt_pltfrm: ""
ms.topic: "article"
ms.assetid: 27a1e54c-71fe-450f-8f84-b4cc125970bf
---

# openWebResource

[!INCLUDE [openwebresource-description](includes/openwebresource-description.md)]

## Syntax

`openWebResource(name, options, data)`

## Parameters

| Parameter Name|Type|Required|Description|
| ------------- |----|--------|-----------|
|name|`string`|yes|The name of the HTML web resource to open.|
|options|`OpenWebResourceOptions`|yes|Window options for the web resource. The OpenWebResourceOptions has the following attributes:<br/>- **height**: `number`. Height of the window to display the resultant page in pixels.<br/>- **width**: `number`. Width of the window to display the resultant page in pixels.<br/>- **openInNewWindow**: `boolean`. whether to open the web resource in a new window.|
|data|`string`|no|Data to be passed into the data parameter.


### Related topics

[Navigation](../navigation.md)<br/>
[PowerApps component framework API Reference](../../reference/index.md)<br/>
[PowerApps component framework Overview](../../overview.md)