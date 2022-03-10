.. _install:

**************
Installation
**************

.. _install-via_pip:

Installing via pip
==================

SQcircuit can  be installed using `pip <http://www.pip-installer.org/>`_, a Python package manager, via 

.. code-block:: bash

   pip install scqubits

To upgrade to the latest version of SQcircuit, one can execute 

.. code-block:: bash

   pip install SQcircuit -U

.. _install-requires:

General Requirements
=====================

scqubits depends on the following Python open-source libraries:


.. cssclass:: table-striped

+----------------+--------------+-----------------------------------------------------+
| Package        | Version      | Details                                             |
+================+==============+=====================================================+
| **Python**     | 3.6+         | Version 3.6 and higher is supported.                |
+----------------+--------------+-----------------------------------------------------+
| **NumPy**      | 1.20.0+      | Not tested on lower versions.                       |
+----------------+--------------+-----------------------------------------------------+
| **SciPy**      | 1.7.0+       | Not tested on lower versions.                       |
+----------------+--------------+-----------------------------------------------------+
| **QuTiP**      | 4.6+         | Quantum operators are defined in QuTip objects      |
+----------------+--------------+-----------------------------------------------------+
