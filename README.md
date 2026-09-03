# CKEditor 5 Plugin Pack

CKEditor 5 Plugin Pack is an official set of free plugins extending
functionalities of CKEditor 5 for Backdrop, maintained by CKSource.

## Installation

- Install this module using the official [Backdrop CMS instructions](https://backdropcms.org/guide/modules).
- Open Administration > Configuration > Content authoring > Text formats and editors (admin/config/content/formats).
- Choose a text format to edit.
- Drag and drop widgets you want to use from "Available buttons" to the "Active toolbar".

## Per plugin

### Fonts

This module enables the font plugin for CKEditor 5, which allows editors to
change font family, size, color, and background color.

**Important caveat:** due to the way the Filter system works, the font family,
color, and background color options will only work if **Limit allowed HTML tags**
is turned off.

The plan is to also port over either the WYSIWYG Filter or the HTML Purifier
Filter modules to relieve this constraint.

### Highlight

It integrates the official Highlight plugin with CKEditor 5. The highlight
feature lets you mark text fragments with different colors. You can use it both
as a marker (to change the background color) and as a pen (to change the text
color).

### Page Break

It integrates the official Page Break plugin with CKEditor 5. It will insert
a div element with a page break class. Other modules will need to provide
display functionality.

### Media Embed

It integrates the official Media Embed plugin with CKEditor 5. It allows video
links such as with Youtube to be converted to oEmbed format. For example,

`<oembed url=""></oembed>`

The link can either be entered in the widget or directly into the editor window.

A third-party module is required to display the videos after saving. One option
is [Video Filter](https://backdropcms.org/project/video_filter).

## Features

The Drupal version of this module has a few more modules and features.

### Already in Core

- Block Indentation
- Bookmarks
- Emoji

### Not yet

- Auto Image
- Find and Replace
- Full Screen
- Layout Tables
- Link Attributes
- Paste Markdown
- Restricted Editing
- Select All
- Templates
- Text Transformation
- To-do Document List
- Word count
- WProofreader grammar and spell checker

## Issues

Bugs and Feature requests should be reported in the [Issue Queue](https://github.com/backdrop-contrib/ckeditor_plugin_pack/issues)

## Current Maintainers

- [Herb v/d Dool](https://github.com/herbdool)
- [Richard Peacock](https://github.com/swampopus)
- Co-maintainers welcome

## Credits

- Created for Backdrop by [Herb v/d Dool](https://github.com/herbdool) and
  [Richard Peacock](https://github.com/swampopus).
- Inspired and borrowed from [equivalent Drupal module](https://www.drupal.org/project/ckeditor5_plugin_pack).

## License

This project is GPL v2 software. See the LICENSE.txt file in this directory for complete text.
