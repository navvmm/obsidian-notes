**-- POST (Power On Self Test) --**
Test major system components before botting the operating system
- Main systems (CPU, CMOS, etc.)
- Video
- Memory

Failures are usually noted with beeps and/or codes
- BIOS versions can differ, check your documentation

Don't bother memorizing the beep codes
- They're all different between manufacturers
- Know what to do when you hear them
---
**-- POST and boot --**
Blank screen on boot
- Listen for beeps
- Bad video, bad RAM, bad CPU
- BIOS configuration issue

BIOS time and setting
- Maintained with the motherboard battery
- Replace the battery

Attempts to boot to incorrect device
- Set boot order in BIOS configuration
- Confirm that the startup device has a valid operating system
- Check for media in a startup device
---
**-- Crash screens --**
Windows Stop Error

Blue Screen of Death
- You don't want this

Contains important information
- Also written to event log

Useful when tracking down problems
- Sometimes more useful for manufacturer support
---
**-- Bluescreens and spontaneous shutdowns --**
Startup and shutdown BSOD
- Bad hardware, bad drivers, bad application

Use Last Known Good, System Restore, or Rollback Driver
- Try Safe Mode

Reseat or remove the hardware
- If possible

Run hardware diagnostics
- Provided by the manufacturer
- BIOS may have hardware diagnostics
---
**-- The spinning ball of death --**
The macOS X Spinning Wait Cursor
- Feedback that something is happening

The spin starts, but it never stops
- You never get back control of your computer

Many possible reasons
- Application bug
- Bad hardware
- Slow paging to disk

Restart the computer
- There may be details in the console logs
---
**-- Black screen --**
Is the monitor connected?
- We wouldn't ask if it wasn't a common solution
- Check both power and signal cable

Input selection on monitor
- HDMI, DVI, VGA, etc.

Image is dim
- Check brightness controls

Swap the monitor
- Try the monitor on another computer

No video after Windows loads
- Use VGA mode (F8)
---
**-- No power --**
No power
- No power at the source
- No power from the power supply
- Get out your multimeter

Fans spin - no power to other devices
- Where is your fan power connected?
- No POST - bad motherboard
- Case fans have lower voltage requirements
- Check the power supply output
---
**-- Sluggish performance --**
Task Manager
- Check for high CPU utilization and I/O

Windows Update
- Latest patches and drivers

Disk space
- Check for available space and defrag

Laptops may be using power-saving mode
- Throttles the CPU

Anti-virus and anti-malware
- Scan for bad guys
---
**-- Overheating --**
Heat generation
- CPUs, video adapters, memory

Cooling systems
- Fans and airflow
- Heat sinks
- Clean and clear

Verify with monitoring software
- Built into the BIOS
- Try HWMonitor
	- -http://www.cpuid.com
---
**-- Smoke and burning smell --**
Electrical problems
- The smoke makes everything work

Always disconnect power
- There should never be a burned odor

Locater bad components
- Even after the system has cooled down
- Replace all damaged components
---
**-- Intermittent shutdown --**
No warning, black screen
- May have some details in your Event Viewer

Heat-related issue
- High CPU or graphics, gaming
- Check all fans and heat sinks
- BIOS may show fan status and temperatures

Failing hardware
- Has anything changed?
- Check Device Manager, run diagnostics

Could be anything
- Eliminate what's working
---
**-- Application crashes --**
Application stops working
- May provide an error message
- May be disappear

Check the Event Log
- Often includes useful reconnaissance

Check the Reliability Monitor
- A history of application problems
- Checks for resolutions

Reinstall the application
- Contact application support
---
**-- Grinding noises --**
Computers should hum
- Not grind

Rattling
- Loose components

Scraping
- Hard drive issues

Clicking
- Fan problems

Pop
- Blown capacitor
---
**-- Lockups --**
System completely stops
- Completely. Usually not much in the event log
- Similar to unexpected shutdowns

Check for any activity
- Hard drive, status lights, try Ctrl-Alt-Del

Update drivers and software patches
- Has this been done recently?

Low resources
- RAM, storage

Hardware diagnostics may be helpful

---
**-- Continuous reboots --**
How far does the boot go before rebooting?
- BIOS only? OS splash screen?

Bad driver or configuration
- F8, "Boot from last known working configuration"

Try F8, Safe Mode
- If system starts, disable automatic restarts in System Properties

Bad hardware
- Try removing or replacing devices
---
**-- Inaccurate system date/time --**
Bad motherboard battery
- Often a "button" style battery

A bad battery will require a BIOS configuration or date/time configuration on every boot

On older systems, can reset the BIOS configuration by removing the battery
- Newer computers use a jumper