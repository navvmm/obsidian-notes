**-- The SCSI Standard --**
Small Computer Systems Interface
- Not really "small" any longer

Originally designed to string many peripherals together onto a single cable/controller
- Up to 15 devices in a SCSI "chain"

Many different formats
- Fast SCSI, Ultra SCSI, Ultra Wide SCSI, Ultra2 SCSI, Ultra3 SCSI, Ultra-320 SCSI, Ultra-640 SCSI, iSCSI (SCSI over IP)

Parallel and serial options

---
**-- SCSI advantages --**
Not just for hard drives
- Scanners, tape drives, CD-ROM drives

Many devices on a single bus
- 8 on narrow bus, 16 on wide bus

Very intelligent interface functionality
- Much of the difficult configuration work is done between the SCSI devices

Industry longevity
- Well supported in the enterprise
- A standard drive for virtual systems

![[Pasted image 20241125122503.png]]

![[Pasted image 20241125122623.png]]

---
**-- SCSI ID and logical unit (LUN) --**
Every SCSI device on a single bus is assigned a separate ID number
- SCSI ID 0 (SCSI controller), ID 2 (hard drive), ID 3 (CD-ROM)

Logical units (LUNs) are defined within each SCSI ID
- Separate drives in a storage array or virtual machine

The signal at the "end" of a physical SCSI bus is terminated
- Can be internal to the device or separate termination device

Serial attached SCSI (SAS) devices have no jumpers, terminators, or settings.

---

![[Pasted image 20241125123029.png]]

---
**-- Serial attached SCSI --**
Move from parallel to serial
- Increased throughput
- Similar to the move from PATA to SATA

Point-to-point connection
- No more daisy chains

No termination required
- The bus has two devices on it

The control and management of SCSI
- The speed of a serial connection