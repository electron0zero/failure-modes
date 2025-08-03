---
layout: post
title: "Multi-Product, Multi-Week Outage - April 4th, 2022"
date: 2022-04-04
categories: [outage, database, maintenance]
tags: [atlassian, jira, confluence, database, maintenance-gone-wrong]
company: Atlassian
incident_date: 2022-04-04
duration: "2+ weeks"
affected_services: ["Jira", "Confluence", "Bitbucket", "Opsgenie"]
---

On April 4, 2022, Atlassian began routine maintenance to delete inactive user accounts but a script logic error caused active customer data to be deleted instead. This affected 775+ customers for over two weeks, making it one of the longest outages in modern SaaS history.

Recovery was complicated by the scale of affected customers and data dependencies between Atlassian products. The incident highlighted critical gaps in maintenance script testing, backup independence, and the need for circuit breakers in destructive operations.

<!--more-->


## Sources

- [Multi-Product, Multi-Week Outage - April 4th, 2022](https://www.atlassian.com/engineering/april-2022-outage-update)
- [Day 7 of the great Atlassian outage: IT giant still struggling to restore access](https://www.theregister.com/2022/04/11/atlassian_still_down/)
- [Post-Incident Review by Atlassian](https://www.atlassian.com/engineering/post-incident-review-april-2022-outage)
- [The Scoop: Inside the Longest Atlassian Outage of All Time](https://newsletter.pragmaticengineer.com/p/scoop-atlassian?ref=blog.pragmaticengineer.com)