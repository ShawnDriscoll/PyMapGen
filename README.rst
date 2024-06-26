**PyMapGen 0.2.7b for Python 3.11**
===================================

**PyMapGen** is a Python 3.11 program for viewing Traveller RPG stellar maps. Of course, it's a much smaller project than what's going on over at https://github.com/inexorabletash/travellermap


.. figure:: images/mapgen_cover_art.png


The Traveller game in all forms is owned by Far Future Enterprises.
Copyright 1977 - 2024 Far Future Enterprises.
Traveller is a registered trademark of Far Future Enterprises.

.. image:: images/video.png
    :target: https://www.youtube.com/watch?v=9HZSrX36lh8

.. figure:: images/mapgen_screen1.png

.. figure:: images/mapgen_screen2.png

.. figure:: images/mapgen_screen3.png

.. figure:: images/mapgen_screen4.png

Requirements
------------

* **Windows 11**

  It has been tested on Windows 10.

* **Python 3.11**

  This code was written using the C implementation of Python version 3.11. Also known as CPython.

* **pyttsx3 2.90**

  PyMapGen speaks in Zira's voice (her voice comes with Windows). Can be changed to a different voice in the source.

* **pygame 2.4.0**

  PyGame is used to draw the maps. It's basically a Python wrapper for SDL 2.26.4, which PyGame includes.



Usage
-----

Click on a sector to center it.

Dragging a sector (or pressing the arrow keys) will scroll the map.

The ``mouse wheel`` will zoom the map in and out while pointing.

Pressing ``0`` will mute the computer's voice.

Pressing ``1 - 9`` will choose the computer's voice shown in the list.

Pressing ``h`` will flip to a hex map(s) at different zoom levels.

Pressing ``r`` will flip to a rectangle map.

Pressing ``c`` will toggle solid/clear travel zones while zoomed in.

Pressing ``z`` will toggle circle/hex/rectangle travel zones while zoomed in.

Pressing ``t`` will toggle world UWP/TC while zoomed in.

Pressing ``l`` will toggle the world system locations on/off.

Pressing ``g`` will toggle the hex/rectangle grid on/off.

Pressing ``ESC`` will exit the program.


Things To-Do
------------

| Printing a PDF from the screen.
| Remove clipping at bottom of subsectors.
| Add more world types.
| Add trade routes.
| Instruction manual.
| Cheat codes.


Known History
-------------

* v0.2.7b

  Displays subsector names.

* v0.2.6b

  Searches for computer voices and displays their names in a list to choose from.

* v0.2.5b

  Updated to Python 3.11.0.

* v0.2.2b

  Desert, Agricultural, and Barren worlds are better displayed.

* v0.2.1b

  Compatible with pygame 2.1.2.

* v0.2.0b

  Removed requirement for colorama.

* v0.1.0b

  A differentiation has now been made between barren and dieback worlds.
  
* v0.0.8b

  Fixed the blue Allegiances.
  
  Removed 3rd-party voices.


Contact
-------
Questions? Please contact shawndriscoll@hotmail.com
