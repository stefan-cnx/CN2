Proxmox Virtual Environment Installation
========================================
NOTE: YOU ARE ALLOWED TO USE TODAY'S EXERCISE FOR A FUTURE SKILL DEMO
---------------------------------------------------------------------
Task: Install Proxmox as an OS - You are allowed to reuse today's work as part of the documention requireement a future skill demo.

Document all installation steps from USB/ISO image generation, all the way up to a running system that you are logged in. Completing this today will give you two attempts to collect the required screenshots for the skill demo, first attempt today and the second attempt at the skill demo.

Proxmox Installation Media
--------------------------
1. Take care to remember the password that you setup during installation. You will not be able to recover this password after installation.
2. Download the Proxmox Virtual Environment (Proxmox VE) ISO image from https://www.proxmox.com/en/downloads.
3. Create your bootable USB drive for the Proxmox VE ISO image with your preferred utility, e.g. rufus.
4. Connect a keyboard, mouse and monitor to your server.
5. Insert your bootlable USB drive into your server.
6. Boot from your USB drive (F12) and follow onscreen instructions for a default installation.
7. Edit https://github.com/stefan-cnx/CNx/blob/main/CNx-Lab-Static-IPv4-Addresses and claim a free IP address (You may need to ask Stefan for colaborator invite). Enter your name after your preferred IP address.
8. Find a unique hostname by creating a subdomain for cnx.ie. Note that moodle.cnx.ie and office.cnx.ie are already taken. Check other students entry to ensure that your choosen hostname is unique. Add your hostname to the GitHub file by typing it after your name.
9. Ensure that you followed this format: 10.10.10.95 - Stefan stefan.cnx.ie
10. Use your reserved IP address and hostname for the Proxmox VE installation.
11. After rebooting, you can login to the Proxmox terminal with UN: root and the password that you have set during installation.
