# ACF Fold Flexible Content

A simple plugin for enhancing the [Advanced Custom Fields Flexible Content Field](http://www.advancedcustomfields.com/add-ons/flexible-content-field/). Collapsed flexible content panels and showing icons representing each field type.

![Screenshot](https://raw.github.com/urre/acf-fold-flexible/master/screenshot-1.png)

![Gif](https://dl.dropboxusercontent.com/u/1162759/acf-fold-flexible.gif)

## Features
+ Better overview of Flexible Content Fields layout panels
+ Collapsed flexible content layouts initially
+ Displays icons using [Dashicons](http://melchoyce.github.io/dashicons) which fields each layout contains, supports all native ACF fields types

## Install
1. Install plugin from the [WordPress plugin directory](http://wordpress.org/plugins/acf-fold-flexible-content/)

## Install manually
1. Download [zip](https://github.com/urre/acf-fold-flexible/archive/master.zip) and extract
2. Rename the folder from `acf-fold-flexible-content-master` to `acf-fold-flexible-content`
3. Upload the plugin to your plugins directory (/wp-content/plugins)
4. Activate the plugin

## Uninstall
1. Deactivate plugin

## Changelog
+ 1.1.2: Fixed an issue were newly added field layouts did not get icon tooltips. Also fixed so newly added don't always stay blue, not until clicked.
+ 1.1.1: Minor tooltip adjustment. Smaller arrow and moved it a bit above the Field Group toggle list.
+ 1.1.0: Better support for both ACF and ACF PRO
+ 1.0.3: Bug fix. Solves panel active states for ACF PRO 5.1.0
+ 1.0.2: Bug fix: the css and javascripts did not load correctly after 4.0. Now fixed.
+ 1.0.1: Added support for fields: Gallery, url and email
+ 1.0: No longer beta. Added Support for Advanced Custom Fields PRO
+ 0.15: Field type tooltips: replace underscores with spaces
+ 0.1: First version released

## Todo
- [x] Support for Advanced Custom Fields PRO
- [x] Change tooltip when fieldgroup is expanded
- [ ] Fix so icons line up in the same order as the fields inside
- [ ] Support new ACF fields
