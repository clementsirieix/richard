# Richard
Material Color Palette Generator

## Installing

```shell
bower install richard
```

Or by downloading the .scss files.

## How to use ?

1. Import the script
``@import "_richard.scss";``
2. Create a new palette
``@include generate-palette($color);``
Or
``@include generate-palette($color, $variant);``
3. Include in your scss
``@include richard($colorNumber, $type);``

## Values

* $color 
The color name set by Google : [google.com/design](http://www.google.com/design/spec/style/color.html/)

* $variant
The number for accessing different variants (vanilla from 1 to 3)

* $type 
For selecting ``hue`` or ``accent``

* $colorNumber 
For the selecting the primary hue or accent ``1``, the lighter hue or accent ``2`` or the darker hue ``3``

## See more

Link to an article about the script: [not available for now](http://www.google.com) (French).