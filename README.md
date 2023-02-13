# Cisco Packet Tracer 
______________________________


## FEATURES:  DHCP SERVERS, Voice Over IP, Telnet, port level security, and device level security

<br>

## Functionality
____________________

The project consists of two interconnected networks. Both network devices can communicate with each other within their network and between networks, excepting the VoIP phones.

<br>
<br>

## SECURITY
_______________

For the port level security, all the devices within the network have password protection on the console ports and auxiliary ports, respectively. Also, the devices on the network are set to have connected to each port only one MAC address and if this rule is violated, the ports on which this violation occured will shut down. Also for the port level security, all the unsused ports were shut down.
For the device level security, a MD5 encrypted password stored as a hash is used in order for authentification when a user is trying to enable the configuration menu on any device. When the user enables the configuration menu on any device, the password inserted by the user is hashed and compared with the password stored in a hash format. If the passwords match, access is grated.  
