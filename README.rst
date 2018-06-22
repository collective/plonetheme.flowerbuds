=====================
plonetheme.flowerbuds
=====================


Introduction
============

*plonetheme.flowerbuds* package is an installable Plone_ Theme using the **theming** and **packaging** 
features available in `plone.app.theming`_ to make the theme `flowerbuds`_ easily
available in `Plone`.

This theme has been taken from http://www.freecsstemplates.org/
and integrated into as a diazo theme for Plone.


Requirements
============

- From the Plone 4.1.x To the Plone 4.3 latest version (https://plone.org/download)
- The ``plone.app.theming`` package (*will be installed as a dependency of this package*)


Features
========
- It's a simple Diazo_ package (Zip file).


Installation
============


Add Plone site
--------------

Install Plone 4.x with `plone.app.theming`_ and create a Plone site (if you have not already)
with Diazo theming configured.

.. image:: https://github.com/collective/plonetheme.flowerbuds/raw/master/screenshot0.png
  :width: 1024px
  :alt: Create a Plone site from ZMI
  :align: center


Zip file
--------

If you are an **end user**, you might enjoy installation via zip file import.

1. Download a `zip file <https://raw.github.com/collective/plonetheme.flowerbuds/master/flowerbuds.zip>`_.
2. Import the theme from the Diazo theme control panel.

.. image:: https://github.com/collective/plonetheme.flowerbuds/raw/master/screenshot1.png
  :width: 1024px
  :alt: Import the Diazo theme zip file
  :align: center


Buildout
--------

If you are a **developer user**, you might enjoy installing it via buildout.

For install ``plonetheme.flowerbuds`` package add it to your ``buildout`` section's 
*eggs* parameter e.g.: ::

   [buildout]
    ...
    eggs =
        ...
        plonetheme.flowerbuds


and then running ``bin/buildout``.

Or, you can add it as a dependency on your own product ``setup.py`` file: ::

    install_requires=[
        ...
        'plonetheme.flowerbuds',
    ],


Enabling the theme
^^^^^^^^^^^^^^^^^^

Browse to ``http://yoursite/Plone/@@theming-controlpanel`` click on ``Enable`` 
on ``Flower buds`` theme from the Diazo control panel.

.. image:: https://github.com/collective/plonetheme.flowerbuds/raw/master/screenshot2.png
  :width: 1024px
  :alt: For select the Diazo theme just click on Activate button
  :align: center

That's it!

You should see the layout of the site when viewed in a computer resolution:

.. image:: https://raw.githubusercontent.com/collective/plonetheme.flowerbuds/master/plonetheme/flowerbuds/theme/flowerbuds/preview.png
  :width: 1024px
  :alt: plonetheme.flowerbuds preview
  :align: center


Contribute
==========

- Issue Tracker: https://github.com/collective/plonetheme.flowerbuds/issues
- Source Code: https://github.com/collective/plonetheme.flowerbuds


Collaborations
--------------

- JeanMichel FRANCOIS (toutpt at gmail dot com).

- Leonardo J. Caballero G. (leonardocaballero at gmail dot com).

- Full Name aka nickname

For an updated list of all the contributors visit: https://github.com/collective/plonetheme.flowerbuds/graphs/contributors


License
=======

This package is licensed under the GPL Version 2.

.. _`flowerbuds`: http://www.freecsstemplates.org/preview/flowerbuds
.. _`Plone`: http://plone.org
.. _`plone.app.theming`: https://pypi.org/project/plone.app.theming/
.. _`Diazo`: http://diazo.org
