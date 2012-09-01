jquery.emoji
============

A simple, lightweight jQuery plugin for [emoji](http://www.emoji-cheat-sheet.com/) parser. :tongue:

Installation
------------

Include script after the jQuery library (unless you are packaging scripts somehow else):

```html
<script src="/path/to/jquery.emoji.js"></script>
```

Usage
-----

```html
$(document).ready(function(){
  $('.comment').each(function(i, d){
    $(d).emoji();
  });
});

<div class="comment">
  <p>:+1:</p>
</div>
```

Author
------

[linyows](https://github.com/linyows)

License
-------

[The MIT License](https://raw.github.com/linyows/jquery-emoji/master/LICENSE)
