# Easy Numeric
____
## Description
Pure JS script!
Allows to replace all
```html
<input type="number">
``` to
```html
<input type="text">
```
much easier and with some improvements

You can use attributes right in HTML code!
For example: min, max, step, placeholder, style, class, readOnly

Now it's impossible to focus element with readOnly attribute
Also, you can set special class to not use this script for some of inputs
____
## Installation
firstly, create your HTML _( everything except "type" isn't required )_ :
```html
  <input type="number" step="5" min="-50" max="50" placeholder="input something" class="a b c d e">
```
then, just connect js and call it
```html
<script src="easyNumeric.js"></script>
<script> new SNumeric(  );</script>
```
____
## Options
All options and their defaults :
```html
<script> new SNumeric( {
  ignore : 'notSNumeric', // elements with this class will be ignored
  oninput: function(  ){  }, // function oninput for every element
  onblur : function(  ){  }, // function onblur for every element
  onfocus: function(  ){  }, // function onfocus for every element
  onclick: function(  ){  }, // function onclick for every element
  placeholder: undefined,    // you can set the same placeholder for each input
} );</script>
```
____
## Preview [sewaca.github.io](https://sewaca.github.io/easyNumeric)
