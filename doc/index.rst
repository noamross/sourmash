.. sourmash documentation master file, created by
   sphinx-quickstart on Sat Jun  4 16:35:43 2016.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Welcome to sourmash!
====================

sourmash is a command-line tool and Python library for computing
`MinHash sketches <https://en.wikipedia.org/wiki/MinHash>`__ from DNA
sequences, compare them to each other, and plot the results.  This
allows you to estimate sequence similarity quickly and accurately.

Please see the `mash <http://mash.readthedocs.io/en/latest/>`__
software and the `mash paper (Ondov et al., 2016)
<http://biorxiv.org/content/early/2015/10/26/029827>`__ for background
information on how and why MinHash sketches work.

In brief,

* ``sourmash`` provides command line utilities for creating, comparing,
  and searching MinHash sketches, as well as plotting and clustering
  sketches by distance (see `the command-line docs <command-line.html>`__).

* ``sourmash`` supports saving, loading, and communication of MinHash
  sketches via `YAML <http://yaml.org/>`__, a ~human-readable & editable
  format.

* ``sourmash`` also has a simple Python API for interacting with sketches,
  including support for online updating and querying of sketches
  (see `the API docs <api.html>`__).

* ``sourmash`` isn't terribly slow, and relies on an underlying CPython
  module.

* ``sourmash`` is developed `on GitHub
  <https://github.com/dib-lab/sourmash>`__ and is freely and openly
  available under the BSD 3-clause license.  Please see `the README
  <https://github.com/dib-lab/sourmash/blob/master/README.md>`__ for
  more information on development, support, and contributing.

Contents:
---------

.. toctree::
   :maxdepth: 2

   command-line
   api
   api-example
   requirements
   more-info


Indices and tables
==================

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`

