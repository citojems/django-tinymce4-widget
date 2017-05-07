Django TinyMCE4 Widget
======================

.. image:: https://travis-ci.org/browniebroke/django-tinymce4-widget.svg?branch=master
    :target: https://travis-ci.org/browniebroke/django-tinymce4-widget
.. image:: https://codecov.io/gh/browniebroke/django-tinymce4-widget/branch/master/graph/badge.svg
    :target: https://codecov.io/gh/browniebroke/django-tinymce4-widget
.. image:: https://readthedocs.org/projects/django-tinymce4-widget/badge/?version=latest
    :target: http://django-tinymce4-widget.readthedocs.io/en/latest/?badge=latest
.. image:: https://badge.fury.io/py/django-tinymce4-widget.svg
    :target: https://badge.fury.io/py/django-tinymce4-widget
.. image:: https://img.shields.io/pypi/pyversions/django-tinymce4-widget.svg
    :target: https://pypi.python.org/pypi/django-tinymce4-widget

**django-tinymce4-widget** is a reworked fork of `django-tinymce4-lite`_. It provides a minimal TinyMCE 4
editor widget that can be used in Django forms.

This version **does not** include any static files, it's using the TinyMCE `from the CDN`_ by default. 
As compared to the original fork, this package support Django from 1.7 to 1.11.

.. warning::
  TinyMCE 4 is incompatible with TinyMCE 3. Read `TinyMCE docs`_ for more information
  about how to configure TimyMCE 4 editor widget.

Documentation
=============

The full documentation is available at http://django-tinymce4-widget.readthedocs.io/en/latest/

.. _django-tinymce4-lite: https://github.com/romanvm/django-tinymce4-lite
.. _from the CDN: https://cloud.tinymce.com/stable/tinymce.min.js
.. _TinyMCE docs: https://www.tinymce.com/docs/
