.. image:: https://img.shields.io/badge/rtn--097-lsst.io-brightgreen.svg
   :target: https://rtn-097.lsst.io
.. image:: https://github.com/lsst/rtn-097/workflows/CI/badge.svg
   :target: https://github.com/lsst/rtn-097/actions/

##########################################################
Guidelines for User Support with the Rubin Community Forum
##########################################################

RTN-097
=======

Guidelines for using the Rubin Community Forum to support the scientific community in their use of the data products, services, and tools created by the Rubin Observatory (or by other groups, e.g., brokers, independent data access centers). This primarily includes guidelines for answering users' questions and resolving issues, but also for posting Rubin-related news and announcements, enabling science discussions and collaboration, and settings to make accounts identifiable as Rubin staff.

**Links:**

- Publication URL: https://rtn-097.lsst.io
- Alternative editions: https://rtn-097.lsst.io/v
- GitHub repository: https://github.com/lsst/rtn-097
- Build system: https://github.com/lsst/rtn-097/actions/


Build this technical note
=========================

You can clone this repository and build the technote locally if your system has Python 3.11 or later:

.. code-block:: bash

   git clone https://github.com/lsst/rtn-097
   cd rtn-097
   make init
   make html

Repeat the ``make html`` command to rebuild the technote after making changes.
If you need to delete any intermediate files for a clean build, run ``make clean``.

The built technote is located at ``_build/html/index.html``.

Publishing changes to the web
=============================

This technote is published to https://rtn-097.lsst.io whenever you push changes to the ``main`` branch on GitHub.
When you push changes to a another branch, a preview of the technote is published to https://rtn-097.lsst.io/v.

Editing this technical note
===========================

The main content of this technote is in ``index.rst`` (a reStructuredText file).
Metadata and configuration is in the ``technote.toml`` file.
For guidance on creating content and information about specifying metadata and configuration, see the Documenteer documentation: https://documenteer.lsst.io/technotes.
