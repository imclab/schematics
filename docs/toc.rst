.. _toc:

Documentation
=============

New Schematics users should start with the :doc:`quickstart`.  That is the
fastest way to get a look at what Schematics does.


Usage
-----

Schematics exists to make a few concepts easy to glue together.  The types
allow us to describe units of data, models let us put them together into
structures with fields.  We can then import data, check if it looks correct,
and easily serialize the results into any format we need.

.. toctree::
   :maxdepth: 2

   usage/types
   usage/models
   usage/exporting
   usage/importing
   usage/validation
   usage/transforms

.. _api:

API Reference
-------------

The User's Guide provides the high-level concepts, but the code itself provides
the most accurate reference.

.. toctree::
   :maxdepth: 2

   api/models
   api/validation
   api/transforms
   api/types
   api/contrib
