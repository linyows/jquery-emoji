jQuery Emoji Plugin
===================

A simple, lightweight jQuery plugin for [emoji](http://www.emoji-cheat-sheet.com/) parser. :tongue:

Installation
------------

Include script after the jQuery library (unless you are packaging scripts somehow else):

```html
<script src="/path/to/jquery.emoji.js"></script>
```

Usage
-----

Very simple.

```html
<script type="text/javascript">
$(document).ready(function(){
  $('.comment').each(function(i, d){
    $(d).emoji();
  });
});
</script>
...
<div class="comment">
  <p>:+1:</p>
</div>
```

Contributing
------------

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Added some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request

Author
------

[linyows](https://github.com/linyows)

License
-------

Copyright (c) 2012 linyows Licensed under the MIT license.
