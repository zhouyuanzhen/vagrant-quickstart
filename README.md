# Vagrant Environment QuickStart

This is a vagrant environment quickstart project (which help you to quickstart your environment with Vagrant).

## Before we start

### Install the Virtualizer

You can choose below VM for your environment

#### VirtualBox (Recommended)

**VirtualBox is a free and opensource virtualizer for x86 hardware.**

- Goto https://www.virtualbox.org/wiki/Downloads to download the right package of your OS.
- Install with it by double click ;)

#### VMware

**Please notice that both VMware Fusion and the Vagrant vmware_desktop are not free, you need get the licenses for them if you wanna to use Vagrant with VMware!**

## Example

### Go to the space you like

```shell
cd centos7
# OR
cd centos8
```

### Play with Vagrant

```shell
# (启动虚机 / Run-up the VM box)
vagrant up

# (连接虚机 / Login to the VM -- SSH)
vagrant ssh

# (停止虚机 / Halt and Stop the VM)
vagrant halt

# (销毁虚机 / Terminate and destroy the VM )
vagrant destroy -f
```
