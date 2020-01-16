# failure-modes
list of failure modes/stories/postmortems in software systems


# Failure Stories

## PostgreSQL
- [Transaction ID wraparound outage at mandrill](https://mailchimp.com/what-we-learned-from-the-recent-mandrill-outage/)
- [Transaction ID wraparound outage at sentry](https://blog.sentry.io/2015/07/23/transaction-id-wraparound-in-postgres)

## Kafka
- [Kafkapocalypse: a postmortem on our service outage](https://blog.parse.ly/post/1738/kafkapocalypse/)
- [Stories from the Front: Lessons Learned from Supporting Apache Kafka](https://www.confluent.io/blog/stories-front-lessons-learned-supporting-apache-kafka/)
- [How to Lose Messages on a Kafka Cluster - Part 1 ](https://jack-vanlightly.com/blog/2018/9/14/how-to-lose-messages-on-a-kafka-cluster-part1)

## Kubernetes
- [Compilation of public failure/horror stories related to Kubernetes](https://github.com/hjacobs/kubernetes-failure-stories)
- [10 Ways to Shoot Yourself in the Foot with Kubernetes, #9 Will Surprise You - Laurent Bernaille](https://www.youtube.com/watch?v=QKI-JRs2RIE)


# Notable Resources

## Postmortems
- [postmortem of global Cloudflare outage](https://blog.cloudflare.com/details-of-the-cloudflare-outage-on-july-2-2019/)
- [postmortem of major GitHub outage](https://github.blog/2018-10-30-oct21-post-incident-analysis/)

## Talks
- [Debugging Under Fire: Keep your Head when Systems have Lost their Mind • Bryan Cantrill](https://www.youtube.com/watch?v=30jNsCVLpAE)
- [Bryan Cantrill - Docker in Production: Tales From the Engine Room](https://www.youtube.com/watch?v=0T2XFSALOaU)
- [Keynote: High Reliability Infrastructure Migrations - Julia Evans, Software Engineer, Stripe](https://www.youtube.com/watch?v=obB2IvCv-K0)
- ["I See What You Mean" by Peter Alvaro](https://www.youtube.com/watch?v=R2Aa4PivG0g)
- [Orchestrated Chaos: Applying Failure Testing Research at Scale](https://www.youtube.com/watch?v=QOTNBKx9Irc)
- [Orchestrating Chaos Applying Database Research in the Wild - Peter Alvaro](https://www.youtube.com/watch?v=YplkQu6a80Q)

## Research
- [Lineage-driven Fault Injection - the morning paper](https://blog.acolyer.org/2015/03/26/lineage-driven-fault-injection/)
- [The Network is Reliable - the morning paper](https://blog.acolyer.org/2014/12/18/the-network-is-reliable/)
- [Gray failure: the Achilles’ heel of cloud-scale systems - the morning paper](https://blog.acolyer.org/2017/06/15/gray-failure-the-achilles-heel-of-cloud-scale-systems/)

## Blog posts
- [Chaos Engineering — Review Lineage Driven Failure Injection(LDFI)](https://medium.com/becloudy/chaos-engineering-review-lineage-driven-failure-injection-ldfi-a1c831abe504)
- [I test in prod - Charity Majors](https://increment.com/testing/i-test-in-production/)

## Projects
- [Chaos Toolkit](https://github.com/chaostoolkit)
- [chaos monkey - Netflix](https://github.com/Netflix/chaosmonkey)
