We recently started to use [SASS / SCSS][1] to code our stylesheets. We were missing some proper syntax highlighting with the default CSS settings provided by [Notepad++][2]. After some research, we found a good base on [Wouter Beugelsdijk's techblog][3] but we were still not quite happy with it. 

# How to use

## To enable SCSS syntax highlighting:

*   In Notepad++, pick the `User Defined Dialog...` item from the `Language` menu.
*   Click on the import button and simply select the XML file located in our ZIP file
*   That's it, all your files with the *.scss* extension should now be highlighted

## To enable autocomplete:

*   go to your Notepad++ folder then to `/plugins/APIs/`
*   duplicate the `css.xml` and rename this file to `SCSS-Light.xml` or `SCSS-Dark.xml`

#Our modifications

## version 1.0

*   Highlighting for HTML tags
*   Changed some colors
*   Added syntax coloring for important comments starting with /\*! instead of just /\*
*   Added syntax coloring for partial css keywords used while using [nested properties][4]


 [1]: http://sass-lang.com
 [2]: http://notepad-plus-plus.org/
 [3]: http://tech.wiedo.nl/sass-3-notepad-user-defined-syntax-highlighti
 [4]: http://sass-lang.com/docs/yardoc/file.SASS_REFERENCE.html#nested_properties
