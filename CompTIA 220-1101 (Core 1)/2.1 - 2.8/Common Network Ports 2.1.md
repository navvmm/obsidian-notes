**-- Port Numbers --**
Well-known port number
- Client and server need to match

Important for firewall rules
- Port-based security

A bit of rote memorization
- Becomes second nature after a while

Make sure you know port number, protocol and how the protocol is used

---
**-- FTP - File Transfer Protocol --**
tcp/20 (active mode data), tcp/21 (control)
- Transfer files between systems

Authenticates with a username and password
- Some systems use a generic/anonymous login

Full-featured functionality
- List, add, delete, etc.
---
**-- SSH - Secure Shell --**
Encrypted communication link - tcp/22

Looks and acts the same as Telnet

---
**-- Telnet --**
Telnet- Telecommunication Network
- tcp/23

Login to devices remotely
- Console access

In-the-clear communication
- Not the best choice for production systems
- Always use SSH for terminal communication
---
**-- SMTP - Simple Mail Transfer Protocol --**
SMTP - Simple Mail Transfer Protocol
- Server to server email transfer
- tcp/25

Also used to send mail from a device to a mail server
- Commonly configured on mobile devices and email

Other protocols are used for clients to receive email
- IMAP, POP3
---
**-- DNS - Domain Name System --**
Converts names to IP address - udp/53
- .www.example.com*
These are very critical resources
- Usually multiple DNS servers are in production
---
**-- DHCP - Dynamic Host Configuration Protocol --**
Automated configuration of IP address, subnet mask and other options
- udp/67, udp/68
- Requires a DHCP server
	- Server, appliance, integrated into a SOHO router, etc.

Dynamic / pooled
- IP addresses are assigned in real-time from a pool
- Each system is given a lease and must renew at set intervals

DHCP reservation
- Addresses are assigned by MAC address in the DHCP server
- Manage address from one location
---
**-- HTTP and HTTPS --**
Hypertext Transfer Protocol
- Communication in the browser
- And by other applications

In the clear or encrypted
- Supported by nearly all web servers and clients

HTTP
- tcp/80
- Hypertext Transfer Protocol
- Web server communication

HTTPS
- tcp/443
- Hypertext Transfer Protocol Secure
- Web server communication with encryption
---
**-- POP3 / IMAP --**
Receive emails from an email server
- Authenticate and transfer

POP3 - Post Office Protocol version 3
- tcp/110
- Basic mail transfer functionality
- Cannot receive from multiple clients

IMAP4 - Internet Message Access Protocol v4
- tcp/143
- Includes management of email inbox from multiple clients
---
**-- SMB Server Message Block --**
Protocol used by Microsoft Windows
- File sharing, printer sharing
- Also called CIFS (Common Internet File System)

Using NetBIOS over TCP/IP (Network Basic Input/Output System)
- udp/137 - NetBIOS name services (nbname)
- udp/139 - NetBIOS session service (nbsession)

Direct over tcp/445 (NetBIOS-less)
- Direct SMB communication over TCP without the NetBIOS transport
---
**-- SNMP - Simple Network Management Protocol --**
Gather statistics from network devices
- Queries: udp/161
- Traps: udp/162

v1 - The original
- Structured tables
- In-the-clear

v2 - A good step ahead
- Data type enhancements
- Bulk transfer
- Still in-the-clear

v3 - A secure standard
- Message integrity
- Authentication
- Encryption
---
**-- LDAP --**
LDAP (Lightweight Directory Access Protocol)
- tcp/389

Store and retrieve information in a network directory
- Commonly used in Microsoft Active Directory
---
**-- RDP - Remote Desktop Protocol --**
Share a desktop from a remote location over tcp/3389

Remote Desktop Services on many Windows versions

Can connect to an entire desktop or just an application

Clients for Windows, macOS, Linux, Unix, iPhone, Android, and others