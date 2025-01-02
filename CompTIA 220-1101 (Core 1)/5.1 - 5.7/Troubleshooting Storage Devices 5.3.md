**-- Storage failure symptoms --**
Read/write failure
- "Cannot read from the source disk"

Slow performance
- Constant LED activity
- Retry...retry...retry

Loud clicking noise
- The click of death
- May also include grinding and scraping


**-- Troubleshooting disk failures --**
Get a backup
- First thing - a bad drive is bad

Check for loose or damaged cables

Check for overheating
- Especially if problems occur after startup

Check power supply
- Especially if new devices were added

Run hard drive diagnostics
- From the drive or computer manufacturer
- Preferably on a known-good computer
---
**-- Boot failure symptoms --**
Drive not recognized, Boot Device Not Found
- Light (or no lights)
- Beeps
- Error messages

Operating system not found
- The drive is there
- Windows is not


**-- Troubleshooting boot failures --**
Check your cables
- Physical problem

Check boot sequence in BIOS
- Check for removeable disks (especially USB)
- Check for disabled storage interfaces

For new installation, check hardware configuration
- Data and power cables
- Try different SATA interfaces

Try the drive in a different computer

---
**-- Data loss/corruption --**
Hard drives are mechanical devices
- They will eventually fail

Repairs are difficult and expensive
- Dust-free environment
- Not always successful

An SSD may simply stop working
- Sometimes can read but not write

Data becomes unavailable or corrupted
- Can be impossible to recover

ALWAYS HAVE A BACKUP

---
**-- RAID not found --**
Missing or faulty RAID controller

![[Pasted image 20250102115518.png]]

Each RAID is different
- Don't start pulling drives until you check the console!

![[Pasted image 20250102115600.png]]


**-- RAID recovery --**

![[Pasted image 20250102115631.png]]

---
**-- S.M.A.R.T --**
Self-Monitoring, Analysis, and Reporting Technology
- Use third-party utilities

Avoid hardware failure
- Look for warning signs

Schedule disk checks
- Built-in to most drive arrays

Warning signs
- Replace a drive
---
**-- Extended read/write times --**
A lot happens when reading or writing data
- Memory access, communication across the bus, spinning drive access, writing or reading the data to the storage device, etc.

Delays can occur anywhere along the way
- Need a way to measure storage device access

Input/output operations per second (IOPS)
- A broad metric of maximum performance

Useful for comparing storage devices
- Hard drive :200 IOPS
- SSD: 1,000,000 IOPS
---
**-- Missing drives in OS --**
OS boots normally
- Other drives not shown
- Check the BIOS

Internal drives
- Bad drive or disconnected cable

Extended drives
- No power to the drive or bad cable connection

Network shares
- Shared drives can be connected during startup
- Option to reconnect at sign-in
- Connected with login script