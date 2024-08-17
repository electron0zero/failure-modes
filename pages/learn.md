---
layout: page
title: Learn
permalink: /learn/
---

## Learn about building resilient systems

A collection of resources to learn about failures and failure modes of software systems.

## Blog Posts

Blog posts on failures, reliability, testing, and other relevant topics

- [Chaos Engineering — Review Lineage Driven Failure Injection(LDFI)](https://medium.com/becloudy/chaos-engineering-review-lineage-driven-failure-injection-ldfi-a1c831abe504)

- [I test in prod - Charity Majors](https://increment.com/testing/i-test-in-production/)

- [Incident Analysis Posts - Adaptive Capacity Labs](https://adaptivecapacitylabs.com/blog/category/incident-analysis)

- [Failure Modes and Continuous Resilience - Adrian cockcroft](https://medium.com/@adrianco/failure-modes-and-continuous-resilience-6553078caad5), also see [this thread](https://twitter.com/daveadams/status/1285987768749961220)

- [Lessons learned in incident management - Dropbox](https://dropbox.tech/infrastructure/lessons-learned-in-incident-management)

- [Post Mortem - The Cloudflare Blog](https://blog.cloudflare.com/tag/postmortem), lists postmortems from cloudflare

- [How we’re building a production readiness review process at Grafana Labs](https://grafana.com/blog/2021/10/13/how-were-building-a-production-readiness-review-process-at-grafana-labs/)

## Talks

Talks on how systems fail, demos of systems, and other wisdom on how we can build better systems -

- [Debugging Under Fire: Keep your Head when Systems have Lost their Mind - Bryan Cantrill](https://www.youtube.com/watch?v=30jNsCVLpAE)

- [Bryan Cantrill - Docker in Production: Tales From the Engine Room](https://www.youtube.com/watch?v=0T2XFSALOaU)

- [Keynote: High Reliability Infrastructure Migrations - Julia Evans, Software Engineer, Stripe](https://www.youtube.com/watch?v=obB2IvCv-K0)

- ["I See What You Mean" by Peter Alvaro](https://www.youtube.com/watch?v=R2Aa4PivG0g)

- [Orchestrated Chaos: Applying Failure Testing Research at Scale](https://www.youtube.com/watch?v=QOTNBKx9Irc)

- [Orchestrating Chaos Applying Database Research in the Wild - Peter Alvaro](https://www.youtube.com/watch?v=YplkQu6a80Q)

- [Doing Site Reliability Engineering (SRE) the Right Way](https://www.youtube.com/watch?v=eKff1yqq0OM&list=WL&index=11)

- [Testing Cloud-Native Databases with Chaos Mesh - Siddon Tang](https://www.youtube.com/watch?v=FIB1qvLHYsw)

- [The Hurricane's Butterfly: Debugging Pathologically Performing Systems](https://www.youtube.com/watch?v=7AO4wz6gI3Q)

- [How AWS Minimizes the Blast Radius of Failures](https://www.youtube.com/watch?v=swQbA4zub20)

## Tools & Projects

Tools and projects focused on failures and failure modes of software systems.

### [Chaos Toolkit](https://github.com/chaostoolkit)
The Open Source Platform for Chaos Engineering

### [Chaos Monkey](https://github.com/Netflix/chaosmonkey)
Chaos Monkey is a resiliency tool that helps applications tolerate random instance failures.

### [Learning from Incidents in Software](https://www.learningfromincidents.io/)
Incidents are costly. Without spending time analyzing and determining the conditions
that exist for an incident to take place, we won't learn how to successfully
remove or recover from these conditions in the future.

Let's help each other learn.

### [SNAFU catchers ](https://www.snafucatchers.com/)
A consortium of industry leaders and researchers united in the common cause of
understanding and coping with the immense levels of complexity involved in the
operation of critical digital services.

### [Resilience engineering papers](https://github.com/lorin/resilience-engineering)
Contains notes about people active in resilience engineering as well as
some influential researchers who are no longer with us.


### [Kubernetes Failure Stories](https://github.com/hjacobs/kubernetes-failure-stories)
A compiled list of links to public failure stories related to Kubernetes.

### [Chaos Mesh](https://github.com/chaos-mesh/chaos-mesh)
Chaos Mesh is a cloud-native Chaos Engineering platform that orchestrates chaos
on Kubernetes environments.

### [Debugging stories - Dan Luu](https://github.com/danluu/debugging-stories)
A collection of links to various debugging stories.

### [A List of Post-mortems! - Dan Luu](https://github.com/danluu/post-mortems)
A collection of postmortems.

### [Testing Distributed Systems](https://github.com/asatarin/testing-distributed-systems)
Curated list of resources on testing distributed systems 

### [k6 - A modern load testing tool](https://github.com/grafana/k6)


## Research

Research on failures and how to test, build, and operate reliable systems -

- [Lineage-driven Fault Injection - the morning paper](https://blog.acolyer.org/2015/03/26/lineage-driven-fault-injection/)

- [The Network is Reliable - the morning paper](https://blog.acolyer.org/2014/12/18/the-network-is-reliable/)

- [Gray failure: the Achilles’ heel of cloud-scale systems - the morning paper](https://blog.acolyer.org/2017/06/15/gray-failure-the-achilles-heel-of-cloud-scale-systems/)

- [Trade-offs under pressure: heuristics and observations of teams resolving internet service outages (Part I) - the morning paper](https://blog.acolyer.org/2020/01/22/trade-offs-under-pressure-part-1/)

- [Trade-offs under pressure: heuristics and observations of teams resolving internet service outages (Part II) - the morning paper](https://blog.acolyer.org/2020/01/24/trade-offs-under-pressure-part-2/)

- [Report from the SNAFU catchers Workshop on Coping With Complexity](https://snafucatchers.github.io/)

- [How Complex Systems Fail -  Richard I. Cook](https://how.complexsystems.fail/), ([Original pdf](https://www.gwern.net/docs/technology/2000-cook.pdf))

### Fault Isolation using Shuffule Sharding
  - [AWS re:Invent 2018: How AWS Minimizes the Blast Radius of Failures (ARC338)](https://www.youtube.com/watch?v=swQbA4zub20)
  - [Shuffle Sharding: Massive and Magical Fault Isolation](https://aws.amazon.com/blogs/architecture/shuffle-sharding-massive-and-magical-fault-isolation/)
  - [Shuffle Sharding - Cortex](https://cortexmetrics.io/docs/guides/shuffle-sharding/)
  - [Level 300: Fault Isolation with Shuffle Sharding](https://wellarchitectedlabs.com/reliability/300_labs/300_fault_isolation_with_shuffle_sharding/)
  - [Patterns for the Distributed Systems in Cloud — Part 1](https://medium.com/@vagees/patterns-for-the-distributed-systems-in-cloud-part-1-b51dc454f0c7)
  - [Uno, DDoS, Tres — The magic of Shuffle sharding](https://hamzahabdulla1.medium.com/uno-ddos-tres-the-magic-of-shuffle-sharding-13d6c9d3a974)
  - [Great thread from Colm MacCárthaigh](https://twitter.com/colmmacc/status/1034492056968736768), alt: [thread reader](https://threadreaderapp.com/thread/1034492056968736768.html)


## Systems

Real-world failure stories and incident postmortems of widely used systems

### PostgreSQL
- [Transaction ID wraparound outage at mandrill](https://mailchimp.com/what-we-learned-from-the-recent-mandrill-outage/)
- [Transaction ID wraparound outage at sentry](https://blog.sentry.io/2015/07/23/transaction-id-wraparound-in-postgres)

### Kafka
- [Kafkapocalypse: a postmortem on our service outage](https://blog.parse.ly/post/1738/kafkapocalypse/)
- [Stories from the Front: Lessons Learned from Supporting Apache Kafka](https://www.confluent.io/blog/stories-front-lessons-learned-supporting-apache-kafka/)
- [How to Lose Messages on a Kafka Cluster - Part 1 ](https://jack-vanlightly.com/blog/2018/9/14/how-to-lose-messages-on-a-kafka-cluster-part1)

### Kubernetes
- [Compilation of public failure/horror stories related to Kubernetes](https://github.com/hjacobs/kubernetes-failure-stories)
- [10 Ways to Shoot Yourself in the Foot with Kubernetes, #9 Will Surprise You - Laurent Bernaille](https://www.youtube.com/watch?v=QKI-JRs2RIE)
- [Kubernetes pods /etc/resolv.conf ndots:5 option and why it may negatively affect your application performance](https://pracucci.com/kubernetes-dns-resolution-ndots-options-and-why-it-may-affect-application-performances.html), also see [DNS Lookups in Kubernetes](https://mrkaran.dev/posts/ndots-kubernetes/)

### YugabyteDB
- [How Plume Handled Billions of Operations Per Day Despite an AWS Zone Outage](https://blog.yugabyte.com/how-plume-handled-billions-of-operations-per-day-despite-an-aws-zone-outage/)
