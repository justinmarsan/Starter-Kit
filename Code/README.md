Code Folder
===========

I use this folder as a kickstarter for frontend dev.

lib/css
-------

The code in there is generated automatically with the Less compiler. global.css is used for dev, it's not minified to allow easier debugging. global.min.css is minified and should be used on prod.

lib/img
-------

Contains the images used through the css code. Dynamic content images should leave somewhere else. As a convention, I prefix temporary images with a "_" such as "_grid.png". All temporary files should be removing on production.

lib/js
------

Needs to be updated with current version of jQuery and such.

lib/less
--------

Most important folder, contains all the module folders. Css modules are stored in their own folders so they can also contain txt or html files as documentation.

global.less imports all the modules, and global.min.less imports global.less and minifies it.