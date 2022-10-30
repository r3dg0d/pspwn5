# pspwn5
A repo dedicated to reverse engineering the PS5 and creating a CFW to run modified homebrew apps.

# UPDATE: PS5 JAILBROKEN!
https://www.engadget.com/ps5-jailbreak-pt-firmware-155201757.html


⚠️NOTICE⚠️

I will be purchasing a jailbreakable PS5 when I have the money. Then I will begin working on an appstore for the PS5, as well as its own CFW. HMU if you are a coder and want to publish your application on it when its complete. 

Some projects that are PS5 Related:
PS5-VPN
FREESTORE
HOMEBREW STORE
DEEPBLUE-CFW (PS5 CUSTOM FIRMWARE)
PS5UIKIT
PS5CONTROLKIT
TWITTERPS5
CHROMIUMPS5
VMPS5
EMULATOR5
PS5-VOICE-SEARCH
Gamehacks
Free-iAP-Purchases

⚗️The Majority of development will be sifting through official firmware code and understanding it, even printing out the code on paper and reading it. The other half will be Coding a new CFW .PUP Update file for the PS5, as well as changing the recovery via keyboard and F12 / DEL on boot.

Basically, completely reverse-engineering the PS5 into a beast Gaming PC.
Yeah... it's gonna be a long project.

# Resources:
FreeBSD 13.0 SMAP Bypass (Not Tested on PS5 FW): https://hackerone.com/reports/1048322, https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2021-29628
cturt PS4 walkthrough: https://cturt.github.io/ps4-2.html


# Programs for messing with webpages / proxies:
https://github.com/Crypt0s/FakeDns


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
