# VagrantBox with Mesos and Marathon
This is a simple example of how Mesos and Marathon work together.
The provision is done with Ansible and works with Docker.

To run this vagrant box, you must need to install the folowwing in your machine:

- Ansible
- Virtual Box
- Vagrant
- (If needed) VagrantVbguest


###### Some useful commands
The *Vagrantfile* have the structure to run 4 vagrant boxes. If you want to make all run together write:
`vagrant up`
This started all in one try.

`vagrant halt`, `vagrant provision` or `vagrant destroy` did the same as `vagrant up`. This affects all machines that are currently running.

If you want to start one of the machines just add the name of it at the end of the command `vagrant up node1` depending of the machine you want to run.
The name of the machines are `node` plus the number of the machine you want from 1 to 4.
You can add more machines if you want in the Vagrantfile.




