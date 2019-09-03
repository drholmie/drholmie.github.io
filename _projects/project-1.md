---
title: "Byzantine Fault Tracing"
excerpt: "Implementing a novel byzantine fault tracing algorithm for distributed services using blockchain and code execution profiles<br/><img src='/images/500x300.png'>"
permalink: "/projects/"
collection: projects
---
Using blockchain, memory maps and code watermarking, we detect Byzantine faults over a deployment of distributed systems.
The blockchain runs on the public network, forwarding requests from the client to the private subnet of the distributed service
The functions it performs generated certain memory maps. These are compared to correct ones that are pre stored on the blockchain(during set up), to detect anomalies in the system.
If detected, the system is removed from the network and replaced by its backup, where the process continues again.
