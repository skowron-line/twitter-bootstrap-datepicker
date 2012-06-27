Extended version of 
http://dl.dropbox.com/u/143355/datepicker/datepicker.html 
add 
- current
- disableDays
- disableAbove
- disableBelow

```javascript
var options = {
    current: '01.08.2012',
    disableAbove: '31.08.2012',
    disableBelow: '01.08.2012'
}; 
```
```javascript
$('#date').datepicker(options);
```

OR
```html
<input class="input-xlarge" data-datepicker="datepicker" type="text" value="" />
<input class="input-xlarge" data-datepicker="datepicker" type="text" value="12.03.2012" />
```
