Extended version of 
http://dl.dropbox.com/u/143355/datepicker/datepicker.html 
add 
- current
- disableDays
- disableAbove
- disableBelow

## Example ##

```javascript
var options = {
    current: '01.08.2012',
    disableAbove: '31.08.2012',
    disableBelow: '01.08.2012'
}; 
```
Options syntax depands on parse method if you parse your date format
```
    dd.mm.YYY - current: '01.08.2012'
    YYY-mm-dd - current: '2012-08-01'
    dd/mm/YYY - current: '01/08/2012'
```
If you want to set datepicker to single file
```javascript
$('#date').datepicker(options);
```
or set to multiple files use date-datepicker selector
```html
<input class="input-xlarge" data-datepicker="datepicker" type="text" value="" />
<input class="input-xlarge" data-datepicker="datepicker" type="text" value="12.03.2012" />
```
