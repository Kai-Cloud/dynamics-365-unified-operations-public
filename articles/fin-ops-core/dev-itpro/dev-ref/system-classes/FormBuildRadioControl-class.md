---
title: FormBuildRadioControl class
description: This topic describes the FormBuildRadioControl class.
author: robinarh
manager: tonyafehr
ms.date: 06/25/2020
ms.topic: article
ms.prod: 
ms.service: dynamics-ax-platform
ms.technology: 

audience: Developer
ms.reviewer: rhaertle
ms.search.scope: Operations
ms.search.region: Global
ms.author: rhaertle
ms.search.validFrom: 2016-02-28
ms.dyn365.ops.version: AX 7.0.0
---

# Class FormBuildRadioControl

[!include [banner](../../includes/banner.md)]

```xpp
class FormBuildRadioControl extends FormBuildControl
```

The FormBuildRadioControl class lets you create, read, update, and delete X++ code and metadata.

## Remarks

Make sure that the user has access to the development security key (SysDevelopment) before this API is called.

## Examples

## Methods

| Method                                                                                                      | Description                                                                                                                             |
|-------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------|
| public boolean alignControl(\[boolean value\])                                                              | Determines whether to align the control.                                                                                                |
| public boolean allowEdit(\[boolean value\])                                                                 | Determines whether the user can change the contents of the control.                                                                     |
| public int arrayIndex(\[int value\])                                                                        |                                                                                                                                         |
| public boolean autoDeclaration(\[boolean value\])                                                           | Determines whether the system can declare a member variable that has the same name as the control.                                      |
| public int backgroundColor(\[int value\])                                                                   | Gets or sets the background color of the control.                                                                                       |
| public int backStyle(\[int value\])                                                                         | Determines whether the control background can be transparent.                                                                           |
| public int bold(\[int value\])                                                                              | Gets or sets the weight of font that is used to output text in the control.                                                             |
| public int bottomMargin(\[int value\], \[AutoMode mode\])                                                   |                                                                                                                                         |
| public AutoMode bottomMarginMode(\[AutoMode mode\])                                                         |                                                                                                                                         |
| public int bottomMarginValue(\[int value\])                                                                 |                                                                                                                                         |
| public int cacheDataMethod(\[int value\])                                                                   |                                                                                                                                         |
| public str caption(\[str value\])                                                                           | Gets or set the caption of the control.                                                                                                 |
| public int characterSet(\[int value\])                                                                      | Gets or sets the character set of the font.                                                                                             |
| public int colorScheme(\[int value\])                                                                       | Gets or sets the color scheme of the control.                                                                                           |
| public int columns(\[int value\])                                                                           |                                                                                                                                         |
| public ConfigurationKeyId configurationKey(\[ConfigurationKeyId value\])                                    | Gets or sets the configuration key that is assigned to the control.                                                                     |
| public int containerId()                                                                                    | Retrieves the ID of the parent container for the control.                                                                               |
| public str countryRegionCodes(\[str value\])                                                                |                                                                                                                                         |
| public FieldId countryRegionContextField(\[FieldId value\])                                                 |                                                                                                                                         |
| public FieldId dataField(\[FieldId value\])                                                                 |                                                                                                                                         |
| public str dataMethod(\[str value\])                                                                        |                                                                                                                                         |
| public str dataRelationPath(\[str value\])                                                                  |                                                                                                                                         |
| public int dataSource(\[AnyType value\])                                                                    | Gets or sets a data source that will be used by the control or the form.                                                                |
| public int displayLength(\[int value\], \[AutoMode mode\])                                                  |                                                                                                                                         |
| public AutoMode displayLengthMode(\[AutoMode mode\])                                                        |                                                                                                                                         |
| public int displayLengthValue(\[int value\])                                                                |                                                                                                                                         |
| public int displayTarget(\[int value\])                                                                     |                                                                                                                                         |
| public int dragDrop(\[int value\])                                                                          | Determines whether to enable or disable drag-and-drop operations for the control.                                                       |
| public boolean enabled(\[boolean value\])                                                                   | Determines whether to enable or disable the object.                                                                                     |
| public EnumId enumType(\[EnumId value\])                                                                    |                                                                                                                                         |
| public ExtendedTypeId extendedDataType(\[ExtendedTypeId value\])                                            |                                                                                                                                         |
| public str font(\[str value\])                                                                              | Gets or sets the name of the font for the control to use.                                                                               |
| public int fontSize(\[int value\])                                                                          | Gets or sets the size of the font for the control to use.                                                                               |
| public int foregroundColor(\[int value\])                                                                   | Gets or sets the text color for the control to use.                                                                                     |
| public int framePosition(\[int value\])                                                                     |                                                                                                                                         |
| public int frameType(\[int value\])                                                                         |                                                                                                                                         |
| public int height(int value, \[int mode\])                                                                  | Gets or sets the height of the control.                                                                                                 |
| public int heightMode(\[int value\])                                                                        | Gets or sets a calculation mode for the height of the control.                                                                          |
| public int heightValue(\[int value\])                                                                       | Gets or sets the height of the control.                                                                                                 |
| public str helpText(\[str value\])                                                                          | Gets or sets the help text to display at the bottom of the screen when a field or control is pointed to.                                |
| public boolean hideFirstEntry(\[boolean value\])                                                            |                                                                                                                                         |
| public str hierarchyParent(\[str value\])                                                                   |                                                                                                                                         |
| public int id()                                                                                             | Retrieves the ID of the control.                                                                                                        |
| public boolean isContainer()                                                                                | Retrieves a value that indicates whether the control is a container control.                                                            |
| public boolean italic(\[boolean value\])                                                                    |                                                                                                                                         |
| public int item(\[int value\])                                                                              |                                                                                                                                         |
| public int items(\[int value\])                                                                             |                                                                                                                                         |
| public int left(int value, \[int mode\])                                                                    |                                                                                                                                         |
| public int leftMargin(\[int value\], \[AutoMode mode\])                                                     |                                                                                                                                         |
| public AutoMode leftMarginMode(\[AutoMode mode\])                                                           |                                                                                                                                         |
| public int leftMarginValue(\[int value\])                                                                   |                                                                                                                                         |
| public int leftMode(\[int value\])                                                                          |                                                                                                                                         |
| public int leftValue(\[int value\])                                                                         |                                                                                                                                         |
| public str name(\[str value\])                                                                              | Gets or sets the name that is used in code to identify a form, report, table, query, or other application object. |
| public int neededPermission(\[int value\])                                                                  |                                                                                                                                         |
| public int rightMargin(\[int value\], \[AutoMode mode\])                                                    |                                                                                                                                         |
| public AutoMode rightMarginMode(\[AutoMode mode\])                                                          |                                                                                                                                         |
| public int rightMarginValue(\[int value\])                                                                  |                                                                                                                                         |
| public SecurityKeyId securityKey(\[SecurityKeyId value\])                                                   |                                                                                                                                         |
| public int selection(\[int value\])                                                                         |                                                                                                                                         |
| public boolean skip(\[boolean value\])                                                                      | Sets or returns a value that indicates whether the control is skipped when the user presses the TAB key to move to the control.         |
| public str text(\[str value\])                                                                              |                                                                                                                                         |
| public int top(int value, \[int mode\])                                                                     |                                                                                                                                         |
| public int topMargin(\[int value\], \[AutoMode mode\])                                                      |                                                                                                                                         |
| public AutoMode topMarginMode(\[AutoMode mode\])                                                            |                                                                                                                                         |
| public int topMarginValue(\[int value\])                                                                    |                                                                                                                                         |
| public int topMode(\[int value\])                                                                           |                                                                                                                                         |
| public int topValue(\[int value\])                                                                          |                                                                                                                                         |
| public int type(\[int value\])                                                                              |                                                                                                                                         |
| public boolean underline(\[boolean value\])                                                                 | Sets or returns the underline property for the text in the control.                                                                     |
| public int userData(\[int value\])                                                                          |                                                                                                                                         |
| public int userDataItem(\[int value\])                                                                      |                                                                                                                                         |
| public int userDataItems(\[int value\])                                                                     |                                                                                                                                         |
| public int verticalSpacing(\[int value\], \[AutoMode mode\])                                                |                                                                                                                                         |
| public AutoMode verticalSpacingMode(\[AutoMode mode\])                                                      |                                                                                                                                         |
| public int verticalSpacingValue(\[int value\])                                                              |                                                                                                                                         |
| public int viewEditMode(\[int value\])                                                                      |                                                                                                                                         |
| public boolean visible(\[boolean value\])                                                                   |                                                                                                                                         |
| public int width(int value, \[int mode\])                                                                   | Gets or sets the width of the control.                                                                                                  |
| public int widthMode(\[int value\])                                                                         | Gets or sets the calculation mode of the width of the control.                                                                          |
| public int widthValue(\[int value\])                                                                        | Gets or sets the width of the control.                                                                                                  |
| public void registerOverrideMethod(str methodToOverride, str objectMethodToCall, \[Object overrideObject\]) |                                                                                                                                         |

