# README

This is a QuickStart environment for Alpine Linux with Vagrant (baked by Yuanzhen Zhou and from the Minimal installation).

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
vagrant box remove zyz/alpine --provider virtualbox --box-version 0.9.x
vagrant box remove zyz/alpine --provider vmware_desktop --box-version 0.9.x
```

