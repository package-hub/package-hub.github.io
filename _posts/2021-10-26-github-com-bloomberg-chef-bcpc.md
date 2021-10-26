---
title: chef-bcpc
categories: ['ruby', 'chef', 'openstack']
---
## [chef-bcpc](https://github.com/bloomberg/chef-bcpc)

### Bloomberg Clustered Private Cloud distribution


chef-bcpc is a set of [Chef](https://github.com/opscode/chef) cookbooks that
build a highly-available [OpenStack](http://www.openstack.org/) cloud.

The cloud consists of head nodes (OpenStack controller services, Ceph Mons,
etc.) and work nodes (hypervisors).

Each head node runs all of the core services in a highly-available manner. Each
work node runs the relevant services (nova-compute, Ceph OSDs, etc.).