## Method alignControl

Determines whether to align the control.

```xpp
public boolean alignControl([boolean value])
```

### Parameters - alignControl

value  

### Return Value - alignControl

true if the control should be aligned; otherwise, false.

### Remarks - alignControl

The upper-left corner of the control is aligned according to the longest label.

## Method allowEdit

Determines whether the user can change the contents of the control.

```xpp
public boolean allowEdit([boolean value])
```

### Parameters - allowEdit

value  

### Return Value - allowEdit

true if the control can be edited; otherwise, false.

### Remarks - allowEdit

When this property is set on a container control, modifications are disabled or enabled for all controls in the container.

## Method arrayIndex

```xpp
public int arrayIndex([int value])
```

### Parameters - arrayIndex

value  

### Return Value - arrayIndex

## Method autoDeclaration

Determines whether the system can declare a member variable that has the same name as the control.

```xpp
public boolean autoDeclaration([boolean value])
```

### Parameters - autoDeclaration

value  

### Return Value - autoDeclaration

true if the member variable can be declared for this control; otherwise, false.

### Remarks - autoDeclaration

Controls cannot have identical names.

## Method backgroundColor

Gets or sets the background color of the control.

```xpp
public int backgroundColor([int value])
```

### Parameters - backgroundColor

value  

### Return Value - backgroundColor

