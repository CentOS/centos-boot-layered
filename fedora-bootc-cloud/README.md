# fedora-bootc-cloud:eln

This container image [Containerfile](Containerfile) builds on top of the
[base Fedora ELN image](github.com/centos/centos-bootc) and adds cloud-init.  It
can be used in any virtualization/IaaS system that is
[supported by cloud-init](https://cloudinit.readthedocs.io/en/latest/reference/datasources.html)
such as [libvirt](https://blog.wikichoon.com/2020/09/virt-install-cloud-init.html),
AWS, etc.

- Pull spec: `quay.io/centos-bootc/fedora-bootc-cloud:eln`
- Download QCOW2: [Download](https://storage.googleapis.com/centos-bootc-dev/fedora-bootc-cloud.qcow2).

The qcow2 image was built using [osbuildbootc](https://github.com/cgwalters/osbuildbootc).