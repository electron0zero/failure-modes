---
layout: post
title: "GitLab Database Incident"
date: 2017-01-31
categories: [outage, database, human-error]
tags: [gitlab, database, postgresql, backup, human-error]
company: GitLab
incident_date: 2017-01-31
duration: "18+ hours"
affected_services: ["GitLab.com", "GitLab CI", "GitLab Pages"]
---

On January 31, 2017, a GitLab engineer accidentally deleted the production database directory while troubleshooting performance issues, running `rm -rf` on the wrong server. The incident revealed that all five backup systems had been failing silently, resulting in 18 hours of downtime and 6 hours of data loss.

GitLab's transparent communication during the crisis - including live blogs, real-time updates, and a publicly shared recovery document - turned a disaster into a case study in crisis management and operational transparency.

<!--more-->


## Sources

- [GitLab.com database incident - January 31st 2017](https://about.gitlab.com/blog/2017/02/01/gitlab-dot-com-database-incident/)
- [Postmortem of database outage of January 31](https://about.gitlab.com/blog/2017/02/10/postmortem-of-database-outage-of-january-31/)
- [Google Doc - Live incident response](https://docs.google.com/document/d/1GCK53YDcBWQveod9kfzW-VCxIABGiryG7_z_6jHdVik/pub) (Historical)