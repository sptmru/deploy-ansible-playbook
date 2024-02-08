# Web Deploy Ansible Playbook

## Description

This is an [Ansible](https://www.ansible.com/) playbook for automatic installation of various stuff I use for web apps deployment.

## Stuff you can install with it

- Docker
- NVM
- Node.js
- Nginx
- Certbot

## Usage

- install Ansible (`brew install ansible` on macOS, `apt install ansible` on Ubuntu. Please check docs if you're using Windows — or just install Ansible into WSL)
- update variables in `playbook.yaml` if you need it
- add the IP addresses of your servers to `inventory.yaml`
- install Ansible "community.general" collection: `ansible-galaxy collection install community.general`
- run playbook this way: `ansible-playbook playbook.yaml -i inventory.yaml`

## Contact

In case of any questions, feel free to contact me by email: [soslanaldatov@gmail.com](mailto:soslanaldatov@gmail.com).
Also, feel free to contribute.
