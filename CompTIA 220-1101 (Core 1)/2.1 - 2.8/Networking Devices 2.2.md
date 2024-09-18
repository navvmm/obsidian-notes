**-- Network Devices --**
Many different devices and components
- All have different roles

Some of these functions are combined together
- Wireless router/switch/firewall

Compare different devices
- Understand when they should be used
---
**-- Routers --**
Routes traffic between IP subnets
- Makes forwarding decisions based on IP address
- Routers inside of switches sometimes called "layer 3 switches"

Often connects diverse network types
- LAN, WAN, copper, fiber
---
**-- Switches --**
Bridging done in hardware
- Application-specific integrated circuit (ASIC)
- Forwards traffic based on data link address

Many ports and features
- The core of an enterprise network
- May provide Power over Ethernet (PoE)

Multilayer switch
- Includes routing functionality
---
**-- Unmanaged Switches --**
Very few configuration options
- Plug and play

Fixed configuration
- No VLANs

Very little integration with other devices
- No management protocols

Low price point
- Simple is less expensive
---
**-- Managed Switch --**
VLAN support
- Interconnect with other switches via 802.1Q

Traffic prioritization
- Voice traffic gets a higher priority

Redundancy support
- Spanning Tree Protocol (STP)

Port mirroring
- Capture packets

External management
- Simple Network Management Protocol (SNMP)
---
**-- Access Point --**
Not a wireless router
- A wireless router is a router and an access point in a single device

An access point is a bridge
- Extends the wired network onto the wireless network
- Makes forwarding decisions based on MAC address
---
**-- Patch panels --**
Combination of punch-down blocks and RJ-45 connectors

Runs from desks are made once
- Permanently punched down to patch panel

Patch panel to switch can be easily changed
- No special tools
- Use existing cables
---
**-- Firewalls --**
Filters traffic by port number
- OSI layer 4(TCP/UDP)
	- Some firewalls can filter based on the application

Can encrypt traffic into/out of the network
- Protect your traffic between sites

Can proxy traffic
- A common security technique

Most firewalls can be layer 3 devices (routers)
- Usually sits on the ingress/egress of the network
---
**-- Power over Ethernet (PoE) --**
Power provided on an Ethernet cable
- One wire for both networks and electricity
- Phones, cameras, wireless access points
- Useful in difficult-to-power areas

Power provided at the switch
- Built-in power - Endspans
- In-line power injector - Midspans
- Commonly marked on the switch or interfaces
---
**-- PoE, PoE+, PoE++ --**
PoE: IEEE 802.3af-2003
- The original PoE specification
- Now part of the 802.3 standard
- 15.4 watts DC power, 350 mA max current

PoE+: IEEE 802.3at-2009
- Now also part of the 802.3 standard
- 25.5 watt DC power, 600 mA max current

PoE++: IEEE 802.3bt-2018
- 51 W (Type 3), 600 mA max current
- 71.3 W (Type 4), 960 mA max current
- PoE with 10GBASE-T
---
**-- Hub --**
"Multi-port repeater"
- Traffic going in one port is repeated to every other port

Everything is half-duplex

Becomes less efficient as network traffic increases

10 megabit / 100 megabit

Difficult to find today

---
**-- Cable Modem --**
Broadband
- Transmission across multiple frequencies
- Different traffic types

Data on the "cable" network
- DOCSIS
- (Data Over Cable Service Interface Specification)

High-speed networking
- Speeds up to 1 Gigabit/s are available

Multiple services
- Data, voice, video
---
**-- DSL Modem --**
ADSL (Asymmetric Digital Subscriber Line)
- Uses telephone lines

Download speed is faster than upload speed (asymmetric)
- ~10,000 foot limitation from the central office (CO)
- 52 Mbit/s downstream / 16Mbit/s upstream are common
- Faster speeds may be possible if closer to the CO
---
**-- ONT --**
Optical network terminal
- Fiber to the premises

Connect the ISP fiber network to the copper network
- Demarcation point (demarc) in the data center
- Terminal box on the side of the building

Line of responsibility
- One side of the box is the ISP
- Other side of the box is your network
---
**-- Network Interface Card (NIC) --**
The fundamental network device
- Every device on the network has a NIC
- Computers, servers, printers, routers, switches, phones, tablets, cameras, etc.

Specific to the network type
- Ethernet, WAN, wireless, etc.

Often built-in to the motherboard
- Or added as an expansion card

Many options
- Single port, multi-port, copper, fiber