---
layout: page
title: About
permalink: /about/
---

Currently at Twitter. My interests are in designing and building highly available and reliable Distributed systems and machine learning systems.

## Experience
### Twitter
https://blog.twitter.com/engineering/en_us/a/2013/observability-at-twitter.html
https://blog.twitter.com/engineering/en_us/a/2016/observability-at-twitter-technical-overview-part-i.html
https://blog.twitter.com/engineering/en_us/a/2016/observability-at-twitter-technical-overview-part-ii.html
https://blog.twitter.com/engineering/en_us/topics/infrastructure/2019/metricsdb.html

1. Work in the **Observability team**:  the company-wide monitoring & alerting system with an in-house built time-series database using Gorilla compression techniques, that stores all system and application-level (15 Billion) metrics across the fleet at Twitter, and supports infrastructure for reading and writing metrics to the database.
2. Revamped the indexing service, a stateful, distributed and highly-available temporal set service, responsible fortracking application containers and metrics across the data center.
3. Shipped reliability improvements that increased success rate of the indexing service from 97% to 99.99%
4. Designed and shipped the real time indexing pipeline that reduces the p99 delay in indexing new metrics from 30 minutes to 10 seconds.
5. Carried the indexing service lossless and zero downtime migration efforts from bare metal to shared cloud. The service is scaled to storing 1 Billion metrics in-memory and handles 14 Million thrift RPC calls per minute.
6. Added zone-aware compatibility for writing metrics from public clouds to on-prem monitoring stack.
7. Designed the ingestion, storage and querying pipeline for metrics metadata, a Json document with informationon metrics, for automating platform service primitives such as creating monitoring dashboards and configuring canary and load tests. The designed pipeline is highly available with p99 latency below 100 milliseconds.
8. Led the efforts to extending the Observability stack to support Prometheus style multi-dimensional metrics from Kubernetes clusters.  Built a new Scala parser and executor for query language to read Kubernetes metrics.
9. Built and setup the self stack for monitoring our own services which are used for monitoring all services acrossthe fleet. This helped in separating production issues and enabled speedy recovery of services during incidents.
10. Identified and shipped bug fixes that reduced the false positive alerts from 50/day to <5/week.
11. Built a proof-of-concept timeseries correlation engine that reduces mean time to resolve issues by correlating timeseries from dependencies.
12. Worked on Read and Write infrastructure for secondly and hourly granular metrics in the Observability stack which is originally built around minutely metrics.
13. Contributed to timeseries query language by adding key functions and shipped performance improvements to the query engine for handling 100 million unique timeseries reads per minute

### Qualcomm

**Safety Application Stack for COnnected Autonomous Vehicles (CV2X)**

1. Built a intelligent transport systems (ITS) stack for connected autonomous vehicles that transmit Basic SafetyMessages following IEEE 1609 protocol.
2. Developed  a  C  library  for  parsing  and  interpreting  the  received  safety  messages  and  implemented  detectionalgorithms for providing safety warnings.

### Cisco

**Resource Based REST API’s for Unified Computing System Director (UCSD)**

1. Developed a workflow to expose operations defined on virtual machine resources and clusters as REST APIs. Employed
java reflections API and Annotations for modifying the existing architecture into a single pane of glass model.
2. Designed Role Based Access Control (RBAC) mechanisms for the generated APIs to ensure secured access.

### Contact me

[sasankpagolu@gmail.com](mailto:sasankpagolu@gmail.com)
