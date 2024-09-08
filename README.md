# Selectbox 1.x
A JavaScript selectbox library.

## Usagge
```html
<!DOCTYPE html>
<html>
  <head>
    <script type="text/javascript" src="/path/to/libs/jquery.min.js"></script>
    <script type="text/javascript" src="'/path/to/libs/selectbox-1.0.min.js"></script>
  </head>
  <body>
    <select id="example1" class="default" name="example1">
      <option value="day">Day</option>
      <option value="night">Night</option>
    </select>
  
    <select id="example2" class="default" name="example2">
      <option value="left">Left</option>
      <option value="right">Right</option>
    </select>
  
    <script>
      $('#example1, #example2').selectbox();
    </script>
  </body>
</html>
```
