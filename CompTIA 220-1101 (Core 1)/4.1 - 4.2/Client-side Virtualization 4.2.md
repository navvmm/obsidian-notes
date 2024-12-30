One computer, many operating systems
- macOS, Windows 11, Linux Ubuntu, all at the same time!

Separate OS, independent CPU, memory, network, etc.
- But really one computer

Host-based virtualization
- Your normal desktop plus others

Standalone server that hosts virtual machines
- Enterprise-level

Been around since 1967
- IBM mainframe virtualization
---
**-- Legacy software and operating systems --**
Need to run different application versions on the same system
- Run each application instance in a separate VM

Application only runs on a previous OS version
- Create a VM with the older operating system
---
**-- Cross-platform virtualization --**
Windows / macOS / Linux doesn't do everything
- Each OS has strengths and weaknesses

Run different operating systems at the same time
- Move between each OS seamlessly
- No rebooting

Save time and resources
- One physical computer
---
**-- The hypervisor --**
Virtual Machine Manager
- Manages the virtual platform and guest operating systems

May require a CPU that supports virtualization
- Can improve performance

Hardware management
- CPU
- Networking
- Security
---
**-- Resource requirements --**
CPU Processor Support
- Intel: Virtualization Technology (VT)
- AMD: AMD-V

Memory
- Above and beyond host OS requirements

Disk space
- Each guest OS has it's own image

Network
- Configurable on each guest OS (standalone, NAT, bridged, etc.)
- Virtual switch
---
**-- Sandboxing --**
Isolated testing environment
- No connection to the real world or production system
- A technological safe space

Virtualize development process
- Try some code, break some code, nobody gets hurt

Additional development features
- Roll back to a previous snapshot
- Run additional systems
---
**-- Develop --**
- Secure environment
- Writing code
- Developers test in their sandboxes

Test
- A separate virtual environment for testing
- Still in the development stage
- All of the pieces are put together
- Does it all work?
---
**-- Hypervisor security --**
Hypervisor is a sweet spot for the bad guys
- No significant vulnerabilities yet

VM escaping
- Malware recognizes it's on a virtual machine
- Malware compromises the hypervisor
- Malware jumps from one guest OS to another

Many hosted services are virtual environments
- Malware on one customer's server can gather information from another
---
**-- Guest operating system security --**
Every guest is self-contained
- Like a real computer

Use traditional security controls
- Host-based firewall
- Anti-virus, anti-spyware

Watch out for rogue virtual machines (VMs)
- The bad guys try to install their own system
	- You're in big trouble

Self-contained VMs provided by 3rd parties can be dangerous
- You have no idea what's running on there
---
**-- Network requirements --**
Most client-side virtual machine managers have their own virtual (internal) networks

Shared network address
- The virtual machine shares the same IP address as the physical host
- Uses a private IP address internally
- Uses NAT to convert to the physical host IP

Bridged network address
- The VM is a device on the physical network

Private address
- The VM does not communicate outside of the virtual network