# Unraid Simple Custom WebUI CSS Plugin

**Only tested on Unraid 7.2+**

This plugin provides a simple, persistent way to inject custom CSS globally into the Unraid WebGUI. Allows you to customize Unraid's WebUI. It is built for Unraid 7.2 and later. (For older Unraid versions <=7.1.4, you can use the more powerful [Theme Engine](https://forums.unraid.net/topic/87126-plugin-theme-engine-a-webgui-styler/) plugin by Skitals)

Note that this plugin is **NOT** a replacement for Theme Engine, it just provide an textarea to input and store a single CSS file then include it in `<head>` on every page. You need to manage locally by yourself if you have multiple CSS files to switch.

## Install
Navigate to Plugins -> Install Plugin and input this URL:
```
https://github.com/WuSiYu/unraid-custom-css/raw/refs/heads/master/custom.css.plg
```


## Usage and Configuration
1. Navigate to Settings -> Utilities -> Custom WebUI CSS.
2. Paste your custom CSS code into the large text field.
3. Click Apply & Save.


I also provide my own CSS config as an example (see [example.css](./example.css)):

<img src="screenshot.png" alt="screenshot">
