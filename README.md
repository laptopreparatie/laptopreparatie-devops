# DevOps repository for laptopreparatie.nl

The repository hosts tools used for management of development, staging and live
environments.

Initial stack of technologies
  - Vagrant + VirtualBox for development virtual machine
  - Ansible to manage development, staging and production machines

Future tech: Docker


## Requirements

You will need the following software in order to manage staging and production
machines.

  - Python 2.7. Probably shipped with your operating system.
  - [`pip`](https://pip.pypa.io/en/stable/installing/). Probably you already have it. 
  - [`virtualenv`](https://virtualenv.pypa.io/en/stable/installation/).
    Prevents pollution of your python installation by Ansible packages.

### Developer machine

You will need the following software if you run a development machine.

  - [VirtualBox](https://www.virtualbox.org/wiki/Downloads)
  - [Vagrant](https://www.vagrantup.com/downloads.html)


TODO: setup dev machine
