---
title: WDI_TLV_ACTION_FRAME_BODY
author: windows-driver-content
description: WDI_TLV_ACTION_FRAME_BODY is a TLV that contains the body of an Action Frame.
ms.assetid: 272782A9-F92E-4F32-A92B-B18EBE7C1803
ms.author: windowsdriverdev 
ms.date: 07/18/2017 
ms.topic: article 
ms.prod: windows-hardware 
ms.technology: windows-devices 
keywords:
 - WDI_TLV_ACTION_FRAME_BODY Network Drivers Starting with Windows Vista
---

# WDI\_TLV\_ACTION\_FRAME\_BODY


WDI\_TLV\_ACTION\_FRAME\_BODY is a TLV that contains the body of an Action Frame.

## TLV Type


0xBE

## Length


The size (in bytes) of the array of UINT8 elements. The array must contain 1 or more elements.

## Values


| Type      | Description                                                           |
|-----------|-----------------------------------------------------------------------|
| UINT8\[\] | An array of UINT8 elements that contains the body of an Action Frame. |

 

Requirements
------------

<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<tbody>
<tr class="odd">
<td><p>Minimum supported client</p></td>
<td><p>Windows 10</p></td>
</tr>
<tr class="even">
<td><p>Minimum supported server</p></td>
<td><p>Windows Server 2016</p></td>
</tr>
<tr class="odd">
<td><p>Header</p></td>
<td>Wditypes.hpp</td>
</tr>
</tbody>
</table>

 

 




