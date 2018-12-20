---
title: "Pseudo Dist (KV Store)"
excerpt: "A fault tolerant, high availability distributed key-value store using python and zookeeper<br/><img src='/images/500x300.png'>"
permalink: "/projects/"
collection: projects
---
Using python, and four systems, implemented a distributed key-value store. The system followed a master-slave architecture. Zookeeper was used for cluster coordination and failure detection. The system could also recover from master/node failures using data replication and when node comes back online, synchronizes its data with the rest of servers. Data was stored as JSON objects and split based on key. 

The nodes maintained two files, data and bkpdata, storing data and backup data respectively. One node acted as another's backup. When node failure occurs, all nodes notified using zookeeper, and backup node begins handling requests. When node comes back online, syncs data with other severs. (For more information click [here](https://github.com/drholmie/PseudoDist/) or check the blog)
