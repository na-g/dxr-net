# README
This is a Vagrant setup which creates a network of VMs for DXR indexing the webrtc.org codebase, private mozilla branches, and perhaps chromium in the future.

**Warning** this setup is not yet functional ... in other words don't use it.

# Requirements
* VirtualBox 5.1.22 (tested version) - VM provider
* Vagrant 1.9.5 (tested version) - VM management
* Ansible 2.2+ - VM provisioning and control

# Bringing up the environment
Within the vagrant folder run: `vagrant up`.
