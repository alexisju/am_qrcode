## Another plugin for Shaarli to display qrcode

This plugin allows the user to open a popup displaying the qrcode of the URL of a link.

This plugin is based on default shaarli's qrcode plugin. It differs by CSS and how qrcode is displayed.

### Installation/configuration
Clone this repository inside your `tpl/plugins/` directory, or download the archive and unpack it there.  
The directory structure should look like:

```
+-- tpl
    +-- plugins
        +-- qrcode-albinomouse
            +-- README.md
			+-- qr-1.1.3.js
			+-- qr-1.1.3.min.js
			+-- qrcode.html
			+-- qrcode.php
			+-- qrcode.png
			+-- shaarli-qrcode.js
			
```

To enable the plugin, add `'qrcode-albinomouse'` to your list of enabled plugins in `data/options.php` (`PLUGINS` array)
. This should look like:

```
$GLOBALS['config']['PLUGINS'] = array('social', 'any_other_plugin', 'qrcode-albinomouse')
```
