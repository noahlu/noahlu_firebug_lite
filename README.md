noahlu_firebug_lite
===================

Doing some bug-fix for official "Firebug Lite" to make it work under most pages.


##How To Use
Add the link below to your browser's Bookmarks Category(or Favorite Category).   
<a href="javascript:(function(d){var s = d.createElement('script');s.src='https://getfirebug.com/firebug-lite-debug.js';d.getElementsByTagName('head')[0].appendChild(s);})(document)">Bookmark</a>

##File Minify
$ ant clean init minify