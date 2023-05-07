---
title: vagrant-fsnotify
categories: ['ruby']
---
## [vagrant-fsnotify](https://github.com/adrienkohlbecker/vagrant-fsnotify)

### Forward filesystem change notifications to your Vagrant VM


In `Vagrantfile` synced folder configuration, add the `fsnotify: true`
option. For example, in order to enable `vagrant-fsnotify` for the the default
`/vagrant` shared folder, add the following:

```ruby
config.vm.synced_folder ".", "/vagrant", fsnotify: true
```

When the guest virtual machine is up, run the following:

```console
$ vagrant fsnotify
```

This starts the long running process that captures filesystem events on the host
and forwards them to the guest virtual machine.
