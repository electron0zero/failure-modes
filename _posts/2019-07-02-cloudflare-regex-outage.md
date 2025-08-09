---
layout: post
title: "Details of the Cloudflare outage on July 2, 2019"
date: 2019-07-02
categories: [outage, performance, regex]
tags: [cloudflare, regex, cpu, performance, waf]
company: Cloudflare
incident_date: 2019-07-02
duration: "27 minutes"
affected_services: ["Cloudflare CDN", "Web Application Firewall"]
---

On July 2, 2019, Cloudflare deployed a Web Application Firewall rule containing a regex with catastrophic backtracking behavior. The pattern consumed excessive CPU resources, causing global server unresponsiveness and widespread internet disruption for 27 minutes.

The incident demonstrated how a single line of code can have massive global impact. Recovery was achieved by disabling the problematic WAF rule, leading to improvements in regex testing, staged rollouts, and automated circuit breakers for resource-intensive operations.

<!--more-->


## Sources

- [Details of the Cloudflare outage on July 2, 2019](https://blog.cloudflare.com/details-of-the-cloudflare-outage-on-july-2-2019/)
- [Regex Performance Analysis Tools](https://regex101.com/) - for testing regex patterns
- [Regular Expression Denial of Service (ReDoS)](https://owasp.org/www-community/attacks/Regular_expression_Denial_of_Service_-_ReDoS)