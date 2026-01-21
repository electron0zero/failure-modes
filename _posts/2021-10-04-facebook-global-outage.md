---
layout: post
title: "Update about the October 4th outage"
date: 2021-10-04
categories: [outage, networking, bgp]
tags: [facebook, instagram, whatsapp, bgp, dns, networking]
company: Facebook
incident_date: 2021-10-04
duration: "6+ hours"
affected_services: ["Facebook", "Instagram", "WhatsApp", "Oculus"]
---

On October 4, 2021, Facebook experienced a 6+ hour global outage affecting Facebook, Instagram, WhatsApp, and Oculus. During routine backbone capacity maintenance, a bug in Facebook's audit tool caused BGP routes to be withdrawn, disconnecting their data centers from the internet and causing DNS cascade failures.

The outage created additional complications as Facebook's internal systems, including door badge systems, were also down, making it physically difficult for engineers to access data centers. The incident highlighted risks of centralized internet infrastructure and the cascading effects of network-level failures.

<!--more-->


## Sources

- [Understanding How Facebook Disappeared from the Internet](https://blog.cloudflare.com/october-2021-facebook-outage/)
- [What happened on the Internet during the Facebook outage](https://blog.cloudflare.com/during-the-facebook-outage/)
- [Update about the October 4th outage - Facebook Engineering](https://engineering.fb.com/2021/10/04/networking-traffic/outage/)
- [More details about the October 4 outage - Facebook Engineering](https://engineering.fb.com/2021/10/05/networking-traffic/outage-details/)
- [What Happened to Facebook, Instagram, WhatsApp? Krebs on Security](https://krebsonsecurity.com/2021/10/what-happened-to-facebook-instagram-whatsapp/)
- [Why was Facebook down for five hours? - YouTube](https://www.youtube.com/watch?v=-wMU8vmfaYo) - Ben Eater's technical explanation