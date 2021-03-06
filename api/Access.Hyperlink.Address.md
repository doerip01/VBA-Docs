---
title: Hyperlink.Address property (Access)
keywords: vbaac10.chm10115
f1_keywords:
- vbaac10.chm10115
ms.prod: access
api_name:
- Access.Hyperlink.Address
ms.assetid: 68b9cf8f-a647-798d-36ae-d451b7e6ae5a
ms.date: 06/08/2017
localization_priority: Normal
---


# Hyperlink.Address property (Access)

You can use the **Address** property to specify or determine the path to an object, document, Web page or other destination for a **[Hyperlink](Access.Hyperlink.md)** object associated with a command button, image control, or label control. Read/write **String**.


## Syntax

_expression_. `Address`

_expression_ A variable that represents a **[Hyperlink](Access.Hyperlink.md)** object.


## Remarks

 When you set the **Address** property, you automatically specify the **HyperlinkAddress** property for the control associated with the hyperlink.

For more information about hyperlink addresses and their format, see the **HyperlinkAddress** and **HyperlinkSubAddress** property topics.


## See also


[Hyperlink Object](Access.Hyperlink.md)

[!include[Support and feedback](~/includes/feedback-boilerplate.md)]