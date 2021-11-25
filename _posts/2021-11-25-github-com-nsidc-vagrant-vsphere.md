---
title: vagrant-vsphere
categories: ['ruby']
---
## [vagrant-vsphere](https://github.com/nsidc/vagrant-vsphere)

### VMware vSphere provider for Vagrant


This is a [Vagrant](http://www.vagrantup.com) 1.6.4+ plugin that adds a
[vSphere](http://pubs.vmware.com/vsphere-50/index.jsp?topic=%2Fcom.vmware.wssdk.apiref.doc_50%2Fright-pane.html)
provider to Vagrant, allowing Vagrant to control and provision machines using
VMware. New machines are created from virtual machines or templates which must
be configured prior to using this provider.

This provider is built on top of the
[RbVmomi](https://github.com/vmware/rbvmomi) Ruby interface to the vSphere API.
