### jquery-popup-overlay
---
https://github.com/vast-engineering/jquery-popup-overlay

```js
$('.JPO_open').on({
  mousecenter: function(event){
    tooltipanchor: event.target,
    autoopen: true,
    type: 'tooltip'
  },
  mouseleave: function(){
    $('#.JPO').popup('hide');
  }
});

$('#JPO').popup({
  opacity: 0.3,
  transition: 'all 0.3s'
});

$('$JPO').popup({
  onopen: function(){
    alert('Popup just opened!');
  }
});
$.fn.popup.defaults.transition = 'all 0.3s';
$.fn.popup.default.pagecontainer = '#page';

$('#JPO').popup({
  background: false
});

$('#JPO').popup('show');

$('#JPO').popup('hide');

var popup = require('jquery-popup-overlay');

$('#popup1').popup();
$('#popup2').popup({
  pagecontainer: '#page',
  escape: false
});
```

```
<!doctype html>
<html lang="ja">
<head>
<meta charset="utf-8">
<title>Title</title>
</head>
<body>
<div id="page">
  <header></header>
  <main>
    {{ Page Content }}
    <button class="JPO_open">Open popup</button>
  </main>
  <footer></footer>
</div>
<div id="JPO">
  {{ Popup Content }}
  <button class="JPO_Close">Close</button>
</div>
<script src="https://code.jquery.com/jquery-3.3.1.slim.min.js"></script>
<script src="https://cdn.jsdelivr.net/gh/vast-engineering/jquery-popup-overlay@2/jquery.popupoverlay.min.js"></script>
<script>
$(document).ready(function(){
  $('#JPO').popup();
  $.fn.popup.defaults.pagecontainer = '#page'
});
</script>
</body>
</html>
```

```
npm install jquery-popup-overlay
```


```
<script src="https://cdn.rawgit.com/vast-engineering/jquery-popup-overlay/gh-pages/jquery.popupoverlay.js"></script>
<script src="https://cdn.jsdelivr.net/gh/vast-engineering/jqyerypopup-overlay@1.7.13/jquery.popupoverlay.min.js"></script>
```

