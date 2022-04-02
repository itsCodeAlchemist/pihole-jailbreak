# pihole-jailbreak
This repository is intended to provide DNS lists from the domains which consoles should not be allowded to resolve after they have been Jailbroken in order to provide account/console bans.

# How this DNS lists are intended to use ?
On your Pi-Hole server, lock your Jailbroken console to a specific list
1. Goto Group Management > Groups;
2. Create a specific group for Jailbroken devices;

3. Goto Group Management > Clients;
4. Associate your Jailbroken devices to the group which you have created;

5. Goto Group Management > Adlists;
6. Add the desired lists available on this repository;

7. At last associate the new list on your Pi-Hole to your Jailbroken devices group.

# Available lists
**[RECOMMENDED]** All playstation: https://github.com/itsCodeAlchemist/pihole-jailbreak/playstation
**[RECOMMENDED]** All nintendo: SOON

* Only playstation.net: https://github.com/itsCodeAlchemist/pihole-jailbreak/domains/playstation/playstation-net
* Only playstation.com: https://github.com/itsCodeAlchemist/pihole-jailbreak/domains/playstation/playstation-com

# Credits
* **Pi-Hole team and contribuitors** - For the amazing DNS tool.
* **Al-Azif** - For his incredible work with the dns-config-watchdog.
* **All of the guys on the consoles scene!**