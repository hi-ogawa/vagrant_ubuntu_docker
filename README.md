### Procedures

First, run commands:

```
$ vagrant up
$ vagrant ssh
 $ docker -v
 Docker version 1.11.2, build b9f10c9
 $ docker-compose -v
 docker-compose version 1.7.0, build 0d7bf73
$ vagrant package --output ubuntu_docker.box
```

Then, upload `ubuntu_docker.box` from this page: https://atlas.hashicorp.com/boxes/new.

It's available here: https://atlas.hashicorp.com/hiogawa/boxes/ubuntu_docker/


### References

- [HashiCorp: Creating a New Vagrant Box](https://atlas.hashicorp.com/help/vagrant/boxes/create)
- [HashiCorp: `vagrant package`](https://www.vagrantup.com/docs/cli/package.html)
- [HashiCorp: ANSIBLE AND VAGRANT](https://www.vagrantup.com/docs/provisioning/ansible_intro.html)
- [scotch.io: How to Create a Vagrant Base Box from an Existing One](https://scotch.io/tutorials/how-to-create-a-vagrant-base-box-from-an-existing-one)
