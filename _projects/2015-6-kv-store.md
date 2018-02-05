---
layout:     project
title:      Building a Fault-Tolerant Key-Value Store
date:       2015-06-01
date-str:       Spring 2015
code:
repo:       MembershipProtocol
doc:
demo:
best:       true
---

It’s a Key-Value Store written in C++, which supports the four CRUD operations with additional support
for load balancing and fault tolerance.
It uses a ring-based DHT, and keeps three replicas of each key-value pair with a quorum-based consistency model.
Beneath the KV store, there is a distributed membership protocol which keeps track of the ring in the event of
a new node joining or when a node fails.
It was the programming project of the University of Illinois’s online Cloud Computing Concepts course, which I got the complete grade.
