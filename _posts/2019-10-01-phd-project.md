---
title: On-going PhD project
date: 2019-10-01
category: blog
collaborators:
  - Simon Bliudze
  - Philippe Merle
tags:
  - OCCIware
  - JavaBIP
images:
  - images/blog/Inria-1.jpg
  - images/blog/Inria-2.jpg
---

Modern software systems are inherently concurrent. They consist of components running simultaneously and sharing access to resources provided by the execution platform. For instance, embedded control software in various domains, ranging from household robotics through operation of smart power-grids to onboard satellite software, commonly comprises, in addition to components responsible for taking the control decisions, a set of components driving the operation of sensing and actuation devices. These components interact through buses, shared memories and message buffers, leading to resource contention and potential deadlocks compromising mission- and safety-critical operations. Similar problems are observed in various kinds of software: system, work-flow management, integration software, as well as cloud computing platforms and applications, which are the main application domain of this proposal. Components of cloud applications interact through cloud resources such as virtual machines, virtual networks, virtual storages, application servers, database managers, middleware services, etc. Thereby, cloud resource sharing can lead to cloud resource contention, potential deadlocks, and operational faults.

Essentially, any software entity that goes beyond simply computing a certain function necessarily has to interact and share resources with other such entities. Correct coordination of access to resources among concurrent software entities is fundamental to ensuring that they satisfy user and system requirements avoiding operational faults and deadlock situations. This proposal targets the correct coordination of access to cloud resources among concurrent cloud application entities.