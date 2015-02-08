PoWA Documentation
=========================


See http://powa.readthedocs.org/

[![Documentation Status](https://readthedocs.org/projects/powa/badge/?version=latest)](https://readthedocs.org/projects/powa/?badge=latest)
                

Compile the doc
-----------------------------------

* Install Sphinx :

``
        apt-get install python-sphinx
``

* Build :

``
	sphinx-build -b html . /tmp/powa-doc/ 
``

or 

``
        make html 
``

Sphinx Theme
------------------------------------------------------------

Install the [https://github.com/snide/sphinx_rtd_theme](Read The Doc theme)

``
        pip install sphinx_rtd_theme
``

And then add the following lines to the ``conf.py`` file:

``
import sphinx_rtd_theme
html_theme = "sphinx_rtd_theme"
html_theme_path = [sphinx_rtd_theme.get_html_theme_path()]


PoWA user documentation
