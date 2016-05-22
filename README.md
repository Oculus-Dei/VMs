## Prerequisites

* Install [VirtualBox](https://www.virtualbox.org/wiki/Downloads)
* Install [Vagrant](https://www.vagrantup.com/downloads.html)

### Ansible

* Install [pip](https://pip.pypa.io/en/stable/installing/)

* Install Ansible

```
pip install ansible
```

## Setup VMs

```
vagrant up --provision
```

The default username and password are both _vagrant_.

### GUI

GUI takes so long to install. Will remove it in the next version. To start, run

```
startx
```

after logging in any of VM.