
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
**-- Authentication Server --**
Login authentication to resources
- Centralized management

Almost always an enterprise service
- Not required on a home network

Usually a set of redundant servers
- Always available
- Extremely important service
---
**-- Spam --**
Unsolicited messages 
- Email, forums, etc.

Various content
- Commercial advertising
- Non-commercial proselytizing
- Phishing attempts

Significant technology issue
- Security concerns, resource utilization, storage costs, managing the spam

**-- Spam gateways --**
Unsolicited email
- Stop it at the gateway before it reaches the user
- On-site or cloud-based
---
**-- All-in-one security appliance --**
Next-generation firewall, Unified Threat Management (UTM) / Web security gateway
URL filter / Content inspection
Malware inspection
Spam filter
CSU/DSU
Router, Switch
Firewall
IDS/IPS
Bandwidth shaper
VPN endpoint

---
**-- Load balancers --**
Distribute the load
- Multiple servers
- Invisible to the end-user

Large-scale implementations
- Web server farms, database farms

Fault tolerance
- Server outages have no effect
- Very fast convergence

**-- Load balancer features --**
Configurable load
- Manage across servers

TCP offload
- Protocol overhead

SSL offload
- Encryption

Caching
- Fast response

Prioritization
- QoS

Content switching
- Application-centric balancing
---
**-- Proxy Server --**
An intermediate server
- Client makes the request to the proxy
- The proxy performs the actual request
- The proxy provides results back to the client

Useful features
- Access control, caching, URL filtering, content scanning
---
**-- SCADA / ICS --**
Supervisory Control and Data Acquisition System
- Large-scale, multi-site Industrial Control Systems (ICS)

PC manages equipment
- Power generation, refining, manufacturing equip

Distributed control systems
- Real-time information
- System control

Requires extensive segmentation
- No access from the outside
---
**-- Legacy and embedded systems --**
Legacy systems
- Another expression for "really old"
- May also be "really important"
- Learning old things can be just as important as learning the new things

Embedded systems
- Purpose-built device
- Not usual to have direct access to the operating system
- Alarm system, door security, time card system
---
**--IoT (Internet of Things) devices --**
Appliances
- Refrigerators

Smart devices
- Smart speakers respond to voice commands

Air control
- Thermostats, temperature control

Access
- Smart doorbells

May require a segmented network
- Limit any security breaches