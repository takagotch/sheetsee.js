### sheetsee.js
---
https://github.com/jlord/sheetsee.js

```js
document.addEventListener('DOMContentLoaded', function(){
  var URL = 'YOURSPREADSHEETSKEYHERE'
  Tabletop.init({key: URL, callback: callback, simpleSheet: true})
})

function callback(data){
}
```

```
<html>
  <head>
  </head>
  <body>
  <div id="placeholder"></div>
  <script id="placeholder" type="text/html">
  </script>
  <script type="text/javascript">
    document.addEventListener('DOMContentLoaded', function(){
      var URL = 'YOURSPREADSHEETSKEYHERE'
      Tabletop.init( { key: URL, callback: myData, simpleSheet: true } )
    })
    function myData(data){}
  </script>
  </body>
</html>
```

```
[{"name":"Coco","breed":"Teacup Maltese","kind":"Dog","cuddlability":"5","lat":"37.74832","long":"-122.402158","picurl":"http://distilleryimage8.s3.amazonaws.com/98580826813011e2bbe622000a9f1270_7.jpg","hexcolor":"#ECECEC","rowNumber":1}...]
```


