# jQuery-ResponsiveFlipper
Responsive flipper countdown

## Demo
https://codepen.io/ArtZ91/pen/ewVNJM

## Features
Font based flipper. Possible to change font css properties.
Possible to add custom color schemes.
Responsive width to parent container by font size fitting.
Bootstrap modal compatible.

## Usage

```HTML

<link rel="stylesheet" href="style.css">

<div id="myFlipper" class="flipper" 
     data-datetime="2020-01-01 00:00:00" 
     data-template="ddd|HH|ii|ss" 
     data-labels="Days|Hours|Minutes|Seconds"></div>

<script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/3.4.1/jquery.min.js"></script>
<script src="jquery.flipper-responsive.js"></script>
```

``` Javascript
$('#myFlipper').flipper('init');
```

## Compatibility

- Chrome
- Edge
