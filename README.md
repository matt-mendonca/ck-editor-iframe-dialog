CK Editor iFrame Dialog Field
=============================

## Overview
This module adds in the iFrame dialog field plugin for CK Editor, meaning it allows CK Editor dialog popups to be populated with and iframe, as opposed to hardcoding the content. In short, this module does not provide any functionality on its own.

## Installation
- Do the standard module install steps.
- Get the correct version of the plugin from http://ckeditor.com/addon/iframedialog that is compatible with the installed version of CK Editor.
- Create a folder in sites/all/libraries called ckeditor\_iframe\_dialog\_field.
- Create a subfolder called plugins
- Create a sub subfolder called iframedialog.
- In the iframedialog folder, place the plugin.js file from the iframedialog download. 
- The file path should be sites/all/libraries/ckeditor\_iframe\_dialog\_field/plugins/iframedialog/plugin.js.

## Configuration
Make sure to enable the iframe dialog field plugin for any text formats that requires iframe dialogs. Example to configure for Full Text:

- Go to admin/config/content/ckeditor/edit/Full
- Under Editor Appearance, then sub heading Plugins, enable CKEditor iFrame Dialog Field