# Storage Server Setup with Ansible

This repository contains Ansible playbooks and configuration files to automate the setup of storage server.

## Usage

To set up the storage server, run the following command

```sh
ansible-playbook main.yml --ask-become-pass
```

This command will execute the main.yml playbook, prompting you for your sudo password

## TODO

- [ ] Create bond network interface
