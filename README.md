# packer-ubuntuserver26_04

Creating a virtual machine template under [Ubuntu Server 26.04 LTS](https://ubuntu.com/download/server) from ISO file with [Packer](https://developer.hashicorp.com/packer/) using [VMware Workstation](https://www.vmware.com/). 

This was created by Yoann LAMY under the terms of the [GNU General Public License v3](http://www.gnu.org/licenses/gpl.html).

### Usage

This virtual machine template must be builded using Packer.

- ``cd packer-ubuntuserver26_04``
- ``packer init vmware-iso-ubuntuserver26_04.pkr.hcl``
- ``packer build vmware-iso-ubuntuserver26_04.pkr.hcl``

This template creates an **ubuntu** user with the password **MotDePasse**.
