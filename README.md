noahlu_firebug_lite
===================

Doing some bug-fix for official "Firebug Lite" to make it work under most pages.


##How To Use
Add the link below to your browser's Bookmarks Category(or Favorite Category).   
<a href="javascript:(function(d){var s = d.createElement('script');s.src='https://raw.github.com/noahlu/noahlu_firebug_lite/master/src/noahlu-firebug-lite-debug.js';d.getElementsByTagName('head')[0].appendChild(s);})(document)">Noahlu Firebug Lite</a>   
or you may use the bookmarklet script directly:  
javascript:(function(d){var s = d.createElement('script');s.src='https://raw.github.com/noahlu/noahlu_firebug_lite/master/src/noahlu-firebug-lite-debug.js';d.getElementsByTagName('head')[0].appendChild(s);})(document)

##File Minify
$ ant clean init minify