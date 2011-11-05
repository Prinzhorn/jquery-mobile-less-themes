jQuery Mobile less themes
======

Create jQuery Mobile themes using [less.js](https://github.com/cloudhead/less.js)


Creating a theme
==========

Fork the repo and copy the `themes/default` folder and give it the name of your theme. Now start editing `variables.less` to create your own theme. You may need to edit `theme.less` and `mixins.less` as well as create and edit images in the `images` folder, depending on how much you want to change.


Folder structure
==========

*themes
	*default
		*images (Image files for the theme)
		*index.html (Show cases all available jQuery Mobile elements with all swatches)
		*mixins.less (Mixins for things like border-radius and box-shadow)
		*theme.less (Main less file with all rules)
		*variables.less (Variables like colors and sizes)
	*jquery.js (Latest jQuery shared across all themes)
	*jquery.mobile.js (Latest jQuery Mobile shared across all themes)
	*jquery.mobile.structure.css (Latest jQuery Mobile CSS structure file shared across all themes)
	*less.js (Latest less.js shared across all themes)
*index.html (Links to all themes aka TOC)
