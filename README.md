## Another plugin for Shaarli to display qrcode

This plugin allows the user to open a popup displaying the qrcode of the URL of a link.

This plugin is based on default shaarli's qrcode plugin. It differs by CSS and how qrcode is displayed.

### Installation/configuration

Clone this repository inside your `tpl/plugins/` directory, or download the archive and unpack it there.  
The directory structure should look like:

```
└── tpl
	└── plugins
		└── am_qrcode
			├── README.md
			├── qr-1.1.3.js
			├── qr-1.1.3.min.js
			├── qrcode.html
			├── qrcode.php
			├── qrcode.png
			└── shaarli-qrcode.js
			
```

To enable the plugin, just check it in the plugin administration page.

You can also add `am_qrcode` to your list of enabled plugins in `data/config.json.php`
(`general.enabled_plugins` list).

This should look like:

```
"general": {
  "enabled_plugins": [
    "am_qrcode",
    [...]
  ],
}
```
