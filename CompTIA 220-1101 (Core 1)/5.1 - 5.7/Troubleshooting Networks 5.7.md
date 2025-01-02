**-- No network connectivity --**
Do you have a link light?
- Is it plugged in?

Ping loopback (127.0.0.1)
- Is the protocol stack working?
- Availability and intermittent connectivity

Ping local IP address
- Checks local configuration, adapter, and link signal

Ping default gateway
- Connectivity on the local network

Ping devices on router's other side
- 8.8.8.8 or 9.9.9.9
---
**-- Intermittent wireless connectivity --**
Interference
- Something else is using our frequency

Signal strength
- Transmitting signal, transmitting antenna, receiving antenna, etc.

Incorrect channel
- Usually automatic; look for manual tuning

Bounce and latency
- Multipath interference; flat surfaces

Incorrect access point placement
- Locate close to the users
---
**-- Wireless interference --**
Predictable
- Fluorescent lights
- Microwave ovens
- Cordless telephones
- High-power sources

Unpredictable
- Multi-tenant building

Measurements
- Signal to noise ratio (SNR)
- Performance Monitor
---
**-- Signal to noise ratio (SNR) --**
Signal
- What you want

Noise
- What you don't want
- Interference from other networks and devices

You want a very large ratio
- The same amount of signal to noise (1:1) would be bad
---
**-- Limited or no connectivity --**
Windows alert in the system tray
- "Limited or No connectivity"
- "No Internet Access"

Check the local IP address
- An APIPA address will only have local connectivity

If DHCP address is obtained, perform the ping tests
- Local gateway, remote IP address
---
**-- Jitter --**
Most real-time media is sensitive to delay
- Data should arrive at regular intervals
- Voice communication, live video

If you miss a packet, there's no retransmission
- There's no time to "rewind" your phone call

Jitter is the time between frames
- Excessive jitter can cause you to miss information, "choppy" voice calls
---
**-- Poor VoIP quality --**
High speed and low latency
- Real-time applications are demanding

Check the Internet connection
- A speed test can identify slow links

Verify the local networking equipment
- An old router can cause significant problems

View the network performance
- A packet capture would be useful
---
**-- Latency --**
A delay between the request and the response
- Waiting time

Some latency is expected and normal
- Laws of physics apply

Examine the response times at every step along the way
- This may require multiple measurement tools

Packet captures can provide detailed analysis
- Microsecond granularity
- Get captures from both sides
---
**-- Port flapping --**
Network interface goes up and down
- Over and over again

Verify the cable
- Check the wiring

Move between switch interfaces
- Is the flapping associated with the switch interface or the device?

Replace bad hardware or cables
- May require additional purchases