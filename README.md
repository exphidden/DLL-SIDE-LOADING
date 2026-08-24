Bluestacks 5 Sideload Method (All Emulators)

This method lets you sideload your build into Bluestacks 5 using an XInput DLL hijack. It features zero ADB usage and is completely ADB-less.

How to Install and Build

Build and Rename
Build your source code in your VS.
Find the compiled output file.
Rename that output file to Xinput1_4.dll.

This DLL works even with Core Isolation Enable !!

Take Ownership of System32 File
Open Command Prompt (CMD) as an Administrator. Run these two commands to unlock the original Windows file:

takeown /f C:\Windows\System32\Xinput1_4.dll
icacls C:\Windows\System32\Xinput1_4.dll /grant Administrators:F

Replace the DLL
Go to C:\Windows\System32.
Paste your new Xinput1_4.dll into that folder to replace the old one.

Maintenance
Update the offsets.hpp file after every official game patch update.

Credits
Discord ID: @Exp!"
