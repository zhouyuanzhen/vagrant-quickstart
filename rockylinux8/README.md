# README

This is a QuickStart environment for Rocky Linux 8.5 with Vagrant (baked by Yuanzhen Zhou and from the Minimal installation).

The image is around **500MB**.

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
vagrant box remove zyz/rockylinux --provider virtualbox --box-version 1.0.0
vagrant box remove zyz/rockylinux --provider vmware_desktop --box-version 1.0.0
```

