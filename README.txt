===============================================
Plone Symposium South America Theme
===============================================

.. contents:: Table of Contents
   :depth: 2

Overview
--------

Plone Symposium South America Theme is an installable Plone Theme developed 
by `Simples Consultoria <http://www.simplesconsultoria.com.br/>`_
using the **theming** and **packaging** features available in 
`plone.app.theming`_.


Requirements
------------

    * Plone 4.1.x (http://plone.org/products/plone)
    
    * plone.app.theming (*will be installed as a dependency of this package*)


Installation
------------

Getting the theme
~~~~~~~~~~~~~~~~~~~~

Zip file
++++++++++

If you are an end user, you might enjoy installation via zip file import.

    1. Download a `zip file <https://github.com/plonegovbr/beyondskins.plonesymposium.site/raw/master/beyondskins.plonesymposium.site.zip>`_ 
        
    2. Import the theme from the Diazo theme control panel.

Buildout
++++++++++

If you are a developer, you might enjoy installing it via buildout.

Add ``beyondskins.plonesymposium.site`` to your ``plone.recipe.zope2instance`` section's *eggs* parameter e.g.::

    [instance]
    eggs =
        Plone
        ...
        beyondskins.plonesymposium.site

Or, you can add it as a dependency on your own product *setup.py*::

    install_requires=[
        ...
        'beyondskins.plonesymposium.site',
    ],


Enabling the theme
~~~~~~~~~~~~~~~~~~~~

    Select and enable the theme from the Diazo control panel. That's it!


Credits
-------

     
    * Andre Nogueira (andre at simplesconsultoria dot com dot br) - Conception 
      and prototype.


.. _`plone.app.theming`: http://pypi.python.org/pypi/plone.app.theming
.. _`Plone 4.1`: http://pypi.python.org/pypi/Plone/4.1rc2

