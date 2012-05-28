Templates overrides folder
===========================

plone.app.themingplugins automatically registers a template
overrides directory for the theme.

This directory can then contain template overrides using ``z3c.jbot``
naming conventions, e.g. ``plone.app.layout.viewlets.logo.pt`` will
override the file ``logo.pt`` in the package 
``plone.app.layout.viewlets`` when the theme is in effect.

The directory and layer can be overriden in the manifest.cfg if required::

    [theme:overrides]
    directory = template-overrides
    layer = beyondskins.plonesymposium.site.interfaces.ISomeLayer

The directory name is relative to the theme directory. The layer interface
must already exist.