An integer that contains a packed RGB color.

### Remarks - backgroundColor

The integer that is returned contains a packed RGB color as follows:

-   The low-order byte contains a value for the relative intensity of red.
-   The second byte contains a value for green.
-   The third byte contains a value for blue.
-   The high-order byte must be zero.
-   The maximum value for a single byte is 255.

## Method backStyle

Determines whether the control background can be transparent.

```xpp
public int backStyle([int value])
```

### Parameters - backStyle

value  

### Return Value - backStyle

1 if the control background can be transparent; otherwise, 0.

## Method bold

Gets or sets the weight of font that is used to output text in the control.

```xpp
public int bold([int value])
```

### Parameters - bold

value  

### Return Value - bold

An integer value between zero and nine, inclusive.

### Remarks - bold

The integer that is returned contains the weight of the font as follows:

-   0 Use the default font weight.
-   1 Thin.
-   2 Extra-light.
-   3 Light.
-   4 Normal.
-   5 Medium.
-   6 Semibold.
-   7 Bold.
-   8 Extra-bold.
-   9 Heavy.

## Method bottomMargin

```xpp
public int bottomMargin([int value], [AutoMode mode])
```

### Parameters - bottomMargin

value  

<!-- -->

mode  

### Return Value - bottomMargin

## Method bottomMarginMode

```xpp
public AutoMode bottomMarginMode([AutoMode mode])
```

### Parameters - bottomMarginMode

mode  

### Return Value - bottomMarginMode

## Method bottomMarginValue

```xpp
public int bottomMarginValue([int value])
```

### Parameters - bottomMarginValue

value  

### Return Value - bottomMarginValue

## Method cacheDataMethod

```xpp
public int cacheDataMethod([int value])
```

### Parameters - cacheDataMethod

value  

### Return Value - cacheDataMethod

## Method caption

Gets or set the caption of the control.

```xpp
public str caption([str value])
```

### Parameters - caption

value  

### Return Value - caption

The string that is used as the caption of the control.

## Method characterSet

Gets or sets the character set of the font.

```xpp
public int characterSet([int value])
```

### Parameters - characterSet

value  

### Return Value - characterSet

