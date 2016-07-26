Introduction
============

This products provides a `collective.transmogrifier`_ blueprint to link content
using LinguaPlone in your Plone site.

It uses the same code structure as the multilingual blueprint provided by
`ftw.blueprints`_

You need to provide the following keys for your content:

**_canonicalTranslation**: True or False, depending on whether this content is a canonical object or not

**_translationOf**: this key is ignored if _canonicalTranslation is True. If _canonicalTranslation is True
this key must contain the path of the canonical object.


.. _`collective.transmogrifier`: https://pypi.python.org/pypi/collective.transmogrifier
.. _`ftw.blueprints`: https://pypi.python.org/pypi/ftw.blueprints.
