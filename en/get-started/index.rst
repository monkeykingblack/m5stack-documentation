﻿***********
Get Started
***********

This document is intended to help users set up the software environment for development of applications. Through a simple example we would like to illustrate how to develop M5Stack boards, firmware(`Arduino IDE`), Blockly or source files(`Micropython`) download to M5Stack boards.


Introduction
============


What You Need
=============

To develop applications for M5Stack Core you need:

* **PC** loaded with either Windows, Linux or Mac operating system
* a **M5Stack Core** with Type-C cable


Your boards
============

At the first time, you need to burn the specific firmware file(.bin) to your board following this article `How to burn firmware`_ befor developing it.

.. _how to burn firmware: how_to_burn_firmware_en.html

If you have one of ESP32 development boards listed below, click the corresponding one to start your development.

============================  ============================  ============================
|Core with Arduino|_           |Core with Micropython|_           |M5GO|_
----------------------------  ----------------------------  ----------------------------
`Core with Arduino`_           `Core with Micropython`_           `M5GO`_
----------------------------  ----------------------------  ----------------------------
|ESP32CAM|_                    |M5Stack STEPMOTOR Module|_        |M5Bala|_
----------------------------  ----------------------------  ----------------------------
`ESP32CAM`_                    `M5Stack STEPMOTOR Module`_        `M5Bala`_
============================  ============================  ============================


.. |Core with Arduino| image:: ../../_static/pics/m5-arduino.jpg
.. _Core with Arduino: M5Stack_Core_Get_Started_Arduino_Windows_en.html

.. |Core with Micropython| image:: ../../_static/pics/m5-micropython.jpg
.. _Core with Micropython: M5Stack_Core_Get_Started_MicroPython_Windows_en.html

.. |M5GO| image:: ../../_static/pics/M5GO.jpg
.. _M5GO: M5Stack_Core_Get_Started_MicroPython_Windows_en.html

.. |ESP32CAM| image::  ../../_static/pics/ESP32CAM.jpg
.. _ESP32CAM: get-started-ESP32CAM.html

.. |M5Stack STEPMOTOR Module| image::  ../../_static/pics/m5-stepmotor.jpg
.. _M5Stack STEPMOTOR Module: get-started-StepMotor.html

.. |M5Bala| image::  ../../_static/pics/M5Bala.jpg
.. _M5Bala: get-started-M5Bala.html


.. toctree::
    :maxdepth: 1
    :hidden:

    M5Stack Core with Arduino IDE <M5Stack_Core_Get_Started_Arduino_Windows_en>
    M5Stack Core with Micropython <M5Stack_Core_Get_Started_MicroPython_Windows_en>
    M5GO <M5Stack_Core_Get_Started_MicroPython_Windows_en>
    ESP32CAM <get-started-ESP32CAM>
    M5Stack STEPMOTOR Module <get-started-StepMotor>
    M5Bala <get-started-M5Bala>

Which programming mode you like
=================================

For being familiar with the programming mode you lik, We suggest you following the corresponding option to do more practices.

============================  ============================  ============================
|Arduino|_                          |Blockly|_                      |MicroPython|_
----------------------------  ----------------------------  ----------------------------
`Arduino`_                          `Blockly`_                      `MicroPython`_
============================  ============================  ============================

.. |Arduino| image:: ../../_static/getting_started_pics/programming_mode_arduino.png
.. |Blockly| image:: ../../_static/getting_started_pics/programming_mode_blockly.png
.. |MicroPython| image:: ../../_static/getting_started_pics/programming_mode_micropython.png

.. _Arduino: practices_arduino.html
.. _Blockly: practices_blockly.html
.. _MicroPython: practices_micropython.html



Related Documents
=================

.. toctree::
    :maxdepth: 1

    establish_serial_connection
