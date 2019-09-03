---
title: "Projects"
permalink: "/projects/"
collection: projects
---

{% include base_path %}

Education
======
* title: "Byzantine Fault Tracing"
excerpt: "Implementing a novel byzantine fault tracing algorithm for distributed services using blockchain and code execution profiles<br/>"

Using blockchain, memory maps and code watermarking, we detect Byzantine faults over a deployment of distributed systems.
The blockchain runs on the public network, forwarding requests from the client to the private subnet of the distributed service
The functions it performs generated certain memory maps. These are compared to correct ones that are pre stored on the blockchain(during set up), to detect anomalies in the system.
If detected, the system is removed from the network and replaced by its backup, where the process continues again.

*
---
title: "Testing environment for [Linkerd](https://github.com/linkerd/linkerd2) deployments"
excerpt: "Building testing environments in different cloud deployments for linkerd<br/><img src='/images/500x300.png'>"
---
Currently working with the developers on building the architecture of said deployment and setting the environment for various tests, using kubernetes, docker, pulumi and Travis CI.

So begun work on cluster formation on GCP and integration using pulumi scripts, after approval will work on running linkerd on the cloud cluster, and finish integration of test scripts.


Work experience
======
* Summer 2015: Research Assistant
  * Github University
  * Duties included: Tagging issues
  * Supervisor: Professor Git

* Fall 2015: Research Assistant
  * Github University
  * Duties included: Merging pull requests
  * Supervisor: Professor Hub
  
Skills
======
* Skill 1
* Skill 2
  * Sub-skill 2.1
  * Sub-skill 2.2
  * Sub-skill 2.3
* Skill 3

Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
* Currently signed in to 43 different slack teams
