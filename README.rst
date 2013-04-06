
The main reason for this package lies in the complicated dependencies in other products 
which export data from Plone. Normally these only work with Plone 3.0 or higher (or not
even with 3.0).

Therefore this package has no major dependency and can be installed in any
Plone version. It probably should work also for Plone 1.0, but this was not
tested. The only dependency is simplejson_.

The format in which data is exported is JSON_ in collective.transmogrifier_
friendly format. There is also a blueprint developed which is laying in
collective.jsonmigrator_ package.

Package is DOCUMENTED_.


:Warning: This product may contain traces of nuts.
:Author: `Rok Garbas`_, *migrating for you since 2008*
:Source: http://github.com/collective/collective.jsonify


.. _`collective.transmogrifier`: http://github.com/collective/collective.jsonmigrator
.. _`simplejson`: http://pypi.python.org/simplejson
.. _`TESTED`: http://packages.python.org/collective.jsonify/testing.html
.. _`DOCUMENTED`: http://packages.python.org/collective.jsonify
.. _`collective.jsonmigrator`: http://pypi.python.org/pypi/collective.jsonmigrator
.. _`Rok Garbas`: http://www.garbas.si/labs/plone-migration
.. _`JSON`: http://en.wikipedia.org/wiki/JSON
