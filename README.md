# WSL Development Ansible Playbook

This playbook installs and configures most of the software I use in WSL for software development. This repository is an ongoing effort, and will evolve over time.

## Installation

  1. [Install Ansible](https://docs.ansible.com/ansible/latest/installation_guide/index.html). It's recommended to install ansible using pip in a virtual environment.
  2. Clone this repository to your local drive.
  3. Run `$ ansible-galaxy install -r requirements.yml` inside this directory to install required Ansible roles.
  4. Run `$ ansible-playbook main.yml -i inventory --ask-become-pass` inside this directory. Enter your account password when prompted.

## Included applications and packages

Applications

  - [Vagrant](https://www.vagrantup.com/)

> Note: Vagrant will require Windows access to work as most Vagrant providers will need to be installed on Windows directly (access is enabled in the playbook). Vagrant installed in WSL must be the same version installed on Windows.

Packages

TODO
