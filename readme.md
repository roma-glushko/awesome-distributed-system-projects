# Awesome Distributed System Projects

This repository contains list of distributed system projects with open source code in various programming languages which may be useful in order to better understand how to build distributed services.

## Databases

- (Golang) [Jocko - Kafka/distributed commit log service in Go. [Serf + Raft]](https://github.com/travisjeffery/jocko)
- (Golang) [oklog - distributed and coordination-free log management system for big ol' clusters [Archived]](https://github.com/oklog/oklog)
- (Golang) [Kingbus - a distributed MySQL binlog store based on raft [Raft]](https://github.com/flike/kingbus)
- (Golang) [elasticell - a distributed HA Redis-compatible NoSQL database with strong consistency and reliability](https://github.com/deepfabric/elasticell)
- (Golang) [RQLite - lightweight, distributed relational database, which uses SQLite as its storage engine](https://github.com/rqlite/rqlite)
- (Golang) [CockroachDB - distributed fault-tolerant SQL database built on a transactional and strongly-consistent key-value store](https://github.com/cockroachdb/cockroach)
- (Erlang) [CouchDB - highly available, partition tolerant, eventually consistent document database ](https://github.com/apache/couchdb). Supports master-master setups with automatic conflict detection.
- (C++) [MongoDB - document database designed for ease of development and scaling](https://github.com/mongodb/mongo)
- (Java) [Apache Cassandra - a highly-scalable partitioned row store. Rows are organized into tables with a required primary key](https://github.com/apache/cassandra)
- (Java) [Apache HBase - Hadoop database, a distributed, scalable, big data store](https://github.com/apache/hbase). Useful when random, realtime read/write access to big data needed
- (Golang) [tikv - distributed transactional key-value database, originally created to complement TiDB](https://github.com/tikv/tikv)
- (Golang) [Tair - high-performance and high-availability distributed fast-access memory (MDB)/persistent (LDB) storage service](https://github.com/alibaba/tair)
- (C) [memcached - high performance multithreaded event-based key/value cache store intended to be used in a distributed system](https://github.com/memcached/memcached)
## Locking

- (Golang) [etcd - distributed reliable key-value store for the most critical data of a distributed system [Raft + gRPC]](https://github.com/etcd-io/etcd)
- (Java) [Apache Zookeeper - highly reliable distributed coordination](https://github.com/apache/zookeeper)
- (Golang) [chubby - A (very simplified) implementation of Chubby, Google's distributed lock service](https://github.com/sherrybai/chubby)

## Streaming

- (Java) [Kafka - distributed, highly scalable, elastic, fault-tolerant, and secure event streaming platform](https://github.com/apache/kafka)
- (Python) [faust - a distributed stream processing library that ports the ideas from Kafka Streams to Python](https://github.com/robinhood/faust)
- (Golang) [Liftbridge - lightweight, fault-tolerant message streams by implementing a durable stream augmentation for the NATS messaging system](https://github.com/liftbridge-io/liftbridge)

## Schedulers

- (Golang) [dkron - distributed, fault tolerant job scheduling system for cloud native environments](https://github.com/distribworks/dkron)
- (Python) [Celery - distributed task queue](https://github.com/celery/celery)
- (Python) [Apache Airflow - a platform to programmatically author, schedule, and monitor workflows](https://github.com/apache/airflow)

## Queues

- (Golang) [nsq - realtime fault tolerant distributed messaging platform designed to operate at scale, handling billions of messages per day [Raft + gRPC]](https://github.com/nsqio/nsq)
- (Golang) [Sandglass - distributed, horizontally scalable, persistent, time ordered message queue](https://github.com/sandglass/sandglass)
- (Golang) [dnpipes - distributed version of Unix named pipes comparable to AWS SQS](https://github.com/mhausenblas/dnpipes)
- (PHP) [GatewayWorker - distributed realtime messaging framework based on workerman](https://github.com/walkor/GatewayWorker)
- (C++) [ZeroMQ - abstraction of asynchronous message queues, multiple messaging patterns, message filtering (subscriptions), seamless access to multiple transport protocols and more](https://github.com/zeromq/libzmq)
- (Java) [Apache Pulsar - distributed pub-sub messaging platform with a very flexible messaging model and an intuitive client API](https://github.com/apache/pulsar)
- (Java) [Apache ActiveMQ - high performance Apache 2.0 licensed Message Broker](https://github.com/apache/activemq)

## Search Engines

- (Java) [ElasticSearch - distributed, RESTful search and analytics engine](https://github.com/elastic/elasticsearch)
- (Java) [Apache Lucene -  a high-performance, full featured text search engine library](https://github.com/apache/lucene)
- (Rust) [MeiliSearch - Lightning Fast, Ultra Relevant, and Typo-Tolerant Search Engine](https://github.com/meilisearch/MeiliSearch)
- (JS) [FlexSearch - memory-flexible full-text search library](https://github.com/nextapps-de/flexsearch)
- (Golang) [RiotSearch - distributed, Simple and efficient full text search engine](https://github.com/go-ego/riot)
- (C++) [Typesense - fast, typo tolerant, fuzzy search engine](https://github.com/typesense/typesense)

## File Systems

- (Golang) [JuiceFS - Hadoop-compatible AWS S3-compatible high-performance POSIX file system](https://github.com/juicedata/juicefs)
- (Golang) [SeaweedFS - a simple Hadoop-compatible AWS S3-compatible distributed highly scalable distributed file system](https://github.com/chrislusf/seaweedfs)
- (C) [GlusterFS - distributed storage that can scale to several petabytes](https://github.com/gluster/glusterfs)
- (C++) [GlusterFS - highly reliable, scalable and efficient distributed file system](https://github.com/lizardfs/lizardfs). It spreads data over a number of physical servers, making it visible to an end user as a single file system.

## Service Discovery

- (Golang) [sleuth - master-less peer-to-peer autodiscovery and RPC between HTTP services that reside on the same network](https://github.com/ursiform/sleuth)

## Data Processing

- (Scala) [Apache Spark - unified analytics engine for large-scale data processing](https://github.com/ursiform/sleuth)

## OS

- (C)[HarveyOS - distributed operating system](https://github.com/Harvey-OS/harvey)
 
## Frameworks

- (Golang) [etcd - framework for distributed systems development](https://github.com/asim/go-micro). Provides the core requirements for distributed systems development including RPC and Event driven communication
- (Golang) [ergo - port of Erlang/OTP approaches in Golang](https://github.com/halturin/ergo)
- (Golang) [gosiris - an actor framework for Golang](https://github.com/teivah/gosiris)
- (Python) [cotyledon - a framework for defining long-running services](https://github.com/sileht/cotyledon). It provides handling of Unix signals, spawning of workers, supervision of children processes, daemon reloading, sd-notify, rate limiting for worker spawning, and more.
- (Java) [atomix - fully featured framework for building fault-tolerant distributed systems [REST + Raft]](https://github.com/atomix/atomix)
- (Kotlin) [ orbit - virtual actor framework for building distributed systems](https://github.com/orbit/orbit)
- (JS) [hemera - A Node.js microservices toolkit for the NATS messaging system [RPC]](https://github.com/hemerajs/hemera)
- (Python) [Tooz - centralizing the most common distributed primitives like group membership protocol, lock service and leader election by providing a coordination API helping developers to build distributed applications](https://github.com/openstack/tooz)
- (C++) [Nebula - powerful framework for building highly concurrent, distributed, and resilient message-driven applications](https://github.com/Bwar/Nebula)

## Components

- (Golang) [Dragonboat - a high performance multi-group Raft consensus library in pure Go](https://github.com/lni/dragonboat)
- (Golang) [Golimit - Uber ringpop based distributed and decentralized rate limiter](https://github.com/myntra/golimit)
- (Python) [Tenacity - general-purpose retrying library](https://github.com/jd/tenacity)
- (Elixir) [ex_hash_ring - pure Elixir consistent hash ring implementation based on the excellent C hash-ring lib](https://github.com/discord/ex_hash_ring)
- (Elixir) [raft - Raft consensus implementation](https://github.com/toniqsystems/raft)
- (C++) [NuRaft - Raft implementation derived from the cornerstone project](https://github.com/eBay/NuRaft)

## Other Resources

- [awesome-scalability - Reading list for illustrating the patterns of scalable, reliable, and performant large-scale systems](https://github.com/binhnguyennus/awesome-scalability)
- [awesome-distributed-systems - curated list on awesome material on distributed systems](https://github.com/theanalyst/awesome-distributed-systems)