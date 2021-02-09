<snippet>
  <content>

## Ansible.Clavister.VPN

The scope of this project is to automate the process of creating 
<br>a site-to-site VPN configuration on a Clavister Netwall Firewall.
 

## Usage

The project is made of a main yml file , a vars file,inventory file and a Jinja2 template file.
<br>The Var file contains the credentials for the firewall(you should use a vault),
<br>and the VPN info needed to establish a session(PSK,local subnets,remote subnets, etc).  
<br>The Jinja2 template contains the CLI commands. The result of the template and var file
<br>is saved in "out" folder and then uploaded and executed on the firewall.
<br>The main file contains all the tasks. 

  
## Credits
This was written by Mihai Cziraki
</content>
</snippet>
