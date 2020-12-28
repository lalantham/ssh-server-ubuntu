# Ubuntu Autoscript SSH/SSL

###### Using this Script you Can Create Your Own SSH Server.This Script Made for Debian Os.

### Service Port
  - SSH 		    : 22
  - Dropbear 		: 80
  - Stunnel 		: 443
  - Badvpn 		  : 7300
  - Squid 		  : 8080/3128
  
### Install Instruction
  - apt update && apt upgrade -y
  - wget https://raw.githubusercontent.com/lalantham/ssh-server-ubuntu/main/install.sh
  - chmod +x install.sh
  - ./install.sh
  - useradd {username}
  - passwd {username}
  - reboot
  
### Tested On
  - Ubuntu 18.04
