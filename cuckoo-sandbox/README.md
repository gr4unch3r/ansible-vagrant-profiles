# Ansible Vagrant profile for Cuckoo Sandbox

This Vagrant profile installs [Cuckoo Sandbox](https://cuckoosandbox.org/) using the [Ansible](https://www.ansible.com/) provisioner. 

## Requirements

- [VirtualBox](https://www.virtualbox.org/wiki/Downloads)
- [Vagrant](https://www.vagrantup.com/downloads.html)
- [Ansible](http://docs.ansible.com/ansible/latest/intro_installation.html)
- [pywinrm](https://github.com/diyan/pywinrm)

## Getting Started

```
$ git clone https://github.com/gr4unch3r/ansible-vagrant-profiles.git
$ cd ansible-vagrant-profiles/cuckoo-sandbox
$ vagrant up
```

- Cuckoo web interface: http://192.168.56.100:8080
- Username/password: `vagrant:vagrant`

## Author Information

gr4unch3r [at] protonmail [dot] com
