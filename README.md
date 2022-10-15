# pspwn5
A repo dedicated to reverse engineering the PS5 and creating a CFW to run modified homebrew apps.

# UPDATE: PS5 JAILBROKEN!
https://www.engadget.com/ps5-jailbreak-pt-firmware-155201757.html

# Resources:
FreeBSD 13.0 SMAP Bypass (Not Tested on PS5 FW): https://hackerone.com/reports/1048322 / https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2021-29628
cturt PS4 walkthrough: https://cturt.github.io/ps4-2.html

# Programs for messing with webpages / proxies:
Fiddler for web debugging: https://www.telerik.com/fiddler
Wireshark for Packet analysis (probably useless): https://www.wireshark.org/
Hosting a localhost webserver with XAMP: https://hostfocuz.com/host-website-locally/

# Programs for reverse-engineering files
- Blog Post from OccupyTheWeb: https://www.hackers-arise.com/post/reverse-engineering-malware-reversing-and-disassembly-tools

# To-Do
- Experiment in PS5 OFW (official firmware)
- Try to find some way to activate webkit (User guide, Help guide)
- MITM on your router to said URL, and change the url to a custom-crafted payload, which can interface with PS5 memory.
- If possible try to dump OFW source code, or find OFW Source code
- Try finding an RCE (Remote Code Execution)
- Figure out how to dump OFW source code or access filesystem
- Update files are pretty hard to reverse-engineer. Tried updating via USB, PS5 doesn't like it.
