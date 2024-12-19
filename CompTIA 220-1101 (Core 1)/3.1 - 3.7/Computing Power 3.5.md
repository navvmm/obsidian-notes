**-- WARNING! --**
Always disconnect from the power source when working on a device
- Always. Seriously.

Some devices store a charge in capacitors
- Know how to discharge before touching

Never connect your body to any part of an electrical system
- Do not connect yourself to the ground wire of an electrical system


**-- Computer power supply --**
Computer uses DC voltage
- Most power sources provide AC voltage

Convert 120V AC or 240V AC
- To 3.3V DC, 5V DC, and 12V DC

You'll know when this isn't working
- An important component
---
**-- Amp and volt --**
Ampere (amp, A) - The rate of electron flow past a point in one second
- The diameter of the hose

Voltage (volt, V) Electrical "pressure" pushing the electrons
- How open the faucet is


**-- Power --**
Watt (W) - Measurement of real power use
- volts * amps = watts
- 120V * 0.5A = 60W


**-- Current --**
Alternating current (AC)
- Direction of current constantly reverses
- Distributes electricity efficiently over long distances
- Frequency of this cycle is important
	- US/Canada - 110 to 120 volts of AC (VAC), 60 hertz (Hz)
	- Europe - 220-240 VAC, 50 Hz

Direct current (DC)
- Current moves in one direction with a constant voltage


**-- Dual-voltage input options --**
Voltage varies by country
- US/Canada - 120 volts of AC (VAC), 60 hertz (Hz)
- Europe - 230 VAC, 50 Hz

Manually switch between 120V and 230V
- Get your meter!
- Or use an auto-switching power supply

Don't plug a 120V power supply into a 230V power source!

---
**-- Power supply output --**
Different voltages
- For different components

Positive and negative voltage
- Voltage is a difference in potential
- The electrical ground is a common reference point
- Depends on where you measure from

At the front door of your house
- The second floor is +10 feet
- The basement is -10 feet


+12V
- PCIe adapters, hard drive motors, cooling fans, most modern components

+5V
- Some motherboard components
- Many components are now using +3.3V

+3.3V
- M.2 slots, RAM slots, motherboard logic circuits

+5VSB
- Standby voltage

-12V
- Integrated LAN
- Older serial ports
- Some PCI cards

-5V 
- Available for ISA adapter cords
- Most cards didn't use it
- Today's motherboards don't have ISA slots
---
**--  24-pin motherboard power --**
Main motherboard power
- Provides +3.3V, +/-5V, and +/-12V

20 pin connector was the original ATX standard
- 24 pin was added for PCI Express power

You can connect a 24-pin connector to a 20-pin motherboard
- Some cables are 20-pin + 4-pin 
---
**-- Redundant power supplies --**
Two (or more) power supplies
- Internal to the server

Each power supply can handle 100% of the load
- Would normally run at 50% of the load

Hot-swappable
- Replace a faulty power supply without powering down
---
**-- Power supply connectors --**
Fixed connectors
- Connected to the power supply
- May have too many connectors
- May not have enough

Modular
- Add cables as needed
- Fewer leftover wires, better airflow
- A bit more expensive
---
**-- Sizing a power supply --**
Power supplies are rated by watts
- Overall and by individual voltages

Bigger isn't necessarily better
- More expensive
- Doesn't speed up your computer

Calculate the watts required for all components
- CPU, storage devices, video adapter
- Many online calculators

Video adapters are usually the largest power draw
- Many video card specifications list a recommended power supply wattage

50% capacity is a good rule of thumb
- Power supply runs efficiently and there's room to grow