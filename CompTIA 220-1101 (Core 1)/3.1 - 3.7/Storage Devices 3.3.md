**-- Hard disk drives (HDD) --**
Non-volatile magnetic storage
- Rapidly rotating platters

Random-access
- Retrieve data from any part of the drive at any time

Moving parts
- Spinning platters, moving actuator arm
- Mechanical components limit the access speeds
- Mechanical components can also break 

![[Pasted image 20241127110540.png]]

---
**-- Solid-state drives (SSD) --**
Non-volatile memory
- No moving parts

Very fast performance
- No spinning drives delays

![[Pasted image 20241127110710.png]]

---
**-- mSATA (Mini-SATA) --**
Shrink the SATA drives into smaller devices
- Same data, different form factor
- Great for laptops and mobile devices

Smaller than 2.5" SATA drives
- No spinning drive
- Allows for different form factors

Was used briefly
- Quickly replaced by the M.2 standard

![[Pasted image 20241127111105.png]]

---
**-- AHCI vs. NVMe --**
SATA was designed for hard drives
- Uses AHCI (Advanced Host Controller Interface) to move drive data to RAM
- SATA revision 3 throughput up to 600 MB/s
- SSDs need a faster communication method

NVMe (Non-volatile Memory Express)
- Designed for SSD speeds
- Lower latency, supports higher throughputs
- Takes advantage of NVMe with an M.2 interface
---
**-- M.2 interface --**
Smaller form factor
- No SATA data or power cables

Can use a PCI Express bus connection
- 4GB/s throughput or faster when using NVMe PCIe x4

Different connector types
- Needs to be compatible with the slot key/spacer
- B key, M key, or B and M key
- Some M.2 drives will support both
---
**-- B-key and M-key --**
M.2 doesn't guarantee NVMe
- Your M.2 interface may be using AHCI
- Check your documentation

Your motherboard may only support one type of M.2 key
- Check the documentation again
---
**-- Flash drives --**
Flash memory
- EEPROM (Electrically erasable) programmable read-only memory
- Non-volatile memory
- No power required to retain data

Limited number of writes
- Can still read the data

Not designed for archival storage
- Easy to lose or damage
- Always have a backup

![[Pasted image 20241127112707.png]]

---
**-- Optical drives --**
Small bumps read with a laser beam
- Microscopic binary storage

Relatively slow
- Archival media

Many different formats
- CD-ROM, DVD-ROM, Blu-ray

Internal and external drives
- For those uncommon application installations