An integer value that indicates the character set of the font.

### Remarks - characterSet

The values for the integer that is returned indicate the character set according to the following table:

| Value. | Description.         |
|--------|----------------------|
| 0      | ANSI\_CHARSET        |
| 1      | DEFAULT\_CHARSET     |
| 2      | SYMBOL\_CHARSET      |
| 77     | MAC\_CHARSET         |
| 128    | SHIFTJIS\_CHARSET    |
| 129    | HANGUL\_CHARSET      |
| 134    | GB2312\_CHARSET      |
| 136    | CHINESEBIG5\_CHARSET |
| 161    | GREEK\_CHARSET       |
| 162    | TURKISH\_CHARSET     |
| 163    | VIETNAMESE\_CHARSET  |
| 186    | BALTIC\_CHARSET      |
| 204    | RUSSIAN\_CHARSET     |
| 238    | EASTEUROPE\_CHARSET  |
| 255    | OEM\_CHARSET         |

The value in the following table is for the Korean language edition of Microsoft Windows.

| Value. | Description.   |
|--------|----------------|
| 130    | JOHAB\_CHARSET |

The values in the following table are for the Middle East language edition of Microsoft Windows.

| Value. | Description.    |
|--------|-----------------|
| 177    | HEBREW\_CHARSET |
| 178    | ARABIC\_CHARSET |

The value in the following table is for the Thai language edition of Microsoft Windows.

| Value. | Description.  |
|--------|---------------|
| 222    | THAI\_CHARSET |

