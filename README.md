<h1>Simulation-of-Smart-Home-Automation</h1>
This project focuses on how different devices within a Smart house such as IoT devices, sensors communicate with each other. We have tried to simulate for 4 different houses namely veda house, joel house, shenthan house, bhargav house.



The subnets used for each house are: <br/>
Veda House adopts the subnet 172.17.68.1/26 <br/>
Shenthan House adopts 172.17.68.65/26 <br/>
Joel House adopts 172.17.68.129/26 <br/>
Bhargav House adopts 172.17.68.203/26.

The project mandates static IP address assignment, foregoing DHCP, for all devices.
Additionally, SSH is configured on routers for remote login, fostering secure
monitoring and control.This comprehensive approach aims to create a secure,
interconnected smart home ecosystem across the four houses with statically
assigned IP addresses for enhanced control and monitoring.

Ip address configuration used for veda house:<br/>
IP ADDRESS BLOCK: 192.168.1.0/24<br/>
SUBNET MASK: 2255.255.255.0<br/>
RANGE: 192.168.1.1-192.168.1.62<br/>

Ip address configuration used for shenthan house:<br/>
IP ADDRESS BLOCK: 192.168.1.0/24<br/>
SUIBNET MASK: 255.255.255.0<br/>
RANGE: 192.168.1.65-192.168.1.126<br/>

Ip address configuration used for bhargav house:<br/>
IP ADDRESS BLOCK: 192.168.2.0/24<br/>
SUBNET MASK: 255.255.255.0<br/>
RANGE: 192.168.2.1-192.168.2.62<br/>

Ip address configuration used for joel house:<br/>
IP ADDRESS BLOCK: 192.168.2.0/24<br/>
SUBNET MASK: 255.255.255.0<br/>
RANGE: 192.168.2.65-192.168.2.126<br/>

<a href="https://www.pinterest.com.au/pin/sykati--508906826651757404/">The template for the background can be found here</a>

This is how a single house would look like:

![image](https://github.com/q35u437/Simulation-of-Smart-Home-Automation/assets/35828699/ccf80a14-a5cc-454b-8928-716829e48fce)

We have used two DNS servers one for name resolution, one for running the IoT services.

Users opens his web browser or the IoT application in his phone and authenticates himself using id and password. Then he will get the state of all devices in his phone currently.


Accesing the web page using web client.

![image](https://github.com/q35u437/Simulation-of-Smart-Home-Automation/assets/35828699/02c3e06b-50a1-40dc-b3e7-b3615023fc3c)

After logging in this is how the user IoT devices will look like:

![image](https://github.com/q35u437/Simulation-of-Smart-Home-Automation/assets/35828699/9088322e-90e1-4827-85f1-8ab4944fb905)

# Conclusion
We were able to implement and simulate how devices in  a particular network would communicate with each other by using concepts such as Subnets, VLANS, DNS, and other stuff.
