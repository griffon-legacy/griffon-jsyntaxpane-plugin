Enables the usage of [JSyntaxPane](http://code.google.com/p/jsyntaxpane/) with any `JEditorPane`.

![Image](http://docs.codehaus.org/images/icons/emoticons/forbidden.gif) **Warning** This plugin requires JDK6 to be installed, it will also constrain the running environment to JRE6 or above. 

# Usage #

This plugin does not add any new nodes however it enables any `JEditorPane` to be syntax aware just by specifying a suitable value for its `contentType:` property, for example `"text/java"` or `"text/groovy"`. Additional properties can be configured in `griffon-app/conf/Config.groovy`, for example|

# History #

| Version | Notes                 |
| ------- | --------------------- |
| 0.1     | Initial release       | 
| 0.2     | griffon 0.9.5 support |
