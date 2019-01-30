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
```

```
```

```
```

