## Overview

## Security

This provisioner does not secure jenkins itself. There are a few ways of doing that: you can allow jenkins to handle the user management or you can put jenkins behind a proxy server like apache.

[Jenkins Security Setup](https://wiki.jenkins-ci.org/display/JENKINS/Standard+Security+Setup)

## Requirements

* an ubuntu 14.04 vps with private/public key root access enabled
* a host with the ability to run Ansible
* Ansible version xx.x

## Provisioning

### Get the VPS

### Get the Code

### Modify the Variables

#### Passwords

### Run the Provisioner

    $ anisible-playbook -i hosts/servers.hosts provision.yml

## Contributing
