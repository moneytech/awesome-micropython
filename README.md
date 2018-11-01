Awesome MicroPython
===================

MicroPython came known as a "Python for microcontrollers". It's far more
than that.

MicroPython is a full-stack language, which, unlike many other languages,
is concerned not only with scaling up, but also with scaling down. This
means it can run on your laptop, desktop, on a supercomputer (sure, why
not), but also inside your Internet router, fridge, clock, smartwatch,
temperature sensor, microcontroller development board, inside your new
game or productivity app, and in gazillion of other applications and
devices. Familiar, easy to use, expressive language everywhere, with
the ability to optimize your software based on the hardware needs.

Summing this all up with the (unoffical) motto: **MicroPython runs everywhere!**

MicroPython is created and maintained by Damien George,
[@dpgeorge](https://github.com/dpgeorge/).

This list is not directly affiliated with, or endorsed by, the "official"
MicroPython and/or forks owned by other parties. Opinions here are solely
those of the list author and agreeing contributors. The list is intended
to capture breadth and pluralism of the MicroPython community, but may
be subjective nonetheless.

This list is compiled and maintained by Paul Sokolovsky, [@pfalcon](https://github.com/pfalcon/).
This list is licensed under [Creative Commons Attribution-ShareAlike 4.0 
International License (CC BY-SA 4.0)](https://creativecommons.org/licenses/by-sa/4.0/):
you are free to share and reuse contents of this list, as long as you
give credit to the original author and allow other people to share/reuse
it under the same terms.

Forks
=====

There are more than 2000 forks of MicroPython on Github, and here are
a few notable ones:

* [Advanced MicroPython (codename "Pycopy")](https://github.com/pfalcon/micropython) -
by [@pfalcon](https://github.com/pfalcon/), 2nd largest (~35%) contributor
to MicroPython. Dedicated to further developing all the great features which
were initially contributed to the mainline - stream I/O interface, async
support, memory-saving APIs, etc. Also to optimizations, bugfixes and improved
documentation. Synced with the mainline, improvements contributed back.
* [Pycom MicroPython](https://github.com/pycom/pycom-micropython-sigfox) -
by [@pycom](https://github.com/pycom/). Support for modern communication
standards like LoRa, Sigfox, etc.
* [CircuitPython](https://github.com/adafruit/circuitpython) -
by [@adafruit](https://github.com/adafruit/). Education friendly MicroPython
fork, concentrating on microcontroller boards of a particular vendor.
Wealth of online tutorials and educational resources.
* [Loboris ESP32 fork](https://github.com/loboris/MicroPython_ESP32_psRAM_LoBo) -
by [@loboris](https://github.com/loboris). Concentrates on ESP32. A number
of C libraries are wrapped.

OS/RTOS ports/forks
===================

* POSIX/Unix - part of the mainline. The POSIX port is the biggest and most
important MicroPython target, alone supporting thousands of diverse computer
and device types, ranging from supercomputers to a few-dollar appliances.
* Windows - part of the mainline. Runs on different Windows variants, from
server down to Windows IoT.
* DOS/DJGPP - part of the mainline. Runs on DOS versions with support of x86
extended mode.
* [Zephyr port](https://github.com/pfalcon/micropython) - Modern advanced RTOS,
more than 100 boards supported.
* FreeRTOS port - part of the mainline (as CC3200 port).
* [mbedOS port](https://os.mbed.com/users/infinnovation/code/micropython/) -
RTOS for ARM microcontrollers, dozens of boards supported.
* [FrostedOS port](https://github.com/insane-adding-machines/micropython) -
POSIX-compatible RTOS.

Tools
=====

* Local access: MicroPython comes with REPL (read-evaluate print loop,
interactive prompt), which you can access right in your terminal, or by
connecting over UART (serial) or USB to another device.
* Remote access:
  * Telnet - available for some ports (e.g. CC3200), 3rd-party libraries
    for other ports.
  * WebREPL - REPL in your browser using Websockets! Official client:
    http://micropython.org/webrepl/ . Can be
    [deployed locally](https://github.com/micropython/webrepl/).

Libraries
=========

Standard Libraries
------------------

* [micropython-lib](https://github.com/pfalcon/micropython-lib) - dozens
  of modules ported from CPython, dozens developed specifically for
  MicroPython.

Graphics
--------

Graphical User Interfaces (GUI)
-------------------------------

Text User Interfaces (TUI)
--------------------------

Databases
---------

Asynchronous Scheduling and I/O
-------------------------------

Protocols
---------

Web Frameworks
--------------


Education and courses
=====================

* University of California, Berkeley. [EE 49: Electronics for IoT](https://people.eecs.berkeley.edu/~boser/courses/49/index.html).
