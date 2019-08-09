========================
1. Installing GPIO Zero
========================


GPIO Zero is installed by default in the Raspbian image, and the Raspberry Pi Desktop image for PC/Mac, both available from raspberrypi.org. Follow these guides to installing on Raspbian Lite and other operating systems, including for PCs using the remote GPIO feature.

-----------------
1.1. Rasberry Pi
-----------------

First, update your repositories list:

+---------------------------------+
|pi@raspberrypi:~$ sudo apt update|
+---------------------------------+

Then install the package for Python 3:

+---------------------------------------------------+
|pi@raspberrypi:~$ sudo apt install python3-gpiozero|
+---------------------------------------------------+

or Python 2:

+--------------------------------------------------+
|pi@raspberrypi:~$ sudo apt install python-gpiozero|
+--------------------------------------------------+

If you’re using another operating system on your Raspberry Pi, you may need to use pip to install GPIO Zero instead. Install pip using get-pip and then type:

+--------------------------------------------+
|pi@raspberrypi:~$ sudo pip3 install gpiozero|
+--------------------------------------------+

or for Python 2:

+-------------------------------------------+
|pi@raspberrypi:~$ sudo pip install gpiozero|
+-------------------------------------------+

To install GPIO Zero in a virtual environment, see the Development page.

-----------
1.2. PC/Mac
-----------

In order to use GPIO Zero’s remote GPIO feature from a PC or Mac, you’ll need to install GPIO Zero on that computer using pip. See the Configuring Remote GPIO page for more information.

