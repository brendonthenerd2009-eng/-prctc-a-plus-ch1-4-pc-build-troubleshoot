# Lab 1 — Troubleshooting Methodology

Ask the User:

Did you recently change any hardware?

Was the PC running slow or acting up before this?

Is the OS on an internal hard drive or SSD?

💡 Possible Causes:

Drive not connected or failed

BIOS boot order is wrong

Corrupted boot files

🧪 First Thing to Check:

Go into BIOS (press F2/DEL at startup).
See if the boot drive is listed.
If not → likely a hardware issue.
If yes → check that it’s first in boot order.

🛠️ What I Did to Fix It:

Reseated the drive’s power and data cables

Set correct boot device in BIOS

If still no boot, tried booting from USB and repaired boot files

## Reflection 
At first, I suspected a simple boot order issue or a loose cable. However, after checking BIOS and reseating the cables, it turned out the drive wasn’t detected at all, pointing to a possible drive failure. The fix involved confirming the drive had failed and replacing it.
