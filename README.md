# Vagrant Environment QuickStart

![GitHub stars](https://img.shields.io/github/stars/zhouyuanzhen/vagrant-quickstart.svg?style=flat&label=Star) ![GitHub stars](https://img.shields.io/github/forks/zhouyuanzhen/vagrant-quickstart.svg?style=flat&label=Fork) ![GitHub stars](https://img.shields.io/github/watchers/zhouyuanzhen/vagrant-quickstart.svg?style=flat&label=Watch) [![](https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat)](https://github.com/zhouyuanzhen/vagrant-quickstart/pulls)

This is a vagrant environment quickstart project (which help you to quickstart your environment with Vagrant).

----

- [x] `alpine3`: Alpine Linux 3 Vagrant Env
- [x] `centos7`: CentOS 7.7 Vagrant Env
- [x] `centos8`: CentOS 8.0 Vagrant Env
- [x] `centos7-docker`: CentOS 7.7 Docker Env

----

## Before you start

### Install the Virtualizer

***You can choose below VM for your environment***

- VirtualBox (Recommended): **VirtualBox is a free and opensource virtualizer for x86 hardware.**
  - Goto https://www.virtualbox.org/wiki/Downloads to download the right package of your OS.
  - Install with it by double click ;)

- VMware Fusion: **Please notice that both VMware Fusion and the Vagrant vmware_desktop are not free, you need get the licenses for them if you wanna to use Vagrant with VMware!**

----

## Example for QuickStart

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

## **My Pre-built Vagrant Box**:

### Get the vagrant box from Vagrant Cloud

- https://app.vagrantup.com/zyz/boxes/centos7
- https://app.vagrantup.com/zyz/boxes/centos7-docker
- https://app.vagrantup.com/zyz/boxes/centos7-python
- https://app.vagrantup.com/zyz/boxes/centos8

### Offline Vagrant boxes 百度网盘

#### Download the boxes

- [https://pan.baidu.com/s/1QReMyocRPPAqfrHd-cxLiA](https://pan.baidu.com/s/1QReMyocRPPAqfrHd-cxLiA)

#### QuickStart

```shell
vagrant box add centos7.7_virtualbox_1.0.2.box --name zyz/centos7

vagrant box add centos8_virtualbox_1.0.0.box --name zyz/centos8
```
