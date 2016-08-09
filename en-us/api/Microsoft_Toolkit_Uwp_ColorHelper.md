---
permalink: /en-US/api/Microsoft_Toolkit_Uwp_ColorHelper.htm
title: Microsoft.Toolkit.Uwp.ColorHelper API 
description: API page for Microsoft.Toolkit.Uwp.ColorHelper
keywords: windows, app, toolkit, UWP, API
layout: default
search.product: eADQiWindows 10XVcnh
---


# ColorHelper class

This class provides static helper methods for colors.

## Members

The **ColorHelper** class has this types of members

* [methods](#methods)

### methods

#### ToColor(System.String colorString)

Returns a color based on XAML color string.

##### parameters



| name | description | type |
#### ToHex(Windows.UI.Color color)

Converts a Color value to a string representation of the value in hexadecimal.

##### parameters



| name | description | type |
#### ToInt(Windows.UI.Color color)

Returns the color value as a premultiplied Int32 - 4 byte ARGB structure.

##### parameters



| name | description | type |
#### ToHsl(Windows.UI.Color color)

Converts an RGBA Color the HSL representation.

##### parameters



| name | description | type |
#### ToHsv(Windows.UI.Color color)

Converts an RGBA Color the HSV representation.

##### parameters



| name | description | type |
#### FromHsl(System.Double hue,System.Double saturation,System.Double lightness,System.Double alpha)

Returns a Color struct based on HSL model.

##### parameters



| name | description | type |
#### FromHsv(System.Double hue,System.Double saturation,System.Double value,System.Double alpha)

Returns a Color struct based on HSV model.

##### parameters



| name | description | type |