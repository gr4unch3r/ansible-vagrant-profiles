# Ansible Vagrant Profiles

[![CI](https://github.com/gr4unch3r/ansible-vagrant-profiles/actions/workflows/ci.yml/badge.svg)](https://github.com/gr4unch3r/ansible-vagrant-profiles/actions/workflows/ci.yml)

This repo contains a collection of virtual machines for various use cases. The VMs are created via Vagrant and provisioned via Ansible, using roles I've published to [Ansible Galaxy](https://galaxy.ansible.com/gr4unch3r). For more info on each VM, `cd` into its sub-directory.

## Available VMs/Environments

- `malware-lab` - Malware analysis lab environment
- `cuckoo-sandbox` - Automated malware analysis sandbox
- `dotnet-dev` - Windows .NET developer box
- `kicksecure` - Secure operating system

## Requirements

- [VirtualBox](https://www.virtualbox.org/wiki/Downloads)
- [Vagrant](https://www.vagrantup.com/downloads.html)
- [Ansible](http://docs.ansible.com/ansible/latest/intro_installation.html)

## Quick-start

```
$ git clone https://github.com/gr4unch3r/ansible-vagrant-profiles.git
$ cd ansible-vagrant-profiles/<box-dir>
$ vagrant up
```

## License

MIT

## Author Information

gr4unch3r [at] protonmail [dot] com
