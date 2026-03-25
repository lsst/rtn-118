.. image:: https://img.shields.io/badge/rtn--118-lsst.io-brightgreen.svg
   :target: https://rtn-118.lsst.io
.. image:: https://github.com/lsst/rtn-118/workflows/CI/badge.svg
   :target: https://github.com/lsst/rtn-118/actions/

###########################################################
Guidelines for Rubin Liaisons to the Science Collaborations
###########################################################

RTN-118
=======

This document provides guidelines for Rubin Liaisons to the Science Collaborations. The Liaisons serve as a support contact, and advocate, and a two-way conduit for information to and from the SCs, with a focus on the scientific application of the Rubin data products, pipelines, and services.

**Links:**

- Publication URL: https://rtn-118.lsst.io
- Alternative editions: https://rtn-118.lsst.io/v
- GitHub repository: https://github.com/lsst/rtn-118
- Build system: https://github.com/lsst/rtn-118/actions/


Build this technical note
=========================

You can clone this repository and build the technote locally if your system has Python 3.11 or later:

.. code-block:: bash

   git clone https://github.com/lsst/rtn-118
   cd rtn-118
   make init
   make html

Repeat the ``make html`` command to rebuild the technote after making changes.
If you need to delete any intermediate files for a clean build, run ``make clean``.

The built technote is located at ``_build/html/index.html``.

Publishing changes to the web
=============================

This technote is published to https://rtn-118.lsst.io whenever you push changes to the ``main`` branch on GitHub.
When you push changes to a another branch, a preview of the technote is published to https://rtn-118.lsst.io/v.

Editing this technical note
===========================

The main content of this technote is in ``index.rst`` (a reStructuredText file).
Metadata and configuration is in the ``technote.toml`` file.
For guidance on creating content and information about specifying metadata and configuration, see the Documenteer documentation: https://documenteer.lsst.io/technotes.
