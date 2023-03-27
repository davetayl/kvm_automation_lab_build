# KVM Based Automation Lab
KVM based automation lab in Ansible format that includes Jenkins, Ansible
Docker and Netbox.

## The build basics
This lab is intended to be installed on a single Debian host acting as a KVM host.
A person should be able to build a basic debian host, then set some basic perameters
in teh inventory file and run an ansible build.

## To Do
- define kvm host config
    - Base kvm build
    - set up cloud image based builds with keys for ansible automation
- deploy and provision lab guests
    - Jenkins host
    - Docker host
    - Netbox host
