# Create the own openVPN server 

# How to Create SSH Keys with OpenSSH on Linux or macOS
 
 -> Generating public/private rsa key pair.
 
 https://www.digitalocean.com/docs/droplets/how-to/add-ssh-keys/
 
 https://www.digitalocean.com/docs/droplets/how-to/add-ssh-keys/create-with-openssh/
 
 $ ssh-keygen
 
 ------------------------------------------------------------------------------------------------------------------------ 
 
 -> public and private keys files are created in defaultly .ssh folder for linux (/home/<username>/.ssh/id_rsa) 
  
 -> Upload your public password (.pub) file in your account 
 
 https://www.digitalocean.com/docs/droplets/how-to/add-ssh-keys/
 
 https://www.digitalocean.com/docs/droplets/how-to/add-ssh-keys/to-account/
 
 ------------------------------------------------------------------------------------------------------------------------ 

 -> how to connect openSHH after the setup creation public and private keys on local machine with droplet ip with linux or MacOS
 
 https://www.digitalocean.com/docs/droplets/how-to/connect-with-ssh/openssh/
 
 https://www.digitalocean.com/community/tutorials/initial-server-setup-with-ubuntu-18-04
 
 $ ssh root@<your_server_ip>
 
 ------------------------------------------------------------------------------------------------------------------------ 
 
 -> how to setup firewall on the serves.
 
 https://www.digitalocean.com/docs/networking/firewalls/
 
 ------------------------------------------------------------------------------------------------------------------------ 
 
 -> Create openSSH vpn server
 
 https://www.digitalocean.com/community/tutorials/how-to-set-up-an-openvpn-server-on-ubuntu-18-04
 
 $ sudo apt update
 $ sudo apt install openvpn

- > Downland and configure EasyRSA for CA (certificate authority)
 
 
- > create the client user keys and cert. 
 
 https://www.digitalocean.com/community/tutorials/how-to-set-up-an-openvpn-server-on-ubuntu-18-04#step-3-%E2%80%94-creating-the-server-certificate,-key,-and-encryption-files
 
 
 ------------------------------------------------------------------------------------------------------------------------ 
 
 https://github.com/Nyr/openvpn-install
 
 https://www.youtube.com/watch?v=qM9twnOYocA
 
 $ wget https://git.io/vpn -O openvpn-install.sh && bash openvpn-install.sh

 
 
 
 
 



 
