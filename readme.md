# [SMOF - Slightly Modded Options Framework](http://aquagraphite.com/2011/09/slightly-modded-options-framework/)
# Version 1.4

SMOF is a back-end framework for creating and managing options inside WordPress themes. It cuts off the process of developing your own admin framework and give you more time to actually focus on building your theme. SMOF comes bundled with plentiful of options that should serve most of the needs of any modern theme authors.

The main feature of SMOF is its intuitive, user-friendly interface that aims to look as native as possible to WordPress. Additionally, it comes loaded with some awesome features that makes it even more usable to you as a theme author. 

Some of these are:

* Native Media Library Uploader
* Drag and Drop Unlimited Slider Options
* Layout Manager
* Tiles
* Backup and Restore

SMOF works with the latest version of WordPress (currently at 3.3.1) and is being actively developed for further improvements.

## Credits
SMOF is heavily based on some of these available frameworks.

* [Thematic Options Panel](http://wptheming.com/2010/11/thematic-options-panel-v2/)
* [KIA Thematic Options Panel](https://github.com/helgatheviking/thematic-options-KIA)
* [Woo Themes](http://woothemes.com/)
* [Option Tree](http://wordpress.org/extend/plugins/option-tree/)

## License
[WTFPL](http://sam.zoy.org/wtfpl/)

Do whatever you want with it. A linkback would be nice :)

## Contacts

Twitter: http://twitter.com/syamilmj

Website: http://aquagraphite.com

## Changelog

**v1.4**

* add folding checkbox group option (credits to plovs - https://github.com/plovs)
* add sample grouped options
* add transfer option
* fix css quirks on some options
* single call to admin/admin.php from functions.php
* unique database name for options & backup
* replaced ereg_replace function (deprecated in PHP 5.3)
* uses add_theme_page() to replace add_submenu_page()
* reorganized files, paths etc
* delete background option
* delete child types
* everything a bit faster now
* change reset method

**v1.3**

* add backup & restore options
* simple tooltip for typography options
* fix *really* long title on slide header
* fix when slider is empty (no longer returns NaN)
* smoother sliding animations when adding/deleting sliders
* add template-debug for debugging

**v1.2.2**

* replace admin-interface.php with current stable

**v1.2.1**

* actually introduced more errors due to some crazy file swapping (I think)

**v1.2**

* Change "background" to "tiles"
* Add support for jpg images for Tiles option

**v1.1 13 Nov 2011**

* add new option "background"
* typography option may now be called individually

**v1.0 10 Nov 2011**

* add version number
* shave off most if not all of the "undefined index" errors
* disable/enable layout block by drag and drop
* slider title will update upon typing







