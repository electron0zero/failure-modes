---
layout: post
title: "Netflix Container Infrastructure Incident"
date: 2020-02-28
categories: [outage, containers, infrastructure]
tags: [netflix, containers, kubernetes, infrastructure]
company: Netflix
incident_date: 2020-02-28
duration: "Several hours"
affected_services: ["Netflix Streaming", "Container Infrastructure"]
---

Netflix experienced an incident where containers were taking out nodes in their infrastructure, affecting streaming services. The issue highlighted the challenges of container orchestration at Netflix's massive scale and the potential for container-level issues to impact entire nodes.

The incident demonstrated the complexities of managing containerized workloads in production environments and the importance of proper resource isolation and monitoring.

<!--more-->

## Sources

- [Containers taking out nodes](https://twitter.com/sargun/status/1228495222658613250?s=19)