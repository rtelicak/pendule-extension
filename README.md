#pendule extension ruler fix

Ruler tool fix for popular web dev chrome [chrome extension pendule][1].

## how to:

 - navigate to chrome extension on your file system
     - ubuntu: `~/.config/google-chrome/Default/Extensions/gbkffbkamcejhkcaocmkdeiiccpmjfdi/1.0.0_0`
     - osx: `/Users/rmn/Library/Application Support/Google/Chrome/Default/Extensions/gbkffbkamcejhkcaocmkdeiiccpmjfdi/1.0.0_0`
 - replace *content_script_top_frame.js* file with one from this repo
 - same thing with *ruler.css* file in *injected-css* folder
 - disable/enable pendule
     
  [1]: https://chrome.google.com/webstore/detail/pendule/gbkffbkamcejhkcaocmkdeiiccpmjfdi