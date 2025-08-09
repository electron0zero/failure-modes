---
layout: post
title: "Summary of the Amazon Kinesis Event in the Northern Virginia (US-EAST-1) Region"
date: 2020-11-25
categories: [outage, cloud, cascade-failure]
tags: [aws, kinesis, capacity, cascading-failure, dependency]
company: AWS
incident_date: 2020-11-25
duration: "20 hours"
affected_services: ["Kinesis", "Lambda", "CloudWatch", "Elasticsearch", "AutoScaling"]
---

On November 25, 2020, AWS Kinesis experienced an outage in US-EAST-1 when new capacity additions caused servers to exceed maximum operating system thread limits. The issue began at 2:44 AM PST with the first customer impact at 5:15 AM PST, cascading through CloudWatch, Lambda, ECS, Cognito, and other services until resolution at 10:23 PM PST.

The incident demonstrated how infrastructure changes can trigger cascading failures through tightly coupled services. What started as an operating system resource limit issue eventually impacted customer monitoring, alerting, and serverless applications worldwide, highlighting critical dependencies in cloud architecture.

<!--more-->


## Sources

- [Summary of the Amazon Kinesis Event in the Northern Virginia (US-EAST-1) Region - November, 25th 2020](https://aws.amazon.com/message/11201/)
- [Twitter Thread Summary by Gergely Orosz](https://twitter.com/GergelyOrosz/status/1337871810738655235)
- [Detailed Technical Analysis](https://threadreaderapp.com/thread/1337869823204847616.html)