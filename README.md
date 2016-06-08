# ansible-ufw
Creating an uncomplicated firewall with ansible scripts

https://www.digitalocean.com/community/tutorials/how-to-setup-a-firewall-with-ufw-on-an-ubuntu-and-debian-cloud-server

## Usage: 

1. Edit inventory file to reporesent your target server. 
1. Make sure to edit the users in `group_vars/all` (these users will have ssh access to the target server)

**To run:**

```
ansible-playbook playbook.yml -i inventory
```
