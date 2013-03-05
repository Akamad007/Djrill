.. Djrill documentation master file, created by
   sphinx-quickstart on Sat Mar  2 13:07:34 2013.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

.. Incorporate the shared-intro section from the root README:

.. include:: ../README.rst
   :start-after: _shared-intro:
   :end-before:  END shared-intro

.. Eliminate the README's Travis build status indicator.
   (Is there some way we could link to Travis status for the
   specific |VERSION| of the app being documented here???)

.. |buildstatus| replace:: \


.. _toc:

Documentation
-------------

.. toctree::
   :maxdepth: 2

   quickstart
   installation
   usage/sending_mail
   usage/templates
   usage/multiple_backends
   contributing
   history


Thanks
------

Thanks to the MailChimp team for asking us to build this nifty little app, and to all of Djrill's
:doc:`contributors <contributing>`. Also thanks to James Socol on Github for his django-adminplus_
library that got us off on the right foot for the custom admin views.
Oh, and, of course, Kenneth Reitz for the awesome requests_ library.

.. _requests: http://docs.python-requests.org
.. _django-adminplus: https://github.com/jsocol/django-adminplus
