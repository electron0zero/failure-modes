---
layout: post
title: "Grafana Labs GCP Outage"
date: 2020-01-23
categories: [outage, cloud, infrastructure]
tags: [grafana, gcp, persistent-disk, cloud, monitoring]
company: Grafana Labs
incident_date: 2020-01-23
duration: "23 hours"
affected_services: ["Grafana Cloud", "Monitoring Services"]
---

On January 23, 2020, Grafana Labs experienced a 23-hour outage caused by a Google Cloud Platform persistent disk incident. What started as a GCP infrastructure issue snowballed into an extended outage due to cascading failures and recovery complications.

The incident demonstrated how cloud provider issues can compound with application-level problems, teaching important lessons about cloud dependency management and disaster recovery planning.

<!--more-->

## Sources

- [How a GCP Persistent Disk incident snowballed into a 23-hour outage - Grafana Labs](https://grafana.com/blog/2020/01/23/how-a-gcp-persistent-disk-incident-snowballed-into-a-23-hour-outage-and-taught-us-some-important-lessons/)