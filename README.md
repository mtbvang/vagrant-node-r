# vagrant-node-r

A docker image that adds Vagrant access and R (v3.2.1) statistical computing tool, and littler to the official node debian jessie image.

There are two vagrant users vagrant and docker with uid's of 1001 and 1000 respectively. For file permissions on the host to be in sync the vagrant user needs to have the same uid as the host user.