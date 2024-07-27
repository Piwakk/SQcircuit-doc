

.. _element_classes:

****************
Element Classes
****************

Capacitor
-------------------

.. autoclass:: SQcircuit.Capacitor
    :members:
    :exclude-members: error, internal_value, partial_mat, is_leaf


----------------------------------

Inductor
-------------------

.. autoclass:: SQcircuit.Inductor
    :members:
    :exclude-members:
        get_key, get_cap_for_flux_dist, partial_mat, error, internal_value,
        is_leaf


----------------------------------

Junction
-------------------

.. autoclass:: SQcircuit.Junction
    :members:
    :exclude-members:
        get_key, get_cap_for_flux_dist, error, internal_value, is_leaf


----------------------------------

Loop
-------------------

.. autoclass:: SQcircuit.Loop
    :members:
    :exclude-members: reset, add_index, addK1, getP, internal_value, is_leaf
