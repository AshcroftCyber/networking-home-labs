🌐 Lab 3: IPv4 Communication and Addressing
📌 Overview
This lab explores how devices communicate in a network using different IPv4 transmission methods and address types. Practical tests were performed to observe unicast, broadcast, and special IP behaviors.

🎯 Objectives
Understand unicast, broadcast, and multicast communication
Identify private vs public IP addresses
Test loopback and link-local addresses
Observe how devices behave in a local network
🛠️ Tools Used
Command Prompt (Windows)
ipconfig
ping
🔬 Part 1: Unicast Communication
Procedure
Open Command Prompt

Run:

ipconfig
Identify your IPv4 Address and Default Gateway

Ping the gateway:

ping <default_gateway>
Example
ping 192.168.1.1
Result

Reply received from a single device.

Explanation

Unicast is one-to-one communication, where a packet is sent from one device to another specific device.

📡 Part 2: Broadcast Communication
Procedure

Run:

ping 255.255.255.255
Result
May show no replies or limited response depending on network restrictions
Explanation

Broadcast sends a packet to all devices on the local network.
Routers typically block broadcast traffic, so it stays within one network.

🌐 Part 3: Multicast Communication
Observation

Multicast addresses range from:

224.0.0.0 – 239.255.255.255

Example:

224.0.0.5
Explanation

Multicast is one-to-many (selected group) communication.
Only devices subscribed to the multicast group receive the data.

🔐 Part 4: Public vs Private IP Addresses
Procedure

Run:

ipconfig
Observation

Common private IP ranges:

192.168.x.x
10.x.x.x
172.16.x.x – 172.31.x.x
Explanation
Private IPs are used within local networks
Public IPs are used on the internet and must be unique
🔁 Part 5: Loopback Address Test
Command
ping 127.0.0.1
Result

Successful reply from your own system.

Explanation

The loopback address is used to test the internal network stack of your device.
If it fails, the issue is within your system.

⚠️ Part 6: Link-Local (APIPA)
Observation

Link-local range:

169.254.0.0 – 169.254.255.255
Explanation

This address is automatically assigned when:

A device cannot reach a DHCP server
No manual IP is configured
🧠 Key Takeaways
Unicast → One-to-one communication
Broadcast → One-to-all (within a network)
Multicast → One-to-selected group
Private IPs are not internet-routable
Loopback (127.0.0.1) tests your own system
APIPA (169.254.x.x) means DHCP failed
🚀 Conclusion
This lab demonstrated how IPv4 communication works across different transmission types and address categories. Understanding these concepts is essential for troubleshooting and designing efficient networks.
