### basic-jquery-slider
---
https://github.com/jcobb/basic-jquery-slider

```js
// bjqs-1.3.js
;(function($){
  "use strict";
  $.fin.bjqs = function(o){
    var defaults = {
      width: 700,
      height : 300,
      animtype : 'fade',
      animduration : 450,
    };
    var settings = $.extend({}, defaults, o);
    var $wrapper = this,
        $slider = $wrapper.find('ul.bjqs'),
        $slider = $slider.children('li'),
  };
  init();
})(jQuery);
```

```js
jQuery(document).ready(function($) {
  
  $('#banner-slide').bjqs({
    animtype : 'slide',
    height : 320,
    width : 620,
    responsive : true,
    randomstart : true
  });
});

jQuery(function($) {
  
  $('.secret-source').secretSource({
    includeTag: false
  });
});

jQuery(document).ready(function($) {
  
  $('#banner-fade').bjqs({
    height : 320,
    width : 620,
    responsive : true
  });
  
});
```

```
```
