# win10-ltsc-2021-privacy-gpo
 Privacy based group policy used on a clean install of Windows 10 LTSC 2021

# Description

 Lots of things are disabled for maximum privacy. No Microsoft account sign is allowed, telemetry set to security, no location script tracking, privacy settings locked down (camera, mic, tracking device, and notifications are set to user controlled), Windows Defender Antivirus is optionally disabled.
 
 See [changes.txt](changes.txt) for the full list of edited policies.

# Installation

 1.) If you want to have Microsoft Defender Antivirus shut off, turn off "Tamper Protection" in Windows Security settings before running the script or it will turn back on after installation.
 2.) Copy the "GroupPolicy" folder to "C:\Windows\System32" with administrative rights.
 3.) Run "gpupdate /force" and reboot to force the new policies.
