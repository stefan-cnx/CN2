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
   => you may get a message informing that 
      this application can not be upgraded as the lastest version is installed
   sudo systemctl status ssh  
   => inspect the status of the OpenSSH server  
      you may need to enable and start this service  
   sudo systemctl enable ssh  
   sudo systemctl start ssh  
   sudo systemctl status ssh  
   => inspect the status of the OpenSSH server (again) to see if it is (still) running    
3. Open your Windows 'Command Prompt' ('Windows' + 'R' => Enter 'cmd' and click 'OK')
4. Start a SSH session by entering 'ssh' + space + your servers username + '@' + the servers IP address
   
