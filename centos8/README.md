# README

This is a QuickStart environment for CentOS 7.7 with Vagrant (baked by Yuanzhen Zhou and from the Minimal installation).

Free feel to start with it and enjoy it!

## QuickStart

```sh
# (Run up your Vagrant box)
vagrant up

## (Run up vagrant box with your provider)
vagrant up --provider=vmware_desktop
vagrant up --provider=virtualbox

# (SSH to the vagrant VM)
vagrant ssh

# (Halt and shutdown the VM)
vagrant halt

# (Destroy the VM)
vagrant destroy -f
```

## Upgrade

```sh
# (Remove old version vagrant box)
vagrant box remove zyz/centos7 --provider virtualbox --box-version 0.4.2
vagrant box remove zyz/centos7 --provider vmware_desktop --box-version 0.4.2
```

