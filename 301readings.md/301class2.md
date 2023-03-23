# What is a port scanner and how does it work

this is a computer program that checks network ports for open closed or filtered status's.  In the office port scanners are good for diagnosing connectivivty and network issues.  Some might use it for other resaons as to see what kind of devices you are running on your network. 

## How does a port scanner opereate 
A port scanner sends a packet of network data to a port to check the current status. 

## What is a port 
a port is a virtual location where networking communication starts and ends.

## Port scanning technics 
### Ping scan 
- looks for ICMP replies showing target is alive 
### TCP half open 
- fastest and most common scan that requests an AKC pacet from computer. 
### TCP connect 
- simialr to half open but instead completes the TCP connection 
### UDP
- slow acting, works best when sending specific payload to a target. 
### Stealth scanning 
- least obvious and most quitest from 

## How to detect a port scan 
To detect if you have been or are being comprimised there are dedicated port scanning softwares such as PortSentry or Scnagold.  These softwares should be run proactivly to detect and close vulnerabilities that may be attacted or exploited.  

## Common ports 
* Telnet
    - Port number: 23
    - Description: Used for remote access to a computer or network. 
* SSH
    - Port number: 22
    - Description: used for secure remote access to a computer or network service.  
* DNS 
    - Port number: 53
    - Description: used for translating domain names into IP address. 
* SMPT
    - Port number: 25
    - Description: used for sending and receiving email messages. 
* HTTP
    - Port number: 80
    - Description: used for accessig web pages 
* HTTPS
    - Port number: 443
    - Description: used for accessing web pages securely 
* RDP
    - Port number: 3389
    - Description: used for remote desktop access. 
* Ping
    - Port number: N/A
    - Description: a utility used for testing network connectivity and does not use a specific port. 

-- source https://www.varonis.com/blog/port-scanning-techniques 