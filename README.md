
Integrates JSyntaxPane
----------------------

Plugin page: [http://artifacts.griffon-framework.org/plugin/jsyntaxpane](http://artifacts.griffon-framework.org/plugin/jsyntaxpane)


Enables the usage of [JSyntaxPane][1] with any `JEditorPane`.


Usage
-----

This plugin does not add any new nodes however it enables any `JEditorPane` to be syntax aware just by specifying a suitable
value for its `contentType:` property, for example `"text/java"` or `"text/groovy"`. Additional properties can be configured in
`griffon-app/conf/Config.groovy`, for example

        syntaxpane.props.'LineNumbers.Foreground' = '0xFF0000'
        syntaxpane.props.'LineNumbers.Background' = '0x000000'

[1]: http://code.google.com/p/jsyntaxpane/

