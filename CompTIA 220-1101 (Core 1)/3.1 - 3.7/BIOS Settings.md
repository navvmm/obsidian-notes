***
**-- The secret button(s) --**
Launching the system setup
- Del, F1, F2, Ctrl-S, Ctrl-Alt-S

Hyper-V (Windows 8/10/11)
- Turn Windows features on and off


VMware Workstation Player
- -http://www.vmware.com/products/player

But not VirtualBox
- -http://www.virtualbox.org

Many simulators online
- Search for "UEFI BIOS simulator"
---
**-- Fast startup --**
Windows 8, 10, and 11
- Doesn't actually shut down all the way
- Starts up so quickly, you can't open the BIOS configuration

From the Windows desktop
- Hold down shift when clicking Restart
- Settings / Update & Security / Recovery / Advanced startup / Restart now
- System Configuration (msconfig)

Interrupt normal boot three times
- Presents the boot option screen now\
- Turns off fast startup
---
**-- Important tips --**
Make a backup of your BIOS configuration
- Write detailed notes
- Take a picture

Doesn't make a change unless you're certain of the settings
- It's difficult to leave it alone
---
**-- Boot options --**
What happens when you power on?
- The BIOS knows

Disable hardware
- Unavailable to the operating system

Modify the boot order
- Which boots first?
- Move to the next in order
- USB drive, SSD, hard drive
---
**-- USB permissions --**
A security challenge
- Very small storage devices
- Very large capacities

USB connections
- Convenient
- High speed

US Department of Defense banned USB flash media for 15 months in 2008
- SillyFDC worm
---
**-- Fans --**
Computing power creates heat
- A lot of heat!

Many different cooling fans
- CPU fans 
- Chassis fans

Motherboards often include an integrated fan controller
- And temperature sensors
- The motherboard increases and decreases the fan speeds
---
**-- Secure Boot --**
Malicious software can "own" your system
- Malicious drivers or OS software

Secure boot
- Part of the UEFI specification

Digitally sign known-good software
- Cryptographically secure
- Software won't run without the proper signature

Support in many different operating systems
- Windows and Linux support


**-- UEFI BIOS Secure Boot --**
UEFI BIOS protections
- BIOS includes the manufacturer's public key
- Digital signature is checked during a BIOS update
- BIOS prevents unauthorized writes to the flash

Secure Boot verifies the bootloader
- Checks the OS bootloader's digital signature
- Bootloader must be signed with a trusted certificate
- Or a manually approved digital signature
---
**-- Boot password management --**
BIOS Password / User Password
- System won't start
- Need the password to start the operating system

Supervisor Password
- Restrict BIOS changes
- Must use supervisor password to change any BIOS configurations

Remember your password!
- Must reset the BIOS to recover


**-- Clearing a boot password --**
Store the BIOS configuration
- Your settings

Complementary metal-oxide semiconductor (CMOS)
- A type of memory
- May be backed up with a battery

Usually flash memory these days
- Easily stored and accessed

Reset with a jumper
- Short (connect) two pins on the motherboard
---
**-- The "CMOS" battery --**
Not needed for today's flash-based storage
- Maintains older BIOS configurations
- May only be used to maintain date/time

A bad battery will require a BIOS configuration or date/time configuration on every boot

On older systems, can reset the BIOS configuration by removing the battery
- Newer computers use a jumper
---
**-- Trusted Platform Module (TPM) --**
A specification for cryptographic functions
- Hardware to help with encryption functions

Cryptographic processor
- Random number generator, key generators

Persistent memory
- Comes with unique keys burned in during production

Versatile memory
- Storage keys, hardware configuration information

Password protected
- No dictionary attacks
---
**-- Hardware Security Module (HSM) --**
Often used in large environments
- Clusters, redundant power

High-end cryptographic hardware
- Plug-in card or separate hard device

Key backup
- Secured storage for servers
- Lightweight HSMs for personal use (Smart card, USB, flash memory)

Cryptographic accelerators
- Offload that CPU overhead from other devices