# homeServer

Hardware
------------------------
1 Raspberry pi

1 Lamp

1 relay (5V logic input, handels 220V 10A)

1 double throw switch

1 sensor (a sensor of any kind to indicate that the lamp is turned on)

Software
------------------------
1 Node Server

1 Web page for the mobile phone user

1 Python program to read the gpio pins and write a text file to communicate with the Node Server 

Description
------------------------
A Raspberry pi is used as a server. When prompted by the user through the web page
it switches the relay which is connected in series with a double throw switch to 
turn off/on a lamp.

The double throw switch allows both switching manually and through the relay independently.

The sensor allows the Raspberry pi to monitor the state of the lamp.

The web page is hosted only locally using a nerby wireless router.
