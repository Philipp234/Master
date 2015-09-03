# Master
All src files and descriptions relevant to my master thesis.

ToDo:
( ) Descripe how to set up environment 
    (mininet, ryu, OFSoftswitch)
( ) all controller scripts should be placed in ryu/ryu/app
    -> to start mininet using the soft switch: 
	$ sudo mn --switch user,protocols=OpenFlow13 --controller remote
    -> start a controller app:
	$ PYTHONPATH=. ./bin/ryu-manager ryu/app/<scriptname.py>