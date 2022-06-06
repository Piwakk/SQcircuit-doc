.. _install:

**************
Installation
**************

.. _install-Conda:

Installing via Conda
=====================

For Python above 3.6, SQcirucit can be simply installed via Conda:

.. code-block:: bash

   conda install -c conda-forge sqcircuit

Updating to the latest version of SQcircuit, can be done by

.. code-block:: bash

   conda update -c conda-forge sqcircuit


.. _install-Pip:

Installing via pip
==================

SQcircuit can  be installed using `pip <http://www.pip-installer.org/>`_, a Python package manager, via 

.. code-block:: bash

   pip install SQcircuit

To upgrade to the latest version of SQcircuit, one can execute 

.. code-block:: bash

   pip install SQcircuit -U

.. _install-genRequires:

General Requirements
=====================

SQcircuit depends on the following Python open-source libraries:


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
| **QuTiP**      | 4.6+         | Quantum operators are defined in QuTip objects.     |
+----------------+--------------+-----------------------------------------------------+
| **IPython**    | 7.0+         | Not tested on lower versions.                       |
+----------------+--------------+-----------------------------------------------------+
