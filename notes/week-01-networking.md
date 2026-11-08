# Week 1 – Networking I

## Learning objectives
- Understand IP addresses
- Understand DNS
- Understand DHCP
- Understand ports

## Day 1 – Networking basics

### IP Address
My understanding:
An IP (Internet Protocol) address is a numerical address assigned to a device on a network. It helps identify the device and allows information to be sent to the correct destination.

For example, when my laptop connects to Wi-Fi, it receives an IP address that allows it to communicate with other devices and the internet.
An IP address identifies a network interface on a network and helps route information to the correct destination.
There are two commonly discussed types:

Private IP: Used within a local network, such as a home or college Wi-Fi network.

Public IP: Used to identify a network or device to other networks on the internet.

### DNS
My understanding:
DNS stands for Domain Name System. It translates human-readable domain names into IP addresses that computers use to communicate.

For example, when I type google.com into my browser, DNS helps find the IP address associated with that domain.

DNS is often called the phonebook of the internet.

### DHCP
My understanding:
DHCP stands for Dynamic Host Configuration Protocol. It automatically provides network configuration to devices when they connect to a network.

It can assign:

IP address

Subnet mask

Default gateway

DNS server information

For example, when my laptop connects to college Wi-Fi, DHCP can automatically provide the network settings it needs instead of requiring me to configure them manually.

### Ports
My understanding:
A port is a logical communication endpoint used by applications and services to send and receive network data.

Ports help a computer direct incoming network traffic to the appropriate service.

Examples:

Port 80 – HTTP

Port 443 – HTTPS

Port 53 – DNS

Port 22 – SSH

Ports are numbered from 0 to 65535.

They work with transport protocols such as TCP
and UDP to identify communication endpoints.

Practical exercises

1. ipconfig

Purpose: Displays the network configuration of my Windows computer.

What I learned:

IPv4 Address identifies my computer on the network.

Subnet Mask helps determine the network portion of an IP address.

Default Gateway is the device through which traffic is routed to other networks.

### My observation

The ipconfig command displayed the network
configuration of my laptop.

I observed the IPv4 address, subnet mask
and default gateway.

This helped me understand how a device
is identified and communicates within
a network.

For privacy, actual network addresses
have not been published.

2. nslookup google.com

Purpose: Queries DNS to find the IP address associated with google.com.

What I learned:

DNS helps translate domain names into IP addresses.

The command displays the DNS server used for the query and the resolved address information.

My observation:

The nslookup command successfully queried
DNS for google.com.

It displayed the DNS server used for the
query and the IP address or addresses
returned for the domain.

This helped me understand how DNS translates
domain names into IP addresses.

3. ping google.com

Purpose: Tests network connectivity by sending ICMP echo requests to a destination.

What I learned:

Reply indicates that an ICMP response was received.

Time shows approximately how long the round trip took.

Packet loss indicates how many packets did not receive a response.

My observation:

The ping command tested connectivity with
google.com using ICMP echo requests.

I observed the replies received, response
time and packet-loss statistics.

This helped me understand how ping is used
to check network connectivity.
Packets sent: 4
Packets received: 4
Packet loss: 0
Average response time: 37 ms

Day 1 Summary

Today I learned the basic concepts of networking, including IP addresses, DNS, DHCP and ports. I also practised using basic Windows networking commands to understand how my computer communicates over a network.
