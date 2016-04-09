# Let's have some simple fun with a Raspberry Pi!


## What we need
1. Raspberry Pi 2
2. Formatted 8gb micro SD card
3. Micro USB power cable with an AC adapter.
4. HDMI cable
5. USB keyboard
6. USB mouse
7. Network cable or WIFI adapter

## How to Install NOOBS OS -(because of time, this step has been done)
* In order to install a basic Raspbian operating system, you can download the zip file from  https://www.raspberrypi.org/downloads/noobs/.
* Unzip the file and copy them over to a micro SD card of 8 GB or more.
* Attach the micro SD to the Raspberry Pi and power up.
* Make sure you use a power cable with an AC adapter, this prevents the Raspberry from being confused! – Think about why!
* Use one of the four USB ports on the Raspberry Pi to attach a keyboard and mouse.
* Connect the Raspberry to a Monitor or TV with the HDMI cable.
* Raspbian should be displayed as an option to install. Check the box and hit install.

## Install Wifi Adapter
•	Each table should have an Edimax WIFI USB adapter. Connect the adapter to one of the USB ports on the Raspberry Pi
•	On the upper right corner, you should see a network sign that shows you as disconnected. Click on that sign. If you don't see the identified networks you may need to restart Raspbian.
#### TODO
•	Join “TheForge” with Password “agileLIVE!”
•	Open the Epiphany Web Browser and navigate to your favorite coding site.

## Install Apache Webserver
* Install the apache 2 package with the following command on Terminal:
`sudo apt-get install apache2 –y`
* By default, Apache puts a test HTML file in the web folder. Browse to this page at http://localhost/ on the Pi.
* Edit this existing test page or swap it out with your own.
*	Navigate to another team's host page and see what they have done.
* The following command on Terminal should show your local ipaddress : `hostname -i`

## Shut down Raspbian
* To shut down, go to the Raspbian Menu and select shut down.
* When prompted, click on OK
