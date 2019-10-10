# myi3-setup
Configure my Laptop

## How to run it
```
$ sudo pacman -S ansible  (for Arch Linux, for Ubuntu refer docs/ubuntu-specific.md)
$ git clone https://github.com/justmeandopensource/myi3
$ cd myi3
$ ansible-playbook -i ansible.cfg setup.yaml
