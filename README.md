# CANCMDDC-Arduino

This project is for an Arduino to control a number of analogue (DC) train controllers 
in response to Merg CBus messages originally intended for use between the CANCAB hand 
throttle and the CANCMD DCC Command Station. The Arduino effectively 'spoofs' a number
of DCC addresses that are then used to control the analogue throttles. It can be used
either 'standalone', or alongside a CANCMD which can then be used to also control DCC
locomotives on a separate track.

Development of this project is documented on the Merg Forum here:
     http://www.merg.org.uk/forum/viewtopic.php?f=45&t=6376

This sketch makes use of the latest version of the MCP_CAN library. It can be found here:
     https://github.com/coryjfowler/MCP_CAN_lib

