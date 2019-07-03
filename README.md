# jQuery-ResponsiveFlipper
Responsive flipper countdown

## Demo
https://codepen.io/ArtZ91/pen/ewVNJM

## Features
Font based flipper. Possible to change font css properties.
Possible to add custom color schemes.
Responsive width to parent container by font size fitting.
Bootstrap modal compatible.

## Usage example

```HTML

<link rel="stylesheet" href="style.css">

<div id="myFlipper" class="flipper" 
     data-reverse="true"
     data-datetime="2020-01-01 00:00:00" 
     data-template="ddd|HH|ii|ss" 
     data-labels="Days|Hours|Minutes|Seconds"></div>

<script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/3.4.1/jquery.min.js"></script>
<script src="jquery.flipper-responsive.js"></script>
<script>
  jQuery(function($){
    $('#myFlipper').flipper('init');
  });
</script>
```

## Data attributes

### reverse (default false) - enable countdown mode

### datetime (default 'now') - target date

### labels (default 'Hours|Minutes|Seconds') - digit groups captions

### template (default 'HH:ii:ss')

`|` - delimiter `[:]`

`ddd` - "days left", three sections `[0][0][0]`-`[9][9][9]`

`dd` - "days left" or "date of month", two sections `[0][0]`-`[9][9]`

`HH` - hours, two sections `[0][0]`-`[2][3]`

`ii` - minutes, two sections `[0][0]`-`[5][9]`

`ss` - seconds, two sections `[0][0]`-`[5][9]`

`d` - "date of month", two digits, one section `[00]`-`[31]`

`H` - hours, two digits, one section `[00]`-`[23]`

`i` - minutes, two digits, one section `[00]`-`[59]`

`s` - seconds, two digits, one section `[00]`-`[59]`


## Compatibility

- Chrome
- Safari
- Edge 
- IE11 (broken animation)
