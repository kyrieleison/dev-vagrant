# dev-vagrant

```
$ vagrant box add nrel/CentOS-6.5-x86_64 https://vagrantcloud.com/nrel/CentOS-6.5-x86_64/version/4/provider/virtualbox.box
$ vagrant plugin install vagrant-hostsupdater
$ vagrant ssh-config --host dev >> ~/.ssh/config
$ vagrant up
$ vagrant provision
```
