---
layout: post
title: "Summary of June 8 outage"
date: 2021-06-08
categories: [outage, cdn, configuration]
tags: [fastly, cdn, configuration, edge-computing, deployment]
company: Fastly
incident_date: 2021-06-08
duration: "49 minutes"
affected_services: ["Fastly CDN", "Edge Compute"]
---

On June 8, 2021, Fastly experienced a 49-minute global CDN outage affecting major websites including Amazon, Reddit, GitHub, and The New York Times. A routine customer configuration change triggered a dormant software bug that caused 85% of Fastly's network to return HTTP 503 errors instead of serving content.

The bug was introduced in a May 12th software deployment but remained undetected until the specific configuration pattern was used. Recovery involved identifying and rolling back the problematic configuration globally, highlighting the risks of configuration complexity in distributed systems.

<!--more-->


## Sources

- [Summary of June 8 outage - Fastly](https://www.fastly.com/blog/summary-of-june-8-outage)
- [Service Incidents and Outages - Fastly Status](https://status.fastly.com/)