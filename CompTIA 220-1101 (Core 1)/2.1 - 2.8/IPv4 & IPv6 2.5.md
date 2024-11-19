Ipv4 is the primary protocol for everything we do
- Included in almost all configurations

IPv6 is now part of all major operating systems
- And the backbone of our Internet infrastructure
---
**-- IPv4 Addresses --**
Internet Protocol version 4
- OSI Layer 3 address
 ![[Pasted image 20241119122409.png]]
Since one byte is 8 bits, the maximum decimal value for each byte is 225

---
**-- IPv6 addresses --**
Internet Protocol v6 - 128-bit address
- 340,282,366,938,463,374,607,431,768,211,456 addresses (340 undecillion)
- 6.8 billion people could have 5 Nonillion addresses each
 ![[Pasted image 20241119122856.png]]
Your DNS is very important!
First 64 bits in generally the network prefix (/64)
Last 64 bits is then the host network address

---
**-- Networking with IPv4 --**
IP Address, e.g., 192.168.1.165
- Every device needs a unique IP address

Subnet mask, e.g., 255.255.255.0
- Used by the local device to determine what subnet it's on
	- The subnet mask isn't (usually) transmitted across the network
	- You'll ask for the subnet mask all the time
		- "What's the subnet mask of this network?"

Default gateway, e.g., 192.168.1.1
- The router that allows you to communicate outside of your local subnet
- The default gateway must be an IP address on the local subnet
---
**-- DNS servers --**
We remember names
- professormesser.com, google.com, youtube.com

Internet routers don't know names
- Routers only know IP addresses

Something has to translate between names an IP addresses
- Domain Name Service

You configure **two** DNS servers in your configuration
- That's how important it is