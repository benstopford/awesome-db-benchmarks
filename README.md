## Curated list of database (NoSQL, Hadoop, Relational) benchmarks and performance comparisons:
(please annotate and submit a pull request if you have others)

| Databases | Link | Type | Independent | Date |
| -------------     | ------ | ---------:| -----------:| ---- |
|SequoiaDB, Cassandra, MongoDB|[NoSQL Performance Test](http://www.msrg.org/publications/pdf_files/2014/NoSQLBenchmark-NoSQL_Performance_Test_-_In-Me.pdf)|YCSB|Y|2014|
|Redshift, Hive, Shark, Imapala, Tez|[Big Data Benchmark](https://amplab.cs.berkeley.edu/benchmark/)|BDB|Y|2014|
|LevelDB, RocksDB, HyperLevelDB, LMDB, InfluxDB|[Benchmarking LevelDB vs. RocksDB vs. HyperLevelDB vs. LMDB Performance for InfluxDB](http://influxdb.com/blog/2014/06/20/leveldb_vs_rocksdb_vs_hyperleveldb_vs_lmdb_performance.html)|YCSB|N|2014|
|Multiple Relational/Hadoop|[TPC industry benchmarks for OLTP, Analytics & Big Data](http://www.tpc.org/)|TPC|Y|Ongoing|
|Cassandra, HBase, MongoDB, OrientDB, Redis|[Which NoSQL Database? A Performance Overview](http://www.ronpub.com/publications/OJDB-v1i2n02_Abramova.pdf)|YCSB|Y|2014|
|MongoDB, ElasticSearch, Redis, OrientDB|[Performance Evaluation of NoSQL Systems Using YCSB in a resource Austere Environment](http://research.ijais.org/volume7/number8/ijais14-451229.pdf)|YCSB|Y|2014|
|LevelDB,SQLite,Keyoto,OpenLdap, BDB|[Sysmas DB Benchmarks](http://symas.com/mdb/microbench/)|YCSB |N|2014|
|Citrus(PostgresColumar), MonetDB|[Citus Data vs. MonetDB TPC-H Shootout](https://www.monetdb.org/content/citusdb-postgresql-column-store-vs-monetdb-tpc-h-shootout)|TPC-H |N|2014|
|Hana, DB2, Postgres, Oracle|[Benchmarking Bitemporal Database Systems: Ready for the Future or Stuck in the Past?](https://websci.informatik.uni-freiburg.de/publications/EDBT2014-Benchmarking-Bitemporal-Database-Systems.pdf)|Custom|Y|2014|
|Hadoop, Spark, DataMPI|[Performance Benefits of DataMPI:A Case Study with BigDataBench](http://arxiv.org/pdf/1403.3480.pdf)|BigDataBench|N|2014|
|MySQL, Postgres,UndisclosedBigVendor1, UndisclosedBigVendor2|[Multi-Metric comparision of Relational Databases](http://oltpbenchmark.com/wiki/index.php?title=Experiments)|10 different |Y|2014|
| Aerospike, Cassandra, MongoDB, Couchbase |[Ultra High Performance NoSQL Benchmarking](http://www.aerospike.com/wp-content/uploads/2013/01/Ultra-High-Performance-NoSQL-Benchmarking.pdf)|YCSB|N|2013|
|Cassandra, HBase on EC2|[Benchmarking Scalability and Elasticity of Distributed Database Systems](http://www.vldb.org/pvldb/vol7/p1219-klems.pdf)|YCSB|Y|2013|
| Cassandra, HBase, MongoDB|[Benchmarking Top NoSQL Databases](https://www.datastax.com/wp-content/uploads/2013/02/WP-Benchmarking-Top-NoSQL-Databases.pdf)|YCSB|N|2013|
|Aerospike, Cassandra, MongoDB, Couchbase | [NoSQL Failover Characteristics](http://www.benstopford.com/wp-content/uploads/2014/03/NoSQL-Failover.pdf)      |   YCSB |N | 2013|
|MongoDb, MySQL|[RDBMS vs NoSQL: Performance and Scaling Comparison](http://www.epcc.ed.ac.uk/sites/default/files/Dissertations/2012-2013/RDBMS%20vs%20NoSQL%20-%20Performance%20and%20Scaling%20Comparison.pdf)|YCSB |Y|2013
|Cassandra|[Evalua&on	of NoSQL and	Array Databases	for	Sciencific Applications](http://datasys.cs.iit.edu/events/DataCloud2013/Lavanya_NoSQL.pdf)|YCSB |Y|2013|
|Cassandra|[An Evaluation of Cassandra for Hadoop](http://www.cs.binghamton.edu/~mgovinda/papers/dede-ieee-cloud-13.pdf)|YCSB |Y|2013|
|Neo4j, OrientDB, Titan, DEX|[An empirical comparison of graph databases](http://euranova.eu/upl_docs/publications/an-empirical-comparison-of-graph-databases.pdf)|Custom|Y|2013|
| HBase, Voldemort, Redis, VoltDB, MySQL | [Solving Big Data Challenges for Enterprise Application Performance Management](http://vldb.org/pvldb/vol5/p1724_tilmannrabl_vldb2012.pdf)      |    YCSB |Y | 2012|
|Cassandra, HBase, MongoDB, Riak| [A Vendor Independent Comparison of NoSQL Databases](https://s3-eu-west-1.amazonaws.com/benstopford/nosql-comp.pdf)|YCSB|Y|2012|
|LevelDB, BangDb, BDB|[Performance Data For LevelDB, Berkley DB And BangDB For Random Operations](http://highscalability.com/blog/2012/11/29/performance-data-for-leveldb-berkley-db-and-bangdb-for-rando.html)|YCSB |N|2012|
|Couchbase|[Couchbase Server 2.0 performance on HP ProLiant DL380p Gen8 Server](http://h20195.www2.hp.com/V2/GetPDF.aspx%2F4AA4-6203ENW.pdf)|YCSB |N|2012|
|Cassandra|[Resource Provisioning for NoSQL Datastores](http://www.globule.org/publi/RPND_master2011.pdf)|YCSB|Y|2011|
|HBase, Accumulo|[YCSB++](http://www.pdl.cmu.edu/PDL-FTP/Storage/socc2011.pdf)|YCSB++ |Y|2011|
|Hadoop, Vertica, SqlServer?|[A Comparison of Approaches to Large-Scale Data Analysis](http://database.cs.brown.edu/sigmod09/benchmarks-sigmod09.pdf)|Custom|Y|2009|
||[]()|YCSB|Y|2013|
|Polybase|[An open-source decentralized alternative to Firebase, Supabase, etc that understands tokens, wallets & ZK](https://framerusercontent.com/modules/assets/GRv4t0d6jQOJbIO7ZOFgonnXqM~f7GLGr1YpwfK85uVr8su7Mxe_3b6VkIZW94sRev8jj4.pdf)|Custom|Y|2022|
||[]()|YCSB|Y|2013|


Benchmark frameworks:

http://www.tpc.org/

https://github.com/intel-hadoop/Big-Bench

https://github.com/brianfrankcooper/YCSB/

https://amplab.cs.berkeley.edu/benchmark/

