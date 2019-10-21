# pack{d}

[`vagrant`](https://www.vagrantup.com/docs/installation/) [`packer`](http://packer.io/intro/getting-started/install.html) machine image builder.

The `packer` `virtualbox` builder extends the official `ubuntu/bionic64` image with [`docker`](https://docs.docker.com/install/) and [`docker-compose`](https://docs.docker.com/compose/install/) using the [`ansible` provisioner](http://packer.io/docs/provisioners/ansible.html).

Artifacts are tagged `lazybit/bionic64-docker` and released to Vagrant Cloud using a `{{ date }}.<major>.<minor>` version scheme.
