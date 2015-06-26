This is a fork of the Atom meteor-api package for personal use.

Meteor API for the Atom Editor
=======================================

Meteor javascript with autocomplete, code snippets, color-coded grammar, and syntax highlighting.
---------------------------------------
#### Meteor API Version  

1.0.4.1

---------------------------------------
#### Installation  

Simply clone this repo into your ~/.atom/packages directory

---------------------------------------
#### Setting Up Atom As an Integrated Development Environment

Meteor specific packages:
````sh
Beautify
Handlebars
Jshint
Prettify
Language-Spacebars
Meteor Api
````

Other packages I use:
````
Autoprefixer
Emmet
Minimap
Vim-Mode
````

To use spacebars in html by default add the following to your config.cson under global:
````
'file-types':
  'html': 'text.html.spacebars'
  'js': 'source.js'
````

If you'd like to permanently make all javascript default to the ``Javascript (Meteor)`` grammar, disable the ``language-javascript`` package.

---------------------------------------
#### Acknowledgements / Contributors

* ThusStyles for piecing together the original [meteor-snippets](https://github.com/ThusStyles/meteor-snippets) atom package
* zaku-eu for [language-spacebars](https://atom.io/packages/language-spacebars)
* Awatson1978 for the [meteor-api](https://github.com/awatson1978/meteor-api) atom package

---------------------------------------
#### Color Coded Meteor Syntax Example

![Meteor-Api Code Sample](https://raw.githubusercontent.com/tan-wyman/meteor-api/master/screenshots/code-sample.png)  
