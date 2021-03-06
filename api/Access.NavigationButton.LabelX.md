---
title: NavigationButton.LabelX property (Access)
keywords: vbaac10.chm10484
f1_keywords:
- vbaac10.chm10484
ms.prod: access
api_name:
- Access.NavigationButton.LabelX
ms.assetid: cddd2467-4d75-bc40-5472-ab8701120940
ms.date: 06/08/2017
localization_priority: Normal
---


# NavigationButton.LabelX property (Access)

The  **LabelX** property (along with the **LabelY** property) specifies the placement of the label for a new control. Read/write **Integer**.



## Syntax

_expression_. `LabelX`

_expression_ A variable that represents a [NavigationButton](Access.NavigationButton.md) object.


## Remarks

If the orientation is left to right for a form or report,  **LabelX** and **LabelY** behavior matches standard Microsoft Access left-to-right orientation. For more information about orientation, see the **Orientation** property.

If orientation is right to left, the origin of the coordinate system for  **LabelX** and **LabelY** is the upper right corner of the attached control. A negative number for **LabelX** places the label to the right of the control. A negative number for **LabelY** places the label above the control.

For General and Right alignment when orientation is RTL,  **LabelX** and **LabelY** specify the location of the upper-right corner of the label relative to the upper-right corner of the label's attached control. For Left and Center alignment, **LabelX** and **LabelY** specify the location of the upper-left corner and top center, respectively, of the label relative to the upper-right corner of the label's attached control.


## See also


[NavigationButton Object](Access.NavigationButton.md)

[!include[Support and feedback](~/includes/feedback-boilerplate.md)]