# Cisco Packet Tracer
______________________________

![Eva_Capture1583557455](https://github.com/user-attachments/assets/218f519b-4972-4098-be57-5692a81ce01a)

![Eva_Capture648911341](https://github.com/user-attachments/assets/3ab448f2-e1de-4cb2-bef6-797544c8f4c5)

<br/>
<br/>
<br/>

## Features

### DHCP SERVERS

![Eva_Capture1941246351](https://github.com/user-attachments/assets/057908b2-3f13-4fc3-a7d9-b52bad42855e)

![Eva_Capture1019659414](https://github.com/user-attachments/assets/4edf3884-6f69-4b2a-b916-f59ba9a4b743)

<br/>
<br/>

### Voice Over IP

![Eva_Capture2058767428](https://github.com/user-attachments/assets/ce3e08cc-66fb-4a1f-81e9-27929eca2274)

<br/>
<br/>

### Telnet, port level security, and device level security

![Eva_Capture461903323](https://github.com/user-attachments/assets/51dbdaba-14c9-4178-a2bd-37b787203fd7)

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
