**-- DHCP --**
IPv4 address configuration used to be manual
- IP address, subnet mask, gateway, DNS servers, NTP servers, etc.

October 1993 - The bootstrap protocol
- BOOTP

BOOTP didn't automatically define everything
- Some manual configurations were still required
- BOOTP also didn't know when an IP address might be available again

Dynamic Host Configuration Protocol (DHCP)
- Initially released in 1997, updated through the years
- Provides automatic address / IP configuration for almost all devices

**-- DHCP process --**
DORA
- A four-step process

**D**iscover
- Find a DHCP server
**O**ffer
- Get an offer
**R**equest
- Lock in the offer
**A**cknowledge
- DHCP server confirmation
---
**-- Step 1: Discover --**
![[Pasted image 20241119133152.png]]
- Client workstation sends a broadcast out to the network to udp/67
---
**-- Step 2: Offer --**
![[Pasted image 20241119133410.png]]

![[Pasted image 20241119133418.png]]
- Servers will send their offers back to the client workstation over a broadcast to udp/68.
- Will them examine the offers and pick one that it wants to use for the IP address assignment
---
**-- Step 3: Request --**
![[Pasted image 20241119133505.png]]
![[Pasted image 20241119133524.png]]
![[Pasted image 20241119133533.png]]
- Send another broadcast over udp/67.
- Broadcast contains a formal request to take the offer that was originally sent.
---
**-- Step 4: Acknowledge --**
![[Pasted image 20241119134018.png]]
![[Pasted image 20241119134036.png]]
![[Pasted image 20241119134044.png]]
- DHCP server sends a message back to the client workstation by default over udp/68.
- The device can assign itself with the configuration settings included in the offer.
---
**-- Turning dynamic into static --**
DHCP assigns an IP address from the first available from a large pool of addresses
- Your IP address will occasionally change

You may not want your IP address to change
- Server, printer, or personal preference

Disable DHCP on the device
- Configure the IP address information manually
- Requires additional administration

Better: Configure an IP reservation on the DHCP server
- Associate a specific MAC address with an IP address
---
**-- Avoid manual configurations --**
No DHCP server reservation
- You configure the IP address manually

Difficult to change later
- You must visit the device again

A DHCP reservation is preferable
- Change the IP address from the DHCP server
---
**-- Automatic Private IP Addressing (APIPA) --**
A link-local address
- No forwarding by routers

IETF has reserved 169.254.0.0 through 169.254.255.255
- First and last 256 addresses are reserved
- Functional block of 169.254.1.0 through 169.254.254.255

Automatically assigned
- Uses ARP to confirm the address isn't currently in use

**-- APIPA --**
![[Pasted image 20241119135932.png]]
