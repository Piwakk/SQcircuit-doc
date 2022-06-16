.. _units:

*****************
Units
*****************

The output of ``Circuit.diag()``, ``Capacitor.energy()``, and ``Inductor.energy()`` methods are in the frqeuncy default unit of SQcircuit, gigahertz. This simply can be changed to ``Hz``, ``kHz``, or ``MHz`` via following method:

.. code-block:: 

	import SQcircuit as sq
	
	sq.units.set_unit_freq("MHz")

The default unit for all elements are gigahertz, and there is no need to specify the unit for the elements in gigahertz unit. However, we can change the default unit for each type of element via ``sq.set_unit_cap()``, ``sq.set_unit_ind()``, and ``sq.set_unit_JJ()`` functions for capacitors, inductors, and Josephson junctions respectively. For example, in the following code ``C1`` and ``C2`` are in gigahertz unit and ``C3`` and ``C4`` are in femtofarad unit. 

.. code-block:: 

	# capacitors in GHz default unit
	C1 = sq.Capacitor(10)
	C2 = sq.Capacitor(12)

	sq.units.set_unit_cap("fF")

	# capacitors in fF default unit
	C3 = sq.Capacitor(3)
	C4 = sq.Capacitor(4)