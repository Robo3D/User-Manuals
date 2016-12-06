# support.robo3d.com

Build Status</br>
[![Documentation Status](https://readthedocs.org/projects/support-site/badge/?version=latest)](http://support-site.readthedocs.io/en/latest/?badge=latest)
     

Current support site location: http://support-site.readthedocs.io/en/latest/demo.html

The site is currently being built by ReadTheDocs, all content is driven from this github repo
https://readthedocs.org

CSS can be found here: https://github.com/Robo3D/support.robo3d.com/tree/master/sphinx_rtd_theme/static/css


In order to customize the existing sphinxdoc theme, you need to create a custom template and stylesheet that contains the desired modifications.

_template and _static subfolders
In your sphinx documentation folder (named docs in this example), create two subfolders: _static and _templates: 
docs
├── conf.py
├── index.rst
└── _templates
    └── page.html
└── _static
    └── style.css

style.css stylesheet
In the _static folder, create a file style.css containing CSS options that you wish to overwrite. You can find the applicable options by looking at the sphinxdoc theme stylesheet, inside the sphinx installation folder: 
./python3.4/site-packages/Sphinx-1.3.1-py3.4.egg/sphinx/themes/sphinxdoc/static/sphinxdoc.css_t`
To change the document background from white to black, add the following lines to style.css:
body {
    background-color: black;
    color: white;
}
div.document {
    background-color: black;
}
To add the ability to center your code using the .. rst-class:: centered directive, add the following lines:
.centered {
    text-align: center;
}
etc...

page.html template
In the _templates subfolder, create a file page.html with the following content:
{% extends "!page.html" %}

{% set css_files = css_files + ["_static/style.css"] %}
This tells sphinx to look for the style.css stylesheet in the _static folder.

More information
These instructions are from the Tinkerer documentation on theming: http://tinkerer.me/doc/theming.html. Tinkerer is a blogging engine based on Sphinx.
Also, see: How to add custom css file.
