---
layout:     project
title:      Building a Fault-Tolerant Key-Value Store
date:       Spring 2015
code:
repo:       MembershipProtocol
doc:
demo:
best:       true
---

It's a Key-Value Store written in C++ which supports the four CRUD operations in addition to
its load balancing and fault tolerance. It uses a ring-based DHT and keeps three replicas of each key-value pair and
supports quorum consistency level for CRUD operations. Beneath the KV store, a distributed membership protocol
is always running to keep track of the ring in the event of a new node joining or when a node fails.
It was the programming project of the University of Illinois's online Cloud Computing Concepts course
which I got the complete grade.
