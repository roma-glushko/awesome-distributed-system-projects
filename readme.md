<p align="center">
  <img loading="lazy" src="https://raw.githubusercontent.com/roma-glushko/awesome-distributed-system-projects/main/imgs/logo.png" width="500px" alt="awesome distributed systems">
</p>

# Awesome Distributed Systems

This repository contains list of distributed system projects with open source code in various programming languages which may be useful in order to better understand how to build distributed services.

## Databases

- (Golang) [Jocko - a Kafka/distributed commit log service in Go. [Serf + Raft]](https://github.com/travisjeffery/jocko)
- (Golang) [oklog - a distributed and coordination-free log management system for big ol' clusters [Archived]](https://github.com/oklog/oklog)
- (Golang) [elasticell - a distributed HA Redis-compatible NoSQL database with strong consistency and reliability](https://github.com/deepfabric/elasticell)
- (Erlang) [CouchDB - a highly available, partition tolerant, eventually consistent document database ](https://github.com/apache/couchdb). Supports master-master setups with automatic conflict detection.
- (Java) [Apache HBase - a Hadoop database, a distributed, scalable, big data store](https://github.com/apache/hbase). Useful when random, realtime read/write access to big data needed
- (Golang) [Tair - a high-performance and high-availability distributed fast-access memory (MDB)/persistent (LDB) storage service](https://github.com/alibaba/tair)
- (Golang) [immudb - an immutable database based on zero trust, Key/Value & SQL, tamperproof, data change history](https://github.com/codenotary/immudb)
- (Rust) [toydb - distributed SQL database in Rust, written as a learning project](https://github.com/erikgrinaker/toydb)
- (Rust) [DB3 Network - a decentralized firebase firestore alternative](https://github.com/dbpunk-labs/db3)
- (Python) [ZODB - an ACID transactional object-oriented database](https://github.com/zopefoundation/ZODB)

### Key-Value Databases

- (C) [memcached - a high performance multithreaded event-based key/value cache store intended to be used in a distributed system](https://github.com/memcached/memcached)
- (C) [redis - an in-memory database with various value types that persists on disk](https://github.com/redis/redis)
- (Rust) [TiKV - a distributed transactional key-value database, originally created to complement TiDB](https://github.com/tikv/tikv)
- (C++) [leveldb - a fast key-value storage library written at Google that provides an ordered mapping from string keys to string values](https://github.com/google/leveldb)
- (Golang) [goleveldb - a LevelDB implemented in Golang](https://github.com/syndtr/goleveldb)
- (Golang) [summitdb - an in-memory, NoSQL key/value database. It persists to disk, uses the Raft consensus algorithm, is ACID compliant, and built on a transactional and strongly-consistent model](https://github.com/tidwall/summitdb).It supports custom indexes, geospatial data, JSON documents, and user-defined JS scripting
- (Python) [pupdb - a simple file-based key-value database](https://github.com/tuxmonk/pupdb)
- (Python) [pickledb - an open source key-value store using Python's json module](https://github.com/patx/pickledb)
- (C++) [KeyDB - a faster drop-in multithreaded alternative to Redis](https://github.com/Snapchat/KeyDB)
- (C++) [Dragonfly - an in-memory data store fully compatible with Redis and Memcache and designed using modern algorithms](https://github.com/dragonflydb/dragonfly)
- (Golang) [BadgerDB - an embeddable, persistent and fast key-value (KV) database written in pure Go](https://github.com/dgraph-io/badger)
- (Golang) [BuntDB - a low-level, in-memory, key/value store in pure Go.](https://github.com/tidwall/buntdb) It persists to disk, is ACID compliant, and uses locking for multiple readers and a single writer. It supports custom indexes and geospatial data.
- (Rust) [ConstDB - a redis-like cache store that implements CRDTs and active-active replications.](https://github.com/tancehao/ConstDB)
- (Golang) [GhostDB - a distributed, in-memory, general purpose key-value data store that delivers microsecond performance at any scale](https://github.com/jakekgrog/GhostDB)
- (Dart) [Hive - a lightweight and blazing fast key-value database written in pure Dart. Inspired by Bitcask](https://github.com/hivedb/hive)
- (Golang) [rosedb - a fast, stable, and embedded NoSQL database based on bitcask, supports a variety of data structures such as string, list, hash, set, and sorted set](https://github.com/flower-corp/rosedb)
- (Rust) [PumpkinDB - an immutable Ordered Key-Value Database Engine](https://github.com/PumpkinDB/PumpkinDB)
- (Golang) [FlashDB - a simple, in-memory, key/value store in pure Go.](https://github.com/arriqaaq/flashdb) It persists to disk, is ACID compliant, and uses locking for multiple readers and a single writer. It supports redis like operations for data structures like SET, SORTED SET, HASH and STRING
- (PHP) [Lazer - a PHP flat file database based on JSON files](https://github.com/Lazer-Database/Lazer-Database)
- (Golang) [Scribble - a tiny JSON database in Golang](https://github.com/sdomino/scribble)
- (Golang) [FlyDB - a high-performance KV storage engine based on bitcask paper supports redis protocol and the corresponding data structure](https://github.com/qishenonly/flydb)
- (Rust) [Engula - a distributed key-value store, used as a cache, database, and storage engine](https://github.com/engula/engula)
- (Golang) [Dice - an extremely simple Golang-based in-memory KV store that speaks Redis dialect](https://github.com/DiceDB/dice)

### Relational, SQL, NewSQL Databases

- (Golang) [CockroachDB - a distributed fault-tolerant SQL database built on a transactional and strongly-consistent key-value store](https://github.com/cockroachdb/cockroach)
- (Golang) [YugabyteDB - a cloud native distributed SQL database for mission-critical applications](https://github.com/yugabyte/yugabyte-db)
- (Golang) [RQLite - a lightweight, distributed relational database, which uses SQLite as its storage engine](https://github.com/rqlite/rqlite)
- (Golang) [Kingbus - a distributed MySQL binlog store based on raft [Raft]](https://github.com/flike/kingbus)
- (C++) [YDB is an open-source Distributed SQL Database that combines high availability and scalability with strict consistency and ACID transactions](https://github.com/ydb-platform/ydb)
- (Golang) [RadonDB - an open source, Cloud-native MySQL database for unlimited scalability and performance](https://github.com/radondb/radon)

### NoSQL, Document Databases

- (C++) [MongoDB - document database designed for ease of development and scaling](https://github.com/mongodb/mongo)
- (Golang) [FerretDB - an proxy, converting the MongoDB 6.0+ wire protocol queries to SQL - using PostgreSQL as a database engine](https://github.com/FerretDB/FerretDB)
- (C#) [LiteDB - NoSQL Document Store in a single data file](https://github.com/mbdavid/LiteDB)
- (Python) [tinydb - a lightweight document oriented database written in pure Python](https://github.com/msiemens/tinydb)
- (PHP) [SleekDB - a simple flat file NoSQL like database implemented in PHP without any third-party dependencies that store data in plain JSON files](https://github.com/rakibtg/SleekDB)
- (Rust) [BonsaiDB - an ACID, transactional KV or document dev-friendly database with configurable delayed on-disk data storing](https://github.com/khonsulabs/bonsaidb)
- (Golang) [CloverDB - a lightweight document-oriented NoSQL database written in pure Golang](https://github.com/ostafen/clover)

### Graph Databases

- (Java) [neo4j - Graph Database](https://github.com/neo4j/neo4j)
- (Python) [edgedb - a graph-relational database](https://github.com/edgedb/edgedb)
- (C++) [nebula - a distributed, fast open-source graph database featuring horizontal scalability and high availability](https://github.com/vesoft-inc/nebula)
- (Golang) [EliasDB - a graph-based lightweight database](https://github.com/krotik/eliasdb)

### Time Series

- (Golang) [VictoriaMetrics - fast, cost-effective monitoring solution and time series database](https://github.com/VictoriaMetrics/VictoriaMetrics)
- (Golang) [influxdb - scalable datastore for metrics, events, and real-time analytics](https://github.com/influxdata/influxdb)
- (Java) [trino - fast distributed SQL query engine for big data analytics](https://github.com/trinodb/trino)
- (Java) [Apache Doris - an easy-to-use, high performance and unified analytics database](https://github.com/apache/doris)
- (Scala) [FiloDB - Distributed, Prometheus-compatible, real-time, in-memory, massively scalable, multi-schema time series / event / operational database](https://github.com/filodb/FiloDB)
- (Rust) [ceresdb - high-performance, distributed, schema-less, cloud native time-series database that can handle both time-series and analytics workloads](https://github.com/CeresDB/ceresdb)
- (Golang) [tstorage is a lightweight local on-disk storage engine for time-series data with a straightforward API](https://github.com/nakabonne/tstorage)
-  (Rust) [CnosDB is a high-performance, high-compression, and easy-to-use open-source distributed time-series database. Used in fields such as IoT, industrial internet, connected cars, and IT operations](https://github.com/cnosdb/cnosdb)
-  (Golang) [LinDB - a scalable, high performance, high availability distributed time series database](https://github.com/lindb/lindb)
-  (Scala) [FiloDB - a distributed, prometheus-compatible, real-time, in-memory, massively scalable, multi-schema time series / event / operational database](https://github.com/filodb/FiloDB)
-  (Rust) [CeresDB - a high-performance, distributed, cloud native time-series database](https://github.com/CeresDB/ceresdb)

### Column Databases

- (Java) [Apache Cassandra - a highly-scalable partitioned row store. Rows are organized into tables with a required primary key](https://github.com/apache/cassandra)
- (C++) [scylladb - a real-time big data database that is API-compatible with Apache Cassandra and Amazon DynamoDB](https://github.com/scylladb/scylladb)
- (Golang) [FrostDB - an embeddable wide-column columnar database written in Go](https://github.com/polarsignals/frostdb)

### Permission Databases

- (Golang) [SpiceDB - a Google Zanzibar-inspired, database system for creating and managing security-critical application permissions](https://github.com/authzed/spicedb)
- (Golang) [Keto - a Google Zanzibar-inspired open source database, gRPC, REST APIs, newSQL, and an easy and granular permission language. Supports ACL, RBAC](https://github.com/ory/keto)

### Analytical Databases

- (C++) [BaikalDB is a distributed HTAP MySQL-compatible database designed for petabytes scale](https://github.com/baidu/BaikalDB) 
- (Golang) [AresDB - a GPU-powered real-time analytics storage and query engine](https://github.com/uber/aresdb)

## Locking

- (Golang) [etcd - distributed reliable key-value store for the most critical data of a distributed system [Raft + gRPC]](https://github.com/etcd-io/etcd)
- (Java) [Apache Zookeeper - highly reliable distributed coordination](https://github.com/apache/zookeeper)
- (Golang) [chubby - A (very simplified) implementation of Chubby, Google's distributed lock service](https://github.com/sherrybai/chubby)

## Streaming

- (Java) [Kafka - a distributed, highly scalable, elastic, fault-tolerant, and secure event streaming platform](https://github.com/apache/kafka)
- (Python) [faust - a distributed stream processing library that ports the ideas from Kafka Streams to Python](https://github.com/robinhood/faust)
- (Golang) [Liftbridge - a lightweight, fault-tolerant message streams by implementing a durable stream augmentation for the NATS messaging system](https://github.com/liftbridge-io/liftbridge)
- (Rust) [RisingWave - a distributed SQL database for stream processing, designed to reduce the complexity and cost of building real-time applications](https://github.com/risingwavelabs/risingwave)

## Schedulers

- (Golang) [dkron - a distributed, fault tolerant job scheduling system for cloud native environments](https://github.com/distribworks/dkron)
- (Python) [Celery - a distributed task queue](https://github.com/celery/celery)
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
- (Rust) [Sonic - fast, lightweight & schema-less search backend. An alternative to Elasticsearch that runs on a few MBs of RAM](https://github.com/valeriansaliou/sonic)

## Vectors

- (Rust) [Qdrant - a vector similarity search engine and vector database](https://github.com/qdrant/qdrant)
- (Golang) [milvus - an open-source vector database built to power embedding similarity search and AI applications](https://github.com/milvus-io/milvus)
- (Golang) [Weaviate - an open source vector database that stores both objects and vectors](https://github.com/weaviate/weaviate)
- (Golang) [tobias-mayer/vector-db - a simple vector database that can be used to search for similar vectors in logarithmic time](https://github.com/tobias-mayer/vector-db)
- (Rust) [DANNY - a decentralized vector database for building vector search applications](https://github.com/firstbatchxyz/danny)

## File Systems

- (Golang) [JuiceFS - Hadoop-compatible AWS S3-compatible high-performance POSIX file system](https://github.com/juicedata/juicefs)
- (Golang) [SeaweedFS - a simple Hadoop-compatible AWS S3-compatible distributed highly scalable distributed file system](https://github.com/chrislusf/seaweedfs)
- (C) [GlusterFS - distributed storage that can scale to several petabytes](https://github.com/gluster/glusterfs)
- (C++) [GlusterFS - highly reliable, scalable and efficient distributed file system](https://github.com/lizardfs/lizardfs). It spreads data over a number of physical servers, making it visible to an end user as a single file system.

## Service Discovery

- (Golang) [sleuth - master-less peer-to-peer autodiscovery and RPC between HTTP services that reside on the same network](https://github.com/ursiform/sleuth)

## Data Processing

- (Scala) [Apache Spark - unified analytics engine for large-scale data processing](https://github.com/apache/spark)

## TerminusDB

- (Prolog) [terminusdb - distributed database with a collaboration model](https://github.com/terminusdb/terminusdb)

## OS

- (C) [HarveyOS - distributed operating system](https://github.com/Harvey-OS/harvey)
 
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
- (GoLang) [Service Weaver - A framework that allows to write applications as modular binary and deploy it as a set of microservices](https://github.com/ServiceWeaver/weaver)
- (GoLang) [Dapr - portable, serverless, event-driven runtime that works as a sidecar and makes it easy for developers to build resilient, stateless and stateful microservices](https://github.com/dapr/dapr)

## Components

- (Golang) [Dragonboat - a high performance multi-group Raft consensus library in pure Go](https://github.com/lni/dragonboat)
- (Golang) [Golimit - Uber ringpop based distributed and decentralized rate limiter](https://github.com/myntra/golimit)
- (Python) [Tenacity - general-purpose retrying library](https://github.com/jd/tenacity)
- (Elixir) [ex_hash_ring - pure Elixir consistent hash ring implementation based on the excellent C hash-ring lib](https://github.com/discord/ex_hash_ring)
- (Elixir) [raft - Raft consensus implementation](https://github.com/toniqsystems/raft)
- (C++) [NuRaft - Raft implementation derived from the cornerstone project](https://github.com/eBay/NuRaft)
- (Python) [Hyx - Lightweight fault tolerance primitives for your resilient and modern Python microservices](https://github.com/roma-glushko/hyx)
- (Python) [Migdalor - a Kubernetes native peer discovery for Python asyncio nodes](https://github.com/roma-glushko/migdalor)
- (Golang) [skiplist - a Golang implementation of the skiplist data structure](https://github.com/huandu/skiplist)
- (Java) [Waltz - a quorum-based distributed write-ahead log for replicating transactions](https://github.com/wepay/waltz)

## Other Resources

- [awesome-scalability - Reading list for illustrating the patterns of scalable, reliable, and performant large-scale systems](https://github.com/binhnguyennus/awesome-scalability)
- [awesome-distributed-systems - curated list on awesome material on distributed systems](https://github.com/theanalyst/awesome-distributed-systems)
- [awesome-database-learning - a list of learning materials to understand databases internals](https://github.com/pingcap/awesome-database-learning)
- (C/C++)(Book) [Build Your Own Redis with C/C++](https://build-your-own.org/redis/#table-of-contents)
- (C) (Article) [Writing a sqlite clone from scratch in C](https://cstack.github.io/db_tutorial/)
- [Berkley CS186: Intro into Database Systems](https://sites.google.com/site/cs186fall2013/homeworks)
- [MIT 6.830: Database Systems](https://ocw.mit.edu/courses/6-830-database-systems-fall-2010/pages/assignments/)
