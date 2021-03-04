# Baremetal Lab Setup

This repo is created to setup the baremetal lab for metal3.

## Ansible installation

`sudo pip3 install ansible`

## Running the playbook

`ansible-playbook ./setup.yaml -i ./hosts -u <user> --ask-become-pass`
