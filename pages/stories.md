---
layout: page
title: Stories
permalink: /stories/
---

Postmortems/Incident Reports/War Stories from real-world failures

### Algolia
- [Salt Incident: May 3rd, 2020 Retrospective and Update](https://blog.algolia.com/salt-incident-may-3rd-2020-retrospective-and-update/)
- [May 30 SSL incident](https://www.algolia.com/blog/engineering/may-30-ssl-incident/)

### Atlassian
- [multi product multi week outage - April 4th, 2022](https://www.atlassian.com/engineering/april-2022-outage-update)
  - [Day 7 of the great Atlassian outage: IT giant still struggling to restore access](https://www.theregister.com/2022/04/11/atlassian_still_down/)

### Authzed
- [Post-Mortem: Feb 16 2022](https://authzed.com/blog/post-mortem-feb-2022/)

### AWS
- [Summary of the Amazon Kinesis Event in the Northern Virginia (US-EAST-1) Region - November, 25th 2020](https://aws.amazon.com/message/11201/)
  - Summary [Tweet thread](https://twitter.com/GergelyOrosz/status/1337871810738655235) of the incident. [Threadreader link](https://threadreaderapp.com/thread/1337869823204847616.html)

### Bungie
- [Destiny 2 Outage and Rollback - Feb 12, 2020](https://www.bungie.net/en/Explore/Detail/News/48723)

### Cloudflare
- [Details of the Cloudflare outage on July 2, 2019](https://blog.cloudflare.com/details-of-the-cloudflare-outage-on-july-2-2019/)
- [Cloudflare outage on July 17, 2020](https://blog.cloudflare.com/cloudflare-outage-on-july-17-2020/)
- [A Byzantine failure in the real world - Cloudflare API availability incident on 2020-11-02](https://blog.cloudflare.com/a-byzantine-failure-in-the-real-world/), [Twitter thread](https://twitter.com/HenryR/status/1333336495260745729)
- [Cloudflare outage on June 21, 2022](https://blog.cloudflare.com/cloudflare-outage-on-june-21-2022/)

### Celer Bridge
- [Celer Network Bridge dapp incident analysis by Coinbase](https://www.coinbase.com/blog/celer-bridge-incident-analysis)

### DataDog
- [Datadog Outage Affects Multiple Regions for a Day](https://www.datadoghq.com/blog/2023-03-08-multiregion-infrastructure-connectivity-issue/), also see [reddit discussion](https://www.reddit.com/r/devops/comments/11luq9r/psa_datadog_outage/))

### DataSpring
- [Datacenter and tornado](https://www.dataspring.cz/datacentrum-a-tornado/)
  - Website is in Czech, use a translation service to read it. [archive.today link](http://archive.today/fWE85)
  - This is a story of how a data center dealt with a tornado, a good reminder to verify your offsite backups, a disaster recovery plan, and conduct disaster recovery dry runs.

### Deno
- [May 30 incident update - May 30, 2022](https://deno.com/blog/2022-05-30-outage-post-mortem)

## DoorDash
- [How to Handle Kubernetes Health Checks - health checks outage on Black Friday](https://doordash.engineering/2022/08/09/how-to-handle-kubernetes-health-checks/)

### Facebook
- October 4, 2021, Facebook Group (Facebook, Instagram, WhatsApp, Oculus) outage
  - [Understanding How Facebook Disappeared from the Internet](https://blog.cloudflare.com/october-2021-facebook-outage/)
  - [What happened on the Internet during the Facebook outage](https://blog.cloudflare.com/during-the-facebook-outage/)
  - [Update about the October 4th outage - Facebook Engineering](https://engineering.fb.com/2021/10/04/networking-traffic/outage/)
  - [More details about the October 4 outage - Facebook Engineering](https://engineering.fb.com/2021/10/05/networking-traffic/outage-details/)
  - [What Happened to Facebook, Instagram, WhatsApp? Krebs on Security](https://krebsonsecurity.com/2021/10/what-happened-to-facebook-instagram-whatsapp/)
  - [Why was Facebook down for five hours? - YouTube](https://www.youtube.com/watch?v=-wMU8vmfaYo) - Ben Eater explains the facebook outage in detail with a demo
  - This outage had side effects on the whole internet, the most common one was ISPs getting DoSed with DNS queries for facebook domains.

### Fastly
- [Summary of June 8 outage - Fastly](https://www.fastly.com/blog/summary-of-june-8-outage) - June 8, 2021, global outage

### Garmin
- [Garmin's multi-day service outage, thread by Osma Ahvenlampi](https://twitter.com/osma/status/1286374610204844033)

### GitHub
- [October 21 post-incident analysis](https://github.blog/2018-10-30-oct21-post-incident-analysis/)
- [April service disruptions analysis - May 22, 2020](https://github.blog/2020-05-22-april-service-disruptions-analysis/)
- [An update on recent service disruptions - March 16, 2022](https://github.blog/2022-03-23-an-update-on-recent-service-disruptions/)

### GitLab
- [GitLab.com database incident - January 31st 2017](https://about.gitlab.com/blog/2017/02/01/gitlab-dot-com-database-incident/)
   - [Postmortem of database outage of January 31](https://about.gitlab.com/blog/2017/02/10/postmortem-of-database-outage-of-january-31/)

### Google Cloud
- [An update on Sunday’s service disruption - June 3, 2019](https://cloud.google.com/blog/topics/inside-google-cloud/an-update-on-sundays-service-disruption)
- [Google OAuth access was unavailable - December 14, 2020](https://status.cloud.google.com/incident/zall/20013)
  - Relevant Twitter [thread 1](https://twitter.com/copyconstruct/status/1338716306963456000) and [thread 2](https://twitter.com/copyconstruct/status/1340140498418208770)
- [Global: Experiencing Issue with Cloud networking - November 16, 2021](https://status.cloud.google.com/incidents/6PM5mNd43NbMqjCZ5REh)
  - [HN Thread](https://news.ycombinator.com/item?id=29243617)
  - [A bug introduced 6 months ago brought Google's Cloud Load Balancer to its knees](https://www.theregister.com/2021/11/23/google_outage/)
- [London (europe-west2) cooling system failure - July 19, 2022](https://status.cloud.google.com/incidents/fmEL9i2fArADKawkZAa2)
  - Oracle Cloud also saw a cooling system failure on the same day in London Data Center

### Grafana Labs
- [How a GCP Persistent Disk Incident Snowballed into a 23-Hour Outage -- and Taught Us Some Important Lessons](https://grafana.com/blog/2020/01/23/how-a-gcp-persistent-disk-incident-snowballed-into-a-23-hour-outage-and-taught-us-some-important-lessons/)
- [How we responded to a 2-hour outage in our Grafana Cloud Hosted Prometheus service](https://grafana.com/blog/2021/03/26/how-we-responded-to-a-2-hour-outage-in-our-grafana-cloud-hosted-prometheus-service/)
- [How a production outage in Grafana Cloud's Hosted Prometheus service was caused by a bad etcd client setup](https://grafana.com/blog/2020/04/07/how-a-production-outage-in-grafana-clouds-hosted-prometheus-service-was-caused-by-a-bad-etcd-client-setup/)
- [How adding Kubernetes label selectors caused an outage in Grafana Cloud Logs — and how we resolved it](https://grafana.com/blog/2022/08/31/how-adding-kubernetes-label-selectors-caused-an-outage-in-grafana-cloud-logs-and-how-we-resolved-it/)

### Independent Stories
- [Debugging a misbehaving distributed system, by Erin](https://twitter.com/erincandescent/status/1281280157073002496),  alt:[Threadreader](https://threadreaderapp.com/thread/1281280157073002496.html)
- [Ask HN: Tell me an engineering war story from your career](https://news.ycombinator.com/item?id=13987098)
- [Impact of an upstream outage - chain of issues due to launchpad outage](https://github.com/electron0zero/failure-modes/issues/58)

### Indian Registry for Internet Names and Numbers (IRINN)
- [Missing IRINN route objects & outage! - 6 July 2020, Anurag Bhatia](https://anuragbhatia.com/2020/07/networking/isp-column/missing-irinn-route-objects-outage/)

### KLAYswap
- [KLAYswap Incident Report - Feb 03, 2022](https://medium.com/klayswap/klayswap-incident-report-feb-03-2022-70ff124aed6b), also see a more details analysis [Post Mortem of KlaySwap Incident through BGP Hijacking - EN](https://medium.com/s2wblog/post-mortem-of-klayswap-incident-through-bgp-hijacking-en-3ed7e33de600)

### Level 3 Communications (CenturyLink)
- [August 30th, 2020: Analysis of CenturyLink/Level 3 Outage](https://blog.cloudflare.com/analysis-of-todays-centurylink-level-3-outage/)

## Loom.com
- [In Place AWS Elasticache Redis Upgrade went wrong](https://twitter.com/vhmth/status/1599133796091461632)

### Netflix
- [Containers taking out nodes - Twitter thread by Sargun Dhillon](https://twitter.com/sargun/status/1228495222658613250?s=19). [Thread Reader link](https://threadreaderapp.com/thread/1228495222658613250.html)

### Nomad Bridge
- [Nomad Bridge incident analysis by Coinbase](https://www.coinbase.com/blog/nomad-bridge-incident-analysis)

### n8n
- [Ask HN: Azure has run out of compute – anyone else affected?](https://news.ycombinator.com/item?id=33743567)

### Oracle Cloud
- [Datacenter cooling infrastructure failed in UK South - July 19, 2022](https://ocistatus.oraclecloud.com/#/incidents/ocid1.oraclecloudincident.oc1.phx.amaaaaaavwew44aa7zoskanlspjh4ll6wxhwxrbkbed4d4cnupxexzqzvlyq)
  - Following unseasonably high temperatures in the UK South (London) region, two cooler units in the data center experienced a failure when they were required to operate above their design limits. As a result, temperatures in the data center began to climb causing a subset of Compute infrastructure to go into protective shut down.
  - Google Cloud also had cooling related failure in London (europe-west2)

### Roblox
- [Roblox 73-hour outage - October 28th, 2021](https://blog.roblox.com/2022/01/roblox-return-to-service-10-28-10-31-2021/)

### Rogers Communications
- [Rogers Communications outage in Canada - July 8, 2022](https://blog.cloudflare.com/cloudflares-view-of-the-rogers-communications-outage-in-canada/)
  - [Causes - Wikipedia](https://en.wikipedia.org/wiki/2022_Rogers_Communications_outage#Causes)

### Salesforce
- [Multi-Instance Service Disruption on May 11-12, 2021](https://help.salesforce.com/s/articleView?id=000358392&type=1)
  - [That Salesforce outage: Global DNS downfall started by one engineer trying a quick fix • The Register](https://www.theregister.com/2021/05/19/salesforce_root_cause/) - in the news

## Stripe
- [Stripe down for for all those with Stripe Tax enabled](https://news.ycombinator.com/item?id=32558191#32558635), and status updates on [@stripestatus twitter page](https://twitter.com/stripestatus/status/1561809071061155841)

### Slack
- [Users are unable to connect to Slack - Tuesday, May 12, 2020](https://status.slack.com/2020-05-12),
and [Twitter Thread](https://twitter.com/copyconstruct/status/1260988880397856769) by copyconstruct
- [Slack’s Outage on January 4th, 2021](https://slack.engineering/slacks-outage-on-january-4th-2021/)
- [May 12, 2020 Outage - A Terrible, Horrible, No-Good, Very Bad Day at Slack - Slack Engineering](https://slack.engineering/a-terrible-horrible-no-good-very-bad-day-at-slack/)
- [Double Trouble with Datastores - Slack’s Incident o February 22, 2022](https://slack.engineering/slacks-incident-on-2-22-22/)

### Twitter
- [An update on our security incident - social engineering attack, July 2020](https://blog.twitter.com/en_us/topics/company/2020/an-update-on-our-security-incident.html)

### Verizon
- [How Verizon and a BGP Optimizer Knocked Large Parts of the Internet Offline Today](https://blog.cloudflare.com/how-verizon-and-a-bgp-optimizer-knocked-large-parts-of-the-internet-offline-today/)
