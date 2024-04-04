Wiring and Assembly
===================

.. image:: ../images/wiring.png
   :alt: wiring
   :align: center

Soldering
---------
All of drone wiring is going to require some soldering skill, which you can develop through this project.

If you ae inexperienced with soldering, I would recommend watching this `video from oneTesla <https://www.youtube.com/watch?v=Qps9woUGkvI>`_. After watching that practicing on some practice boards would be strongly advised, you don't want to mess up your expensive flight controller.

To get more specific drone soldering tips you can look to this `video from The Drone Racing League <https://www.youtube.com/watch?v=Ct-kvrCdGOY>`_ which is quite quick and helpful or consider this longer but still information packed `video from TRONCAT FPV <https://www.youtube.com/watch?v=2funvs3nU7U>`_.

Assembly order
--------------
After honing your soldering skills it is important to be conscious of order in which you solder and assemble your drone. I have created this list below as a recommendation for the in which you should make your drone. This is based off of difficulty and of course necessary assembly order to try and give you the opportunity to fine tune your soldering in the easier steps and move up to bigger challenges. 

1. Camera to Flight Controller
2. Video Transmitter to Flight Controller
3. Radio Transmitter to Flight Controller
4. Assemble Bottom half of frame
5. Battery Pigtail to ESC Board
6. Motors and ESC Wiring
7. Flight Controller Mounting
8. Assemble Remainder of Drone
9. Wire Management

Below I have included some tips and tricks for each step along the way.

1. Camera to Flight Controller
------------------------------
Every flight controller should come with a pin-out. This tells you where every wire needs to go. Below i've attached an example for a camera.

.. image:: ../images/cameratofc.png
   :alt: camera to flight controller
   :align: center

2. Video Transmitter to Flight Controller
-----------------------------------------
.. tip:: Your Video Transmitter is commonly referred to as a VTX. 

This step can get a little tricky because although your VTX cable will have 6 wires you might not need to solder all of them to your flight controller. 

This means you need to check the wiring diagram for your flight controller as well as consult the cable channels from your VTX and its specifications.

Below i've attached an example of a VTX to FC wiring diagram.

.. image:: ../images/vtxtofc1.png
   :alt: vtx to flight controller
   :align: center

.. image:: ../images/vtxtofc2.png
   :alt: vtx to flight controller
   :align

See how the the wiring can change between two different transmitters.

3. Radio Receiver to Flight Controller
-----------------------------------------
.. tip:: Your Radio Receiver is commonly referred to as an RX.

The RX can have a variety of wiring configurations. Below is an example of some RX to FC wiring diagrams. 

.. image:: ../images/rxtofc1.png
   :alt: rx to flight controller
   :align: center

.. image:: ../images/rxtofc2.png
   :alt: rx to flight controller
   :align: center

.. image:: ../images/rxtofc3.png
   :alt: rx to flight controller
   :align: center

For the Radio Receiver what changes is the radio protocol you are using. This is built into your radio receiver so if you already have a radio controller I would advise purchasing a receiver that has a protocol supported by your controller.

Check your receivers specifications for its protocol and then consult the wiring diagram for your flight controller. 

4. Assemble Bottom half of frame
--------------------------------
Now that your flight controller is wired up its time to construct the lower half of your drone. This means start building your frame and take a break from soldering.

.. important:: Make sure not to tighten bolts too much, it should be firm but if you are exerting yourself to tighten a bolt, you doing too much.

.. image:: ../images/rock.png
   :alt: rock
   :align: center

5. Battery Pigtail to ESC Board
-------------------------------
Now be warned this is the hardest part of the entire build from my experience. 

This the wire that attaches your drone electronics to the battery. Its thick and the soldering pads are normally horrible. That being said once you've crossed this hump you will be in the endgame.

Credit to Just Hack it for their great tutorial here that helped me a lot when I first did this - `How To Solder XT60 to ESC | Beginners Guide <https://www.youtube.com/watch?v=KWzGA4khJGg>`_

My advice would be to take your time setting up the wires so that they can sit still while you apply solder. 

.. warning:: Remember to think about how the wires will sit inside of your drone chassis. If you wire them going straight out of the ESC board and they need to go 90 degrees upwards you will have a miserable time redoing this.

Take your time figuring out the setup both on the drone and for soldering.

6. Motors and ESC Wiring
------------------------


7. Flight Controller Mounting
-----------------------------

8. Assemble Remainder of Drone
------------------------------

9. Wire Management
------------------




