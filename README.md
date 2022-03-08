# Find Default Login for Web to Access the Web Administrator page.

tools:

## CloudFlair
============

![MicroBadger Size](https://img.shields.io/microbadger/image-size/christophetd/cloudflair)
[christophetd/cloudflair](https://img.shields.io/hub.docker/image-size/cloudflair)](https://hub.docker.com/r/christophetd/cloudflair/)
![MicroBadger Layers](https://img.shields.io/microbadger/layers/christophetd/cloudflair)
[open an issue](https://github.com/christophetd/cloudflair/issues/new)

CloudFlair is a tool to find origin servers of websites protected by CloudFlare who are publicly exposed and don't restrict network access to the CloudFlare IP ranges as they should.

The tool uses Internet-wide scan data from [Censys](https://censys.io) to find exposed IPv4 hosts presenting an SSL certificate associated with the target's domain name. API keys are required and can be retrieved from your [Censys account](https://search.censys.io/account/api).

For more detail about this common misconfiguration and how CloudFlair works, refer to the companion blog post at <https://blog.christophetd.fr/bypassing-cloudflare-using-internet-wide-scan-data/>.

[Detail](cloudflair/#README.md)

## HostHunter v1.6
=================

[![Python Version](https://img.shields.io/static/v1.svg?label=Python&message=3.x&color=blue)]()
[![GitHub release](https://img.shields.io/github/release/SpiderLabs/HostHunter.svg?color=orange&style=popout)](https://github.com/SpiderLabs/HostHunter/releases)
[![License](https://img.shields.io/github/license/spiderlabs/hosthunter.svg)](https://github.com/SpiderLabs/HostHunter/blob/master/LICENSE)
[![Issues](https://img.shields.io/github/issues/SpiderLabs/HostHunter?style=popout)](https://github.com/SpiderLabs/HostHunter/issues)
[![Twitter Follow](https://img.shields.io/twitter/follow/superhedgy.svg?style=social)](https://twitter.com/superhedgy)
[![Stargazers over time](https://starchart.cc/SpiderLabs/HostHunter.svg)](https://starchart.cc/SpiderLabs/HostHunter)

A tool to efficiently discover and extract hostnames providing a large set of target IP addresses. HostHunter utilises simple OSINT techniques to map IP addresses with virtual hostnames. It generates a CSV or TXT file containing the results of the reconnaissance.
Latest version of HostHunter also takes screenshots of the target web applicatiinos. This functionality is currently in beta.

[Detail](hosthunter/#README.md)

## Default HTTP Login Hunter
===========================

The **default-http-login-hunter.sh** is a tool capable of checking more then 380 different web interfaces for default credentials. It is based on the [NNdefaccts](https://github.com/nnposter/nndefaccts) alternate fingerprint dataset maintained by nnposter.
[Detail](httplogin/#README.md)

## Censys subdomain finder
=========================

[open an issue](https://github.com/christophetd/censys-subdomain-finder/issues/new) or to [tweet @christophetd](https://twitter.com/christophetd/)

This is a tool to enumerate subdomains using the Certificate Transparency logs stored by [Censys](https://censys.io). It should return any subdomain who has ever been issued a SSL certificate by a public CA.
[Detail](subdomainfinder/#README.md)
