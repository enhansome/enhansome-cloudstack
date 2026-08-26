![Build Status](https://github.com/resmo/awesome-cloudstack/actions/workflows/main.yml/badge.svg)

# Awesome Apache CloudStack with stars

> A curated list of bookmarks, projects, tutorials, videos and other cool resources from the CloudStack ecosystem.

## Table of Contents

* [Essentials](#essentials)
* [Installation Guides](#installation-guides)
* [Packages and Images](#packages-and-templates)
* [Command Line Interface Clients](#command-line-interface-clients)
* [Configuration Management Integrations](#configuration-management-integrations)
* [Libraries](#libraries)
* [Operational Extensions](#operational-extensions)
* [Public Cloud Providers](#public-cloud-providers)
* [Videos](#videos)
* [Articles, Tutorials, Blogs, etc.](#articles-tutorials-blogs-etc)
* [Development](#development)
* [Community](#community)

## Essentials

* [Apache CloudStack](https://cloudstack.apache.org/)
* [CloudStack API Reference](https://cloudstack.apache.org/api.html)

## Installation Guides

* [CloudStack Official Installation Guide](https://docs.cloudstack.apache.org/en/latest/installguide/)
* [CloudStack x86\_64 Ubuntu KVM Install Guide](https://rohityadav.cloud/blog/cloudstack-kvm/)
* [CloudStack ARM64 Ubuntu KVM Install Guide](https://rohityadav.cloud/blog/cloudstack-arm64-kvm/)
* [Ceph Installation and CloudStack Usage Guide](https://rohityadav.cloud/blog/ceph/)

## Packages and Templates

### Installation Packages

* [Install Packages from Community Repo](https://download.cloudstack.org)
* [Install Packages from ShapeBlue](https://www.shapeblue.com/packages/)

### Templates

* [Instance Templates Packer by PCextreme](https://github.com/PCextreme/packer-templates) ⚠️ Archived
* [SystemVM Packer](https://github.com/MissionCriticalCloud/systemvm-packer) ⭐ 8 | 🐛 0 | 🌐 Shell | 📅 2021-01-29
* [Instance Templates Packer by Schuberg Philis](https://github.com/MissionCriticalCloud/bubble-templates-packer) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2026-02-08
* [Pre-Built Instance Templates](http://dl.openvm.eu/cloudstack/)

## Command Line Interface Clients

* [cmk - Apache CloudMonkey (Official Go-based CLI)](https://github.com/apache/cloudstack-cloudmonkey) ⭐ 118 | 🐛 19 | 🌐 Go | 📅 2026-08-21
* [cs (Python)](https://github.com/ngine-io/cs) ⭐ 89 | 🐛 0 | 🌐 Python | 📅 2026-08-24
* [CloudStack Go-SDK (Official SDK)](https://github.com/apache/cloudstack-go) ⭐ 39 | 🐛 17 | 🌐 Go | 📅 2026-08-17
* [cloudstack-cli (Ruby)](https://github.com/niwo/cloudstack-cli) ⭐ 17 | 🐛 0 | 🌐 Ruby | 📅 2026-04-16

## Configuration Management Integrations

### Ansible

* [Ansible Cloud Infra Role (Advanced Networking)](https://github.com/swisstxt/ansible-role-cloud-infra) ⭐ 6 | 🐛 4 | 🌐 Jinja | 📅 2025-11-28
* [Ansible CloudStack Integration](https://docs.ansible.com/ansible/latest/collections/ngine_io/cloudstack/index.html)

### Kubernetes

* [CloudStack Kubernetes Provider](https://github.com/apache/cloudstack-kubernetes-provider) ⭐ 51 | 🐛 16 | 🌐 Go | 📅 2026-08-26
* [CloudStack CSI Driver](https://github.com/shapeblue/cloudstack-csi-driver) ⭐ 1 | 🐛 14 | 🌐 Go | 📅 2026-08-23
* [CAPC - Cluster API Provider for CloudStack](https://cluster-api-cloudstack.sigs.k8s.io/introduction)

### Terraform

* [CloudStack Provider](https://github.com/apache/cloudstack-kubernetes-provider) ⭐ 51 | 🐛 16 | 🌐 Go | 📅 2026-08-26

### Vagrant

* [Vagrant Cloudstack Provider ](https://github.com/MissionCriticalCloud/vagrant-cloudstack) ⭐ 68 | 🐛 17 | 🌐 Ruby | 📅 2022-10-06

## Libraries

* [cs (Python)](https://github.com/ngine-io/cs) ⭐ 89 | 🐛 0 | 🌐 Python | 📅 2026-08-24
* [go-cloudstack (Go)](https://github.com/xanzy/go-cloudstack) ⚠️ Archived
* [apache-cloudstack-java-client (Java)](https://github.com/Autonomiccs/apache-cloudstack-java-client) ⭐ 20 | 🐛 0 | 🌐 Java | 📅 2019-03-13
* [cloudstack\_client (Ruby)](https://github.com/niwo/cloudstack_client) ⭐ 14 | 🐛 0 | 🌐 Ruby | 📅 2026-08-25
* [golang-cloudstack-library (Go)](https://github.com/atsaki/golang-cloudstack-library) ⭐ 10 | 🐛 2 | 🌐 Go | 📅 2017-03-25
* [cloudstack-php (PHP)](https://github.com/PCextreme/cloudstack-php) ⚠️ Archived
* [.NET SDK for CloudStack](https://github.com/richardlawley/cloudstack.net) ⭐ 8 | 🐛 3 | 🌐 C# | 📅 2022-06-22
* [cloudstack PHP Client (PHP - ACS 4.10 compatible)](https://github.com/myENA/cloudstack-php-client) ⭐ 7 | 🐛 1 | 🌐 PHP | 📅 2020-01-17
* [vhd-util for manipulating Xen VHDs](https://github.com/NuxRo/vhd-util) ⭐ 4 | 🐛 0 | 🌐 Shell | 📅 2016-03-19
* [apache-cloudstack-javascript-client (JavaScript)](https://github.com/Autonomiccs/apache-cloudstack-javascript-client) ⭐ 2 | 🐛 0 | 🌐 JavaScript | 📅 2017-04-14
* [Apache libcloud (Python)](https://libcloud.apache.org/)
* [Apache jclouds (Java)](https://jclouds.apache.org/)

## Operational Extensions

### Montitoring and Graphs

* [garm - Multi-cloud, auto-scaling manager for GitHub Actions & Gitea self-hosted runners](https://github.com/cloudbase/garm) ⭐ 384 | 🐛 29 | 🌐 Go | 📅 2026-08-25
* [collectd-cloudstack Plugin](https://github.com/exoscale/collectd-cloudstack) ⚠️ Archived
* [CloudStack Nagios Monitoring by SWISS TXT](https://github.com/swisstxt/cloudstack-nagios) ⭐ 6 | 🐛 0 | 🌐 Ruby | 📅 2021-09-02
* [csbench - CloudStack Benchmarking Tool](https://github.com/apache/cloudstack-csbench) ⭐ 6 | 🐛 4 | 🌐 Go | 📅 2026-05-15
* [CloudStack Statistics into InfluxDB](https://github.com/niwo/cloudstats) ⭐ 2 | 🐛 0 | 🌐 Ruby | 📅 2021-07-08

### RealHostIP replacement

* [nip.io - realhostip compatible service](https://github.com/exentriquesolutions/nip.io) ⭐ 1,773 | 🐛 16 | 🌐 Python | 📅 2026-06-19
* [powerdns-cloudstack-proxy-dns](https://github.com/terbolous/powerdns-cloudstack-proxy-dns) ⭐ 2 | 🐛 1 | 🌐 Lua | 📅 2014-06-26

### Billing Solutions

* [HostBill (commercial)](http://hostbillapp.com/feature/cloudstack-overview/)
* [Amysta (commercial)](http://www.amysta.com/)
* [Cyclops](https://icclab.github.io/cyclops/)

### Misc

* [Chaotic - Chaos for Clouds](https://github.com/ngine-io/chaotic) ⭐ 74 | 🐛 9 | 🌐 Python | 📅 2026-08-17
* [Scalr - Autoscaling for Clouds](https://github.com/ngine-io/scalr) ⭐ 50 | 🐛 3 | 🌐 Python | 📅 2026-08-24
* [Alternative CloudStack-UI by Bitworks Software, Ltd.](https://bwsw.github.io/cloudstack-ui/)

## Public Cloud Providers

* [Ikoula](https://www.ikoula.com/en)
* [LeaseWeb](https://www.leaseweb.com/)
* [PCextreme](https://www.pcextreme.com/)

## Videos

* [Introduction to Apache CloudStack by David Nalley](https://www.youtube.com/watch?v=1MDLg-wxB6g)
* [CloudOps Channel](https://www.youtube.com/channel/UC0FMV0TSW6jvSRGC26r4-Gw)

## Articles, Tutorials, Blogs, etc

* [Wikipedia Article](https://en.wikipedia.org/wiki/Apache_CloudStack)
* [ShapeBlue Blog](https://www.shapeblue.com/blog/)
* [Remi Bergsma's blog](https://blog.remibergsma.com/tag/cloudstack-2/)
* [shankerbalan.net](https://shankerbalan.net/)
* [Rohit Yadav's Blog](https://rohityadav.cloud)

## Development

### Main

* [GitHub](https://github.com/apache/cloudstack) ⭐ 3,030 | 🐛 983 | 🌐 Java | 📅 2026-08-26
* [Apache CloudStack Issue Tracker - GitHub](https://github.com/apache/cloudstack/issues) ⭐ 3,030 | 🐛 983 | 🌐 Java | 📅 2026-08-26
* [Hackerbook](https://github.com/shapeblue/hackerbook) ⭐ 73 | 🐛 0 | 📅 2026-01-25 - Guide to CloudStack Development
* [Apache CloudStack Issue Tracker - Jira (retired)](https://issues.apache.org/jira/browse/CLOUDSTACK)

### Development Environment

* [CloudStack Simulator Container](https://github.com/ansible/cloudstack-test-container) ⭐ 9 | 🐛 1 | 🌐 Dockerfile | 📅 2025-09-11
* [mbx](https://github.com/shapeblue/mbx) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2026-03-30 - build dev and QA environments on KVM
* [Apache CloudStack Simulator as Docker Container](https://hub.docker.com/r/apache/cloudstack-simulator)

### Continuous Integrations

* [GitHub CI CloudStack Service Workflow](https://github.com/apache/cloudstack-terraform-provider/blob/main/.github/workflows/acceptance.yml) ⭐ 53 | 🐛 29 | 🌐 Go | 📅 2026-08-19
* [Trillian](https://github.com/shapeblue/Trillian) ⭐ 14 | 🐛 16 | 🌐 Jinja | 📅 2026-08-26
* [bubble-blueprint](https://github.com/MissionCriticalCloud/bubble-blueprint) ⭐ 5 | 🐛 2 | 🌐 Python | 📅 2025-07-03

### Build with Docker

* [DEB Builder](https://github.com/khos2ow/cloudstack-deb-builder) ⭐ 4 | 🐛 2 | 🌐 Shell | 📅 2021-11-05
* [RPM Builder](https://github.com/khos2ow/cloudstack-rpm-builder) ⭐ 1 | 🐛 1 | 🌐 Shell | 📅 2021-11-23

## Community

* [Mailing Lists](http://cloudstack.apache.org/mailing-lists.html)
* IRC: `irc://irc.libera.chat/cloudstack`
* [Slack](https://apachecloudstack.slack.com)

## Contributing

Found an awesome project, blog, video etc.? Send me a pull request!

### Guidelines

* Please make an individual pull request for each suggestion
* Make sure the TravisCI tests pass on your pull request
* Use the following format for links: \[Resource]\(URL)
* New categories or improvements to the existing categorization are welcome

## License

[![CC BY 4.0](https://licensebuttons.net/l/by/4.0/88x31.png)](https://creativecommons.org/licenses/by/4.0/)

Awesome CloudStack is licensed under a [Creative Commons Attribution 4.0 International License](https://creativecommons.org/licenses/by/4.0/).

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-26._
