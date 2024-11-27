**-- Data redundancy --**
Hard drives store huge amounts of data
- Important data

Hard drives are moving components
- They will eventually break

What happens to the data when the drive fails?
- You can prepare for that
- Use an Array of drives

RAID is not backup

---
**-- RAID --**
Redundant Array of Independent Disks
- They're also inexpensive disks

Different RAID levels
- Some redundant, some not
---
**-- RAID 0 - Striping --**

![[Pasted image 20241127113517.png]]

File blocks are split between two or more physical drives

High performance
- Data written quickly

No redundancy
- A drive failure breaks the array
- Raid 0 is zero redundancy


**-- RAID 1 - Mirroring --**

![[Pasted image 20241127113712.png]]

File blocks are duplicated between two or more physical drives

High disk utilization
- Every file is duplicated
- Required disk space is doubled

High redundancy
- Drive failure does not affect data availability


**-- RAID 5 - Striping with parity --**

![[Pasted image 20241127114007.png]]

File blocks are striped
- Along with a parity block
- Requires at least three disks

Efficient use of disk space
- Files aren't duplicated, but space is still used for parity

High redundancy
- Data is available after drive failure
- Parity calculation may affect performance
---
**-- RAID 10 (1+0) - A stripe of mirrors --**
The speed of striping, the redundancy of mirroring
- The best of both worlds

Need at least 4 drives

![[Pasted image 20241127123254.png]]

