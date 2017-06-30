# Ansible playbook for openvpn server
openvpn server and easy-rsa with ldap authentication plugin
## Prerequisites
* centos 7 (minimal) installed
* NAT on Firewall - both directions
* 1194 UDP open on Firewall - both directions

## Installing
```
git clone https://github.com/nielipin/ansible_openvpn_ldap
yum install ansible
```
Edit hosts and host_vars/openvpn with your values

ansible-playbook create-server.yml

