.. _units:

*****************
Units
*****************

The output of ``Circuit.diag()``, ``Capacitor.energy()``, and ``Inductor.energy()`` methods are in the frqeuncy default unit of SQcircuit, gigahertz. This simply can be changed to ``Hz``, ``kHz``, or ``MHz`` via following method:

.. code-block:: 

	import SQcircuit as sq
	
	sq.units.setFreq("MHz")

 
