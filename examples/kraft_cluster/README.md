# KRaft-based 3-node Kafka Cluster

This folder contains an examle KFraft-based 3-node Kafka Cluster that can
be deployed using Vagrant.

To start the cluster and to re-configure it, whenever you have made any
changes to the underlying role(s) or the configuration, run:

## Prerequisites

- Vagrant
- libvirt

## Running the example

```sh
vagrant up --provision
```

To tear down the cluster, run:

```sh
vagrant destroy --force
```
