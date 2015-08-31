[![Build Status](https://travis-ci.org/zalando/patroni.svg?branch=master)](https://travis-ci.org/zalando/patroni)
[![Coverage Status](https://coveralls.io/repos/zalando/patroni/badge.svg?branch=master)](https://coveralls.io/r/zalando/patroni?branch=master)
# Patroni: A Template for PostgreSQL HA with ZooKeeper or etcd

*There are many ways to run high availability with PostgreSQL; here we present a template for you to create your own custom fit high availability solution using python and distributed configuration store (like ZooKeeper, etcd or Consul) for maximum accessibility.*

## Getting Started
Use the documentation in the docs directory of this repository, or read using [Patroni at readthedocs.org](http://patroni.readthedocs.org)

## Notice

There are many different ways to do HA with PostgreSQL, see [the
PostgreSQL documentation](https://wiki.postgresql.org/wiki/Replication,_Clustering,_and_Connection_Pooling) for a complete list.

We call this project a "template" because it is far from a one-size fits
all, or a plug-and-play replication system.  It will have it's own
caveats.  Use wisely.
