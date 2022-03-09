1. Install Virtual Box from https://www.virtualbox.org/wiki/Downloads
1. Install Vagrant from https://www.vagrantup.com/downloads
2. Install Ansible on Windows 10:
(Credit: https://geekflare.com/ansible-installation-windows/)
  i.    Install Ubuntu from Microsoft Store
  ii.   Enable "Windows SubSystem for Linux" from "Turn Windows features on or off"
  iii.  Login to ubuntu bash
  iv.   
        sudo apt-get update 
        sudo apt-get install software-properties-common 
        sudo apt-add-repository ppa:ansible/ansible 
        sudo apt-get update 
        sudo apt-get install ansible
        
        The following NEW packages will be installed: 
          ansible 
          ansible-core 
          python3-bcrypt 
          python3-jmespath 
          python3-kerberos 
          python3-ntlm-auth 
          python3-packaging 
          python3-paramiko 
          python3-pyparsing 
          python3-requests-kerberos 
          python3-requests-ntlm 
          python3-resolvelib 
          python3-winrm 
          python3-xmltodict
          
          shafiur@ShafiurRahman:~$ ansible --version                                                                                                                                                               ansible [core 2.12.2]                                                                                                                                                             config file = /etc/ansible/ansible.cfg                                                                                                                                           configured module search path = ['/home/shafiur/.ansible/plugins/modules', '/usr/share/ansible/plugins/modules']                                                                 ansible python module location = /usr/lib/python3/dist-packages/ansible                                                                                                           ansible collection location = /home/shafiur/.ansible/collections:/usr/share/ansible/collections                                                                                   executable location = /usr/bin/ansible                                                                                                                                           python version = 3.8.10 (default, Nov 26 2021, 20:14:08) [GCC 9.3.0]                                                                                                             jinja version = 2.10.1                                                                                                                                                           libyaml = True                 
