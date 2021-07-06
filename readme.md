# Awesome Distributed System Projects

This repository contains list of distributed system projects with open source code in various programming languages which may be review in order to better understand how to distributed services.

## Databases

- (Golang) [Jocko - Kafka/distributed commit log service in Go. [Serf + Raft]](https://github.com/travisjeffery/jocko)
- (Golang) [oklog - distributed and coordination-free log management system for big ol' clusters [Archived]](https://github.com/oklog/oklog)
- (Golang) [Kingbus - a distributed MySQL binlog store based on raft [Raft]](https://github.com/flike/kingbus)
- (Golang) [elasticell - a distributed HA Redis-compatible NoSQL database with strong consistency and reliability](https://github.com/deepfabric/elasticell)
- (Golang) [RQLite - lightweight, distributed relational database, which uses SQLite as its storage engine](https://github.com/rqlite/rqlite)
- (Golang) [CockroachDB - distributed fault-tolerant SQL database built on a transactional and strongly-consistent key-value store](https://github.com/cockroachdb/cockroach)
- (Erlang) [CouchDB - highly available, partition tolerant, eventually consistent document database ](https://github.com/apache/couchdb). Supports master-master setups with automatic conflict detection.
- (C++) [MongoDB - a document database designed for ease of development and scaling](https://github.com/mongodb/mongo)

## Locking

- [(Golang) etcd - distributed reliable key-value store for the most critical data of a distributed system [Raft + gRPC]](https://github.com/etcd-io/etcd)
- [(Java) Apache Zookeeper - highly reliable distributed coordination](https://github.com/apache/zookeeper)

## Streaming

- [(Python) faust - a distributed stream processing library that ports the ideas from Kafka Streams to Python](https://github.com/robinhood/faust)
- [(Golang) Liftbridge - lightweight, fault-tolerant message streams by implementing a durable stream augmentation for the NATS messaging system](https://github.com/liftbridge-io/liftbridge)

## Schedulers

- [(Golang) dkron - distributed, fault tolerant job scheduling system for cloud native environments](https://github.com/distribworks/dkron)

## Queues

- [(Golang) nsq - realtime fault tolerant distributed messaging platform designed to operate at scale, handling billions of messages per day [Raft + gRPC]](https://github.com/nsqio/nsq)
- [(Golang) Sandglass - distributed, horizontally scalable, persistent, time ordered message queue](https://github.com/sandglass/sandglass)
- [(Golang) dnpipes - distributed version of Unix named pipes comparable to AWS SQS](https://github.com/mhausenblas/dnpipes)
- [(PHP) GatewayWorker - distributed realtime messaging framework based on workerman](https://github.com/walkor/GatewayWorker)

## File Systems

- (Golang) [JuiceFS - Hadoop-compatible AWS S3-compatible high-performance POSIX file system](https://github.com/juicedata/juicefs)
- (Golang) [SeaweedFS - a simple Hadoop-compatible AWS S3-compatible distributed highly scalable distributed file system](https://github.com/chrislusf/seaweedfs)
- (C) [GlusterFS - distributed storage that can scale to several petabytes](https://github.com/gluster/glusterfs)
- (C++) [GlusterFS - highly reliable, scalable and efficient distributed file system](https://github.com/lizardfs/lizardfs). It spreads data over a number of physical servers, making it visible to an end user as a single file system.

## Service Discovery

- (Golang) [sleuth - master-less peer-to-peer autodiscovery and RPC between HTTP services that reside on the same network](https://github.com/ursiform/sleuth)

## OS

- (C)[HarveyOS - distributed operating system](https://github.com/Harvey-OS/harvey)
 
## Frameworks

- [(Golang) etcd - framework for distributed systems development](https://github.com/asim/go-micro). Provides the core requirements for distributed systems development including RPC and Event driven communication
- [(Golang) ergo - port of Erlang/OTP approaches in Golang](https://github.com/halturin/ergo)
- [(Golang) gosiris - an actor framework for Golang](https://github.com/teivah/gosiris)
- [(Python) cotyledon - a framework for defining long-running services](https://github.com/sileht/cotyledon). It provides handling of Unix signals, spawning of workers, supervision of children processes, daemon reloading, sd-notify, rate limiting for worker spawning, and more.
- [(Java) atomix - fully featured framework for building fault-tolerant distributed systems [REST + Raft]](https://github.com/atomix/atomix)
- [(Kotlin) orbit - virtual actor framework for building distributed systems](https://github.com/orbit/orbit)
- [(JS) hemera - A Node.js microservices toolkit for the NATS messaging system [RPC]](https://github.com/hemerajs/hemera)

## Components

- [(Golang) Dragonboat - a high performance multi-group Raft consensus library in pure Go](https://github.com/lni/dragonboat)
- [(Golang) Golimit - Uber ringpop based distributed and decentralized rate limiter](https://github.com/myntra/golimit)
- [(Python) Tenacity - general-purpose retrying library](https://github.com/jd/tenacity)
- [(Elixir) ex_hash_ring - pure Elixir consistent hash ring implementation based on the excellent C hash-ring lib](https://github.com/discord/ex_hash_ring)

## Other Resources

- [awesome-scalability - Reading list for illustrating the patterns of scalable, reliable, and performant large-scale systems](https://github.com/binhnguyennus/awesome-scalability)