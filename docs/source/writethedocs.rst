How to write the docs?
======================

Quick overview
--------------

This page gets you started for contributing to the doc pages.

The docs are written in `reStructuredText <http://www.sphinx-doc.org/en/master/usage/restructuredtext/basics.html>`_ -
an easy-to-learn markup language. So adding or editing content basically means
writing rst documents in a simple text editor.

The sources are available in `this GitHub repository <https://github.com/heistermann/wasto-docs>`_.
If these sources are modified through a new "commit", a new doc version is built
and hosted via https://readthedocs.org/ and shown at https://wasto-docs.readthedocs.io.

Building the docs is done with `Sphinx <http://www.sphinx-doc.org>`. But let's
here about that later.

The quickest, though not recommended, way to edit the docs is directly via GitHub.
Let's try that first. If you do not have a GitHub account, yet, get it
`here <Get a `GitHub <https://github.com>`_ account>`_.



The quickest, though not really recommended

- Get a `GitHub <https://github.com>`_ account
- a `GitHub repository <https://github.com/heistermann/wasto-docs>`_ that
  collects the documentation sources
- a local Sphinx environment to test the build process
- a ReadTheDocs environment to automatically build and host the docs
- git and GitHub to manage the collaborative development


Install Sphinx
--------------

Sphinx collects all the raw documentation sources and puts them together
to beautiful html pages, pdfs, epubs and more. The documentation sources are written
in `reStructuredText <http://www.sphinx-doc.org/en/master/usage/restructuredtext/basics.html>`_ -
a simple markup language.

To install Sphinx, we recommend the following way:

1. Install Miniconda (https://conda.io/miniconda.html).

3. Create a new ``conda`` environment::

      $ conda create --name sphinx python=3.7

4. Activate the new environment:

    **Linux**::

       $ source activate sphinx

    **Windows**::

       > activate sphinx

5. Install dependencies::

      (sphinx) $ conda install sphinx sphinx_rtd_theme


Install git
6. Get the doc sources
