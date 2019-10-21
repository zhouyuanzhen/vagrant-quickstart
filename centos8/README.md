# README

This is a QuickStart environment for CentOS 8.0.1905 with Vagrant (baked by Yuanzhen Zhou and from the Minimal installation).

The image is less than **500MB** (Around 400MB for VMware desktop image and 450MB for VirtualBox image).

Free feel to start with it and enjoy it!

## QuickStart

```sh
## Run up your Vagrant box with default provider
vagrant up

## Run up vagrant box with your provider in case you have multi provider envs like me, I am rich :)
vagrant up --provider=vmware_desktop
vagrant up --provider=virtualbox

## SSH to the vagrant VM
vagrant ssh

## (Halt and shutdown the VM)
vagrant halt

## (Destroy the VM)
vagrant destroy -f
```

## Upgrade

```sh
# (Remove old version vagrant box)
vagrant box remove zyz/centos7 --provider virtualbox --box-version 1.0.0
vagrant box remove zyz/centos7 --provider vmware_desktop --box-version 1.0.0
```

