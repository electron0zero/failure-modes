---
layout: post
title: "GitHub Outage"
date: 2018-10-21
categories: [outage, database, infrastructure]
tags: [github, database, mysql, infrastructure, git]
company: GitHub
incident_date: 2018-10-21
duration: "24+ hours"
affected_services: ["GitHub.com", "Git Operations", "Issues", "Pull Requests"]
---

On October 21, 2018, GitHub experienced a major outage lasting over 24 hours due to network connectivity issues between their East and West Coast data centers. The incident resulted in database inconsistencies and required extensive data reconciliation to restore service.

The outage affected millions of developers worldwide and highlighted the challenges of maintaining consistency in distributed systems during network partitions, leading to significant improvements in GitHub's infrastructure resilience.

<!--more-->

## Sources

- [October 21 post-incident analysis - GitHub Blog](https://github.blog/2018-10-30-oct21-post-incident-analysis/)