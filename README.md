# myi3-setup
Configure my Laptop

## How to run it
#### Install Pre-reqs

- enable rpm fusion libraries for fedora
- enable AUR libraries for Manjaro
```
$ sudo pacman -S ansible i3        (for Arch Linux)
$ sudo dnf install ansible         (for Fedora, i3 will be installed during ansible run)
```
(for Ubuntu refer docs/ubuntu-specific.md)

#### Clone my repo and run ansible
```
$ git clone https://github.com/roystonanillobo/myi3
$ cd myi3
$ ansible-playbook -i ansible.cfg setup.yaml                 (edit the username in setup.yaml before running)
```