The default character set is set to a value, depending on the current system locale. For example, when the system locale is English (United States), it is set as ANSI\_CHARSET. For more information, see the LOGFONT structure on the [MSDN website](https://go.microsoft.com/fwlink/?LinkID=85972).

## Method colorScheme

Gets or sets the color scheme of the control.

```xpp
public int colorScheme([int value])
```

### Parameters - colorScheme

value  

### Return Value - colorScheme

An integer between zero and two, inclusive.

### Remarks - colorScheme

The color scheme is defined according to the following table:

| Value. | Style.                        |
|--------|-------------------------------|
| 0      | Default.                      |
| 1      | The Microsoft Windows palette. |
| 2      | The true-color scheme.        |

## Method columns

```xpp
public int columns([int value])
```

### Parameters - columns

value  

### Return Value - columns

## Method configurationKey

Gets or sets the configuration key that is assigned to the control.

```xpp
public ConfigurationKeyId configurationKey([ConfigurationKeyId value])
```

### Parameters - configurationKey

value  

### Return Value - configurationKey

The identifier of the configuration key that is assigned to the control.

### Remarks - configurationKey

The configuration key is used to determine whether this control can be displayed. If the configuration key is disabled in the system, the control is not displayed in the form.

## Method containerId

Retrieves the ID of the parent container for the control.

```xpp
public int containerId()
```

### Return Value - containerId

The ID of the parent container.

## Method countryRegionCodes

```xpp
public str countryRegionCodes([str value])
```

### Parameters - countryRegionCodes

value  

### Return Value - countryRegionCodes

## Method countryRegionContextField

```xpp
public FieldId countryRegionContextField([FieldId value])
```

### Parameters - countryRegionContextField

value  

### Return Value - countryRegionContextField

## Method dataField

```xpp
public FieldId dataField([FieldId value])
```

### Parameters - dataField

value  

### Return Value - dataField

## Method dataMethod

```xpp
public str dataMethod([str value])
```

### Parameters - dataMethod

value  

### Return Value - dataMethod

## Method dataRelationPath

```xpp
public str dataRelationPath([str value])
```

### Parameters - dataRelationPath

value  

### Return Value - dataRelationPath

## Method dataSource

Gets or sets a data source that will be used by the control or the form.

```xpp
public int dataSource([AnyType value])
```

### Parameters - dataSource

value  

### Return Value - dataSource

The identifier of the data source that will be used.

## Method displayLength

```xpp
public int displayLength([int value], [AutoMode mode])
```

### Parameters - displayLength

value  

<!-- -->

mode  

### Return Value - displayLength

## Method displayLengthMode

```xpp
public AutoMode displayLengthMode([AutoMode mode])
```

### Parameters - displayLengthMode

mode  

### Return Value - displayLengthMode

## Method displayLengthValue

```xpp
public int displayLengthValue([int value])
```

### Parameters - displayLengthValue

value  

### Return Value - displayLengthValue

## Method displayTarget

```xpp
public int displayTarget([int value])
```

### Parameters - displayTarget

value  

### Return Value - displayTarget

## Method dragDrop

Determines whether to enable or disable drag-and-drop operations for the control.

```xpp
public int dragDrop([int value])
```

### Parameters - dragDrop

value  

### Return Value - dragDrop

1 if drag-and-drop operations are enabled; otherwise, false.

## Method enabled

Determines whether to enable or disable the object.

```xpp
public boolean enabled([boolean value])
```

### Parameters - enabled

value  

### Return Value - enabled

true if the object is enabled; otherwise, false.

### Remarks - enabled

The enabled property allows for controls to be enabled or disabled at run time. For example, you can disable objects that do not apply to the current state of the application. You can also disable a control that is used only for display purposes, such as an error message, which provides read-only information.

## Method enumType

```xpp
public EnumId enumType([EnumId value])
```

### Parameters - enumType

value  

### Return Value - enumType

## Method extendedDataType

```xpp
public ExtendedTypeId extendedDataType([ExtendedTypeId value])
```

### Parameters - extendedDataType

value  

### Return Value - extendedDataType

## Method font

Gets or sets the name of the font for the control to use.

```xpp
public str font([str value])
```

### Parameters - font

value  

### Return Value - font

The name of the font to use, such as Tahoma or Verdana.

## Method fontSize

Gets or sets the size of the font for the control to use.

```xpp
public int fontSize([int value])
```

### Parameters - fontSize

value  

### Return Value - fontSize

The height of the font in points.

## Method foregroundColor

Gets or sets the text color for the control to use.

```xpp
public int foregroundColor([int value])
```

### Parameters - foregroundColor

value  

### Return Value - foregroundColor

An integer that contains a packed RGB color.

### Remarks - foregroundColor

The integer that is returned contains a packed RGB color as follows:

-   The low-order byte contains a value for the relative intensity of red.
-   The second byte contains a value for green.
-   The third byte contains a value for blue.
-   The high-order byte must be zero.
-   The maximum value for a single byte is 255.

## Method framePosition

```xpp
public int framePosition([int value])
```

### Parameters - framePosition

value  

### Return Value - framePosition

## Method frameType

```xpp
public int frameType([int value])
```

### Parameters - frameType

value  

### Return Value - frameType

## Method height

Gets or sets the height of the control.

```xpp
public int height(int value, [int mode])
```

### Parameters - height

value  

<!-- -->

mode  

### Return Value - height

The height of the control in pixels.

### Remarks - height

Exact mode is used if the value parameter is omitted. Calculate the height according to the following table:

| Mode.            | Height calculation.                                                                       |
|------------------|-------------------------------------------------------------------------------------------|
| -1 Exact.        | The exact height in pixels of the controls is used.                                       |
| 0 Auto.          | The height of the control is calculated automatically and the value parameter is ignored. |
| 1 Column height. | The layout of the form determines the height of the control.                              |

The height and height calculation mode can be set separately.

## Method heightMode

Gets or sets a calculation mode for the height of the control.

```xpp
public int heightMode([int value])
```

### Parameters - heightMode

value  

### Return Value - heightMode

The calculation mode.

### Remarks - heightMode

Calculate the height according to the following table:

| Mode.          | Height Calculation.                                                                       |
|----------------|-------------------------------------------------------------------------------------------|
| Exact.         | The exact height in pixels of the controls is used.                                       |
| Auto.          | The height of the control is calculated automatically and the value parameter is ignored. |
| Column height. | The layout of the form determines the height of the control.                              |

The height of the control might change when the mode is set to auto or column height.

## Method heightValue

Gets or sets the height of the control.

```xpp
public int heightValue([int value])
```

### Parameters - heightValue

value  

### Return Value - heightValue

The height in pixels.

### Remarks - heightValue

The height of the control is not changed unless the exact height calculation mode is used.

## Method helpText

Gets or sets the help text to display at the bottom of the screen when a field or control is pointed to.

```xpp
public str helpText([str value])
```

### Parameters - helpText

value  

### Return Value - helpText

The string to be displayed at the bottom of the screen.

### Remarks - helpText

Set the HelpText property for an object by using the property sheet. The help text must not exceed 250 characters.

## Method hideFirstEntry

```xpp
public boolean hideFirstEntry([boolean value])
```

### Parameters - hideFirstEntry

value  

### Return Value - hideFirstEntry

## Method hierarchyParent

```xpp
public str hierarchyParent([str value])
```

### Parameters - hierarchyParent

value  

### Return Value - hierarchyParent

## Method id

Retrieves the ID of the control.

```xpp
public int id()
```

### Return Value - id

The ID of the control.

## Method isContainer

Retrieves a value that indicates whether the control is a container control.

```xpp
public boolean isContainer()
```

### Return Value - isContainer

A Boolean value that indicates whether the control is a container control.

## Method italic

```xpp
public boolean italic([boolean value])
```

### Parameters - italic

value  

### Return Value - italic

## Method item

```xpp
public int item([int value])
```

### Parameters - item

value  

### Return Value - item

## Method items

```xpp
public int items([int value])
```

### Parameters - items

value  

### Return Value - items

## Method left

```xpp
public int left(int value, [int mode])
```

### Parameters - left

value  

<!-- -->

mode  

### Return Value - left

## Method leftMargin

```xpp
public int leftMargin([int value], [AutoMode mode])
```

### Parameters - leftMargin

value  

<!-- -->

mode  

### Return Value - leftMargin

## Method leftMarginMode

```xpp
public AutoMode leftMarginMode([AutoMode mode])
```

### Parameters - leftMarginMode

mode  

### Return Value - leftMarginMode

## Method leftMarginValue

```xpp
public int leftMarginValue([int value])
```

### Parameters - leftMarginValue

value  

### Return Value - leftMarginValue

## Method leftMode

```xpp
public int leftMode([int value])
```

### Parameters - leftMode

value  

### Return Value - leftMode

## Method leftValue

```xpp
public int leftValue([int value])
```

### Parameters - leftValue

value  

### Return Value - leftValue

## Method name

Gets or sets the name that is used in code to identify a form, report, table, query, or other application object.

```xpp
public str name([str value])
```

### Parameters - name

value  
The name to assign to the control.

### Return Value - name

The name that is used in code to identify an application object.

### Remarks - name

The name property value of an object must meet the following criteria to avoid code conflicts:

-   It must start with a letter.
-   It cannot exceed 250 characters.
-   It can include numbers and underscore (\_) characters.
-   It cannot include punctuation or spaces.
-   Tables cannot have the same name as other public objects, such as extended data types, base enums, or classes.

## Method neededPermission

```xpp
public int neededPermission([int value])
```

### Parameters - neededPermission

value  

### Return Value - neededPermission

## Method rightMargin

```xpp
public int rightMargin([int value], [AutoMode mode])
```

### Parameters - rightMargin

value  

<!-- -->

mode  

### Return Value - rightMargin

## Method rightMarginMode

```xpp
public AutoMode rightMarginMode([AutoMode mode])
```

### Parameters - rightMarginMode

mode  

### Return Value - rightMarginMode

## Method rightMarginValue

```xpp
public int rightMarginValue([int value])
```

### Parameters - rightMarginValue

value  

### Return Value - rightMarginValue

## Method securityKey

```xpp
public SecurityKeyId securityKey([SecurityKeyId value])
```

### Parameters - securityKey

value  

### Return Value - securityKey

## Method selection

```xpp
public int selection([int value])
```

### Parameters - selection

value  

### Return Value - selection

## Method skip

Sets or returns a value that indicates whether the control is skipped when the user presses the TAB key to move to the control.

```xpp
public boolean skip([boolean value])
```

### Parameters - skip

value  
The value to assign to the skip property of the control; optional.

### Return Value - skip

true if the control is skipped when the user presses the TAB key to move to the control; otherwise, false.

## Method text

```xpp
public str text([str value])
```

### Parameters - text

value  

### Return Value - text

## Method top

```xpp
public int top(int value, [int mode])
```

### Parameters - top

value  

<!-- -->

mode  

### Return Value - top

## Method topMargin

```xpp
public int topMargin([int value], [AutoMode mode])
```

### Parameters - topMargin

value  

<!-- -->

mode  

### Return Value - topMargin

## Method topMarginMode

```xpp
public AutoMode topMarginMode([AutoMode mode])
```

### Parameters - topMarginMode

mode  

### Return Value - topMarginMode

## Method topMarginValue

```xpp
public int topMarginValue([int value])
```

### Parameters - topMarginValue

value  

### Return Value - topMarginValue

## Method topMode

```xpp
public int topMode([int value])
```

### Parameters - topMode

value  

### Return Value - topMode

## Method topValue

```xpp
public int topValue([int value])
```

### Parameters - topValue

value  

### Return Value - topValue

## Method type

```xpp
public int type([int value])
```

### Parameters - type

value  

### Return Value - type

## Method underline

Sets or returns the underline property for the text in the control.

```xpp
public boolean underline([boolean value])
```

### Parameters - underline

value  
The value to assign to the underline property of the control; optional.

### Return Value - underline

true if the text in the control is underlined; otherwise, false.

## Method userData

```xpp
public int userData([int value])
```

### Parameters - userData

value  

### Return Value - userData

## Method userDataItem

```xpp
public int userDataItem([int value])
```

### Parameters - userDataItem

value  

### Return Value - userDataItem

## Method userDataItems

```xpp
public int userDataItems([int value])
```

### Parameters - userDataItems

value  

### Return Value - userDataItems

## Method verticalSpacing

```xpp
public int verticalSpacing([int value], [AutoMode mode])
```

### Parameters - verticalSpacing

value  

<!-- -->

mode  

### Return Value - verticalSpacing

## Method verticalSpacingMode

```xpp
public AutoMode verticalSpacingMode([AutoMode mode])
```

### Parameters - verticalSpacingMode

mode  

### Return Value - verticalSpacingMode

## Method verticalSpacingValue

```xpp
public int verticalSpacingValue([int value])
```

### Parameters - verticalSpacingValue

value  

### Return Value - verticalSpacingValue

## Method viewEditMode

```xpp
public int viewEditMode([int value])
```

### Parameters - viewEditMode

value  

### Return Value - viewEditMode

## Method visible

```xpp
public boolean visible([boolean value])
```

### Parameters - visible

value  

### Return Value - visible

## Method width

Gets or sets the width of the control.

```xpp
public int width(int value, [int mode])
```

### Parameters - width

value  

<!-- -->

mode  

### Return Value - width

The width of the control in pixels.

### Remarks - width

Exact mode is used if the value parameter is omitted. Calculate the width according to the following table:

| Mode.           | Width calculation.                                                                       |
|-----------------|------------------------------------------------------------------------------------------|
| -1 Exact.       | The exact width in pixels of the controls is used.                                       |
| 0 Auto.         | The width of the control is calculated automatically and the value parameter is ignored. |
| 1 Column width. | The layout of the form determines the width of the control.                              |

The width and width calculation mode can be set separately.

## Method widthMode

Gets or sets the calculation mode of the width of the control.

```xpp
public int widthMode([int value])
```

### Parameters - widthMode

value  

### Return Value - widthMode

An integer value that indicates the current calculation mode.

### Remarks - widthMode

Calculate the width according to the following table:

| Mode.         | Width Calculation.                                                                       |
|---------------|------------------------------------------------------------------------------------------|
| Exact.        | The exact width in pixels of the controls is used.                                       |
| Auto.         | The width of the control is calculated automatically and the value parameter is ignored. |
| Column width. | The layout of the form determines the width of the control.                              |

The width of the control might change when the mode is set to auto or column width.

## Method widthValue

Gets or sets the width of the control.

```xpp
public int widthValue([int value])
```

### Parameters - widthValue

value  

### Return Value - widthValue

The width in pixels of the control.

### Remarks - widthValue

To change the width of the control, use the exact width calculation mode.

## Method registerOverrideMethod

```xpp
public void registerOverrideMethod(str methodToOverride, str objectMethodToCall, [Object overrideObject])
```

### Parameters - registerOverrideMethod

methodToOverride  

<!-- -->

objectMethodToCall  

<!-- -->

overrideObject  

