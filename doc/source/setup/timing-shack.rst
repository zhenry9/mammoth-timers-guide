Timing Shack Setup
==================

.. figure:: ../img/timing-shack-signal-flow.png

	Basic timing shack signal flow for homologated races.
	
:Equipment Needed:
	.. include:: /equipment/kits/homologated-timing-shack-kit.rst
	
The timing shack is where the timing system is tied together. The start and the finish are connected to the electronic timers, and the electronic timers to the timing PC(s). Communications are established between the timer and the starter, and between the scoreboard staff. Accessories such as digital display boards are setup.

Impulse distributors are not required by rule, and some mountains don't use them. However, the large amount of electrical noise at Mammoth Mountain necessitates their use here. They filter the noise out of timing lines and prevent false impulses.

Connecting the electronic timers
--------------------------------

.. image:: /img/timing-shack-connections/tidy-up.jpg
	:width: 25%

The first step is to connect the start and finish to the electronic timers. This is made easier by the labled timing boards located in each of the timing shacks. For this example we will use the timing board in the :ref:`Hilton`.

Connect the start
~~~~~~~~~~~~~~~~~

.. figure:: /img/timing-shack-connections/start-distributor-1.jpg
	:width: 25%

	The start distributor next to the timing board.
	
.. container:: step1

   .. container:: leftside

      .. figure:: /img/timing-shack-connections/start-distributor-2.jpg

   .. container:: rightside

      Connect 'Time 1' on the timing board to 'Input 1' on the start impulse distributor. This is the System A start.
	  
|clear|
	  
.. container:: step2

   .. container:: leftside

      .. figure:: /img/timing-shack-connections/start-distributor-3.jpg

   .. container:: rightside

     Connect 'Time 2' on the timing board to 'Input 2' on the distributor. This is the System B start.
	
.
	
.. container:: step3

   .. container:: leftside

      .. figure:: /img/timing-shack-connections/start-distributor-4.jpg

   .. container:: rightside

      Connect 'Output 1' on the distributor to 'Input 1' on the System A electronic timer.
	  
.
	  
.. container:: step4

   .. container:: leftside

      .. figure:: /img/timing-shack-connections/start-distributor-5.jpg

   .. container:: rightside

     Connect 'Output 2' on the distributor to 'Input 1' on the System B electronic timer.

.. |clear| raw:: html 

	<div class="clear"></div>

Connect the finish
~~~~~~~~~~~~~~~~~

.. figure:: /img/timing-shack-connections/finish-distributor-1.jpg
	:width: 25%

	The finish distributor next to the timing board.


.. figure:: /img/timing-shack-connections/finish-distributor-2.jpg
	:width: 25%
	
	Step 1
	
	Connect 'HiFi 1' on the timing board to 'Input 1' on the finish impulse distributor. This is the System A finish.
	
.. figure:: /img/timing-shack-connections/finish-distributor-3.jpg
	:width: 25%
	
	Step 2
	
	Connect 'HiFi 2' on the timing board to 'Input 2' on the distributor. This is the System B finish.
	
.. figure:: /img/timing-shack-connections/finish-distributor-4.jpg
	:width: 25%
	
	Step 3
	
	Connect 'Output 1' on the distributor to 'Input 2' on the System A electronic timer.
	
.. figure:: /img/timing-shack-connections/finish-distributor-5.jpg
	:width: 25%
	
	Step 4
	
	Connect 'Output 2' on the distributor to 'Input 2' on the System B electronic timer.
	
Scoreboard Setup
----------------

.. figure:: ../img/timing-shack-with-scoreboard-signal-flow.png

	Timing shack signal flow, with digital display board and paper scoreboard connections made