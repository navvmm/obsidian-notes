***
**-- Operating system technologies --**
32-bit vs. 64-bit
- Processor specific

32-bit processors can store 2^32 = 4,294,967,296 values

64-bit processors can store 2^64 = 18,446,744,073,709,551,616 values
- 4GB vs. 17 billion GB
- The OS has a maximum supported value

Hardware drivers are specific to the OS version (32-bit / 64-bit)
- 32-bit (x86), 64-bit (x64)

32-bit OS cannot run 64-bit apps
- But 64-bit OS can run 32-bit apps

Apps in a 64-bit Windows OS
- 32-bit apps: \Program Files (x86)
- 64-bit apps: \Program Files
---
**-- Advanced RISC Machine (ARM) --**
CPU architecture developed by Arm Ltd.
- They design the chip, others license and build

Simplified instruction set
- Efficient and fast processing
- Less power
- Less heat

Traditionally used for mobile and IoT devices
- The lines are constantly blurring
---
**-- Processor Cores --**

![[Pasted image 20241213123938.png]]

---
**-- Multithreading --**
Hyper-Threading Technology (HTT)

One CPU, acts like two

Doesn't actually work as fast as two
- 15% to 30% performance improvement

Operating system must be written for HTT
- Windows XP and later (any modern OS)
---
**-- Virtualization support --**
Run other operating systems within a single hardware platform
- Multiple operating systems share physical hardware components

Virtualization in software was limited
- Performance and hardware management challenges

Virtualization added to the processor
- Hardware is faster and easier to manage
- Intel Virtualization Technology (VT)
- AMD Virtualization (AMD-V)