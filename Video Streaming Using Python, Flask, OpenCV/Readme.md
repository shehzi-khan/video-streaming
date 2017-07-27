Requirements:
----------------------------------------------------------------------------

Server:
___________________________________________________________
* Operating System:         Windows or Linux
* Additional Hardware:      Webcam
* Python Interpreter:       Python 2.7
* Python Package Manager:   PIP
* Python Packages:
  * FLASK         Use Following Command to Install:   pip install flask
  * OpenCV        Use Following Command to Install:   pip install opencv-python
  
Client:
______________________________________________________________
* Operating System:         Windows or Linux
* Python Interpreter:       Python 2.7
* Python Package Manager:   PIP
* Python Packages:
  * Opencv        Use Following Command to Install:   pip install opencv-python
  * urllib        Use Following Command to Install:   pip install urllib
  * numpy         Use Following Command to Install:   pip install numpy
Browser:
  None other than Browser itself


Try out following steps:
----------------------------------------------------------------
1.  Make sure client and server can reach each other via network. 
2.  Check Server IP address using "ipconfig" in windows cmd and "ifconfig" in linux shell.
3.  Run server_app on the system that has camera connected to it. It will stream video at servers ip and port 5000.
4.  Checkout video stream in browser by visiting <server-ip-address>:5000
5.  Replace the ip address in client_app with server's ip address.
6.  Copy the client_app to another machine and try to run it.
