---
layout: post
title: "DoorDash Kubernetes Health Checks Incident"
date: 2022-08-09
categories: [outage, kubernetes, health-checks]
tags: [doordash, kubernetes, health-checks, black-friday]
company: DoorDash
incident_date: 2022-08-09
duration: "Several hours"
affected_services: ["DoorDash Platform", "Order Processing"]
---

DoorDash experienced a significant incident related to Kubernetes health check configurations during a high-traffic period similar to Black Friday. The incident demonstrated how misconfigurations in health checks can cascade through containerized applications during peak load.

The outage highlighted the critical importance of properly configured health checks in Kubernetes environments and the challenges of maintaining service reliability during traffic spikes in food delivery platforms.

<!--more-->

## Sources

- [How to handle Kubernetes Health Checks - Black Friday](https://doordash.engineering/2022/08/09/how-to-handle-kubernetes-health-checks/)