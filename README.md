SiS-PM Control for Windows 
========================

Based on Source Code sispmctrl in version 4.9from following authors

(c) 2015-2020, Heinrich Schuchardt &lt;xypron.glpk@gmx.de&gt;

(c) 2011-2016, Pete Hildebrandt &lt;send2ph@gmail.de&gt;

(c) 2005-2011, Mondrian Nuessle et al. 

Overview
--------

This project provides a management software for the following USB controlled
powerstrips:

* Gembird SIS-PMS SilverShield
* Gembird MSIS-PM
* EnerGenie EG-PMS2
* EnerGenie EG-PMS2

Dependencies
------------

- USB driver libusb-win32 (v1.2.6.0) - Replaced with [Zadiq - USB driver installation made easy](https://zadig.akeo.ie/)
- Cygwin-Runtime-Libraries (in package provided)
  - cygwin1.dll
  - cygusb0.dll
  - cygncursesw-10.dll

Limitation
----------

- This build was compiled **without** web-interface features.

How to use
----------

- Like mentioned in the section **Limitation** the default driver has to be replaced with driver libusb-win32 
- Get list of options (help) with `sispmctl.exe -h`

Command Line Interface
----------------------

The command `sispmctl` can be used to

* show the status of one or all outputs
* switch on or off, or toggle an output
* program a schedule according to which outputs shall be switched on and off

License
-------

SiS-PM Control for Linux is published under the GNU Public License Version 2 or
(at your option) any later version.
