# Whonix ESXi
Whonix adaptation for VMware ESXi

VMware.mf - .ovf md5 hash deleted
OVF reformatted for VMware - IDE changed to SAS, DVD removed, etc.

How to:

1. Download Whonix
https://www.whonix.org/wiki/VirtualBox

2. Unzip .ova file (7Zip or OVFTool)

3. Open .mf file with Notepad, remove first line: SHA1 (Whonix-Workstation-13.0.0.1.1.ovf)= some md5 hash

3. Replace .ovf file

4. Import to ESXi/VCenter

