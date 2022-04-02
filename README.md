# pihole-jailbreak
This repository is intended to provide DNS lists from the domains which consoles should not be allowded to resolve after they have been Jailbroken in order to provide account/console bans.

## Available lists
**[RECOMMENDED]** All playstation: https://raw.githubusercontent.com/itsCodeAlchemist/pihole-jailbreak/main/playstation
**[RECOMMENDED]** All nintendo: SOON

* Only playstation.net: https://raw.githubusercontent.com/itsCodeAlchemist/pihole-jailbreak/main/domains/playstation/playstation-net
* Only playstation.com: https://raw.githubusercontent.com/itsCodeAlchemist/pihole-jailbreak/main/domains/playstation/playstation-com

## Credits
* **Pi-Hole team and contribuitors** - For the amazing DNS tool.
* **Al-Azif** - For his incredible work with the dns-config-watchdog.
* **All of the guys on the consoles scene!**

## How this DNS lists are intended to use ?
On your Pi-Hole server, lock your Jailbroken console to a specific list
1. **Goto** Group Management > Groups;
2. **Create** a specific group for Jailbroken devices;
![Group Management_Groups](https://user-images.githubusercontent.com/102748012/161399371-ef907416-abe1-40a2-9297-c2470c6a790e.png)
3. **Goto** Group Management > Clients;
4. **Add** the corresponded MAC address from your Jailbroken device to the list
![Group Management_Clients_Create](https://user-images.githubusercontent.com/102748012/161399382-67f9919c-d2a2-429d-b339-697b946032d1.png)
5. **Link** your Jailbroken devices to the group which you have created;
![Group Management_Clients_List](https://user-images.githubusercontent.com/102748012/161399409-bf7a6a37-c198-48de-bbb3-0a277ee6baa2.png)
5. **Goto** Group Management > Adlists;
6. **Add** the desired lists available on this repository;
![Group Management_Adlists](https://user-images.githubusercontent.com/102748012/161399969-86ba87b7-51b4-4073-badf-de61eb607426.png)
7. At last **link** the new list on your Pi-Hole to your Jailbroken devices group.
![Group Management_Adlists_Group](https://user-images.githubusercontent.com/102748012/161400015-143f6ab9-74b8-4dc6-bc41-fabf71163c9f.png)
