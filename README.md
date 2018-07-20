# jquery-birthday-picker

A lightweight jQuery plugin which allows the user to pick the birthday from customizable dropdown select lists. Forked from https://www.jqueryscript.net/time-clock/Customizable-Dropdown-Birthday-Picker-Plugin-with-jQuery.html

## How to use it:
1. Include jQuery Javascript library and the jQuery Birthday Picker plugin in the document.

```
<script src="js/jquery-birthday-picker.js"></script>
```

2. Create an empty element that will be served as a container.
```
<div id="demo"></div>
```
3. Initialize the birthday picker with default settings.
```
$("#demo").birthdayPicker(); 
```
4. Optional settings to customize the birthday picker.
```
$("#demo").birthdayPicker({
    maxAge: 120,
    minAge: 18,    
    dateFormat: "middleEndian",
    monthFormat: "number",
    placeholder: true,
    defaultDate: false,
    sizeClass: "span2"
});	
```


