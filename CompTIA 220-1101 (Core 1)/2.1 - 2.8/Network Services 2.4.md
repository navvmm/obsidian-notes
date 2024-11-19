**-- DNS server --**
Domain Name System
- Convert names to IP addresses
- And vice versa

Distributed naming system
- The load is balanced across many different servers

Usually managed by the ISP or enterprise IT department
- A critical resource
---
**-- DHCP server --**
Dynamic Host Configuration Protocol
- Automatic IP address configuration

Very common service
- Available on most home routers

Enterprise DHCP will be redundant
- Usually running on central servers
---
**-- File server --**
Centralized storage of documents, spreadsheets, videos, pictures, and any other files
- A fileshare

Standard system of file management
- SMB (Server Message Block), Apple Filing Protocol (AFP), etc.

The front-end hides the protocol
- Copy, delete, rename, etc.
---
**-- Printer server --**
Connect a printer to the network
- Provide printing services for all network devices

May be software in a computer
- Computer is connected to the printer

May be built-in to the printer
- Network adapter and software

Uses standard printing protocols
- SMB (Server Message Block), IPP (Internet Printing Protocol), LPD (Line Printer Daemon)
---
**-- Mail server --**
Store your incoming mail
- Send your outgoing mail

Usually managed by the ISP or the enterprise IT department
- A complex set of requirements

Usually one of the most important services
- 24x7 support
---
**-- Syslog --**
Standard for message logging
- Diverse systems, consolidated log

Usually a central logging receiver
- Integrated into the SIEM

You're going to need a lot of disk space
- No, more. More than that.
---
**-- Web server --**
Respond to browser requests
- Using standard web browsing protocols - HTTP / HTTPS
- Pages are built with HTML, HTML5

Web pages are stored on the server
- Downloaded to the browser
- Static pages or built dynamically in real-time
---
**-- AN AWESOME EDIT --**