SSH and FTP Setup
=================

1. SSH
------
We will use SSH to access our server remotely without the need of the ProxMox VE WebUI.
1. Login to the bash terminal of the Ubuntu server on Proxmox VE WebUI.
2. Install OhenSSH Server by running these commands:
   sudo apt update
   sudo apt upgrade -y
   sudo apt install openssh-server
   sudo systemctl status ssh
   => inspect the status of the OpenSSH server
      you may need to enable and start this service
   sudo systemctl enable ssh
   sudo systemctl start ssh
