# openshift-vagrant


This project aims to provision a CentOS 7 with OKD all-in-one, using openshift-ansible with container storage, router, registry, metrics, logging and etc.</br>

You can change in environment varibles Vagrantfile file or use os environment varibles. It defaults to origin, v3.11 and 10.0.0.111 respectively.</br>

After vagrant up you'll be able to access your OpenShift instance at:https://okd.master1.10.0.0.111.nip.io:8443/ with admin:admin.</br>


### Dependency
 - Vagrant
 - vagrant-hostmanager plugin
 - VirtualBox

Tested only on MacOS.
