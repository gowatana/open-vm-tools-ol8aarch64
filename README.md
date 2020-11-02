# open-vm-tools for Oracle Linux 8 (ARM)

## Introduction

* This is an unofficial build for Home Lab.
* Install to the Guest OS on [ESXi Arm Edition](https://flings.vmware.com/esxi-arm-edition).
* Download the disk image here: [Oracle Linux for ARM](https://www.oracle.com/linux/downloads/linux-arm-downloads.html)

## To install

get yum .repo file.

```
# curl -o /etc/yum.repos.d/open-vm-tools-ol8.repo https://gowatana.github.io/open-vm-tools-ol8aarch64/open-vm-tools-ol8.repo
```

install.

```
# dnf install -y open-vm-tools
# systemctl start vmtoolsd
```
