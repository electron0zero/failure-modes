---
layout: post
title: "Slack May 12, 2020 Outage"
date: 2020-05-12
categories: [outage, infrastructure, distributed-systems]
tags: [slack, infrastructure, messaging, distributed-systems]
company: Slack
incident_date: 2020-05-12
duration: "8+ hours"
affected_services: ["Slack Messaging", "File Sharing", "Search"]
---

On May 12, 2020, Slack experienced a major outage caused by HAProxy configuration bugs that prevented proper service discovery with Consul. The incident began with database issues at 8:30 AM Pacific, followed by the main outage at 4:45 PM Pacific, which was resolved by rolling restart of the HAProxy fleet.

The outage occurred during peak remote work adoption due to COVID-19, highlighting the critical dependency of distributed teams on messaging platforms and the cascading effects of infrastructure configuration issues.

<!--more-->

## Sources

- [A terrible, horrible, no good, very bad day at Slack - Slack Engineering](https://slack.engineering/a-terrible-horrible-no-good-very-bad-day-at-slack/)