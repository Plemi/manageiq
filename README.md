# ManageIQ

[![Build Status](https://travis-ci.org/ManageIQ/manageiq.svg?branch=ivanchuk)](https://travis-ci.org/ManageIQ/manageiq)
[![Code Climate](https://codeclimate.com/github/ManageIQ/manageiq/badges/gpa.svg)](https://codeclimate.com/github/ManageIQ/manageiq)
[![Codacy](https://api.codacy.com/project/badge/grade/9ffce48ccb924020ae8f9e698048e9a4)](https://www.codacy.com/app/ManageIQ/manageiq)
[![Coverage Status](https://coveralls.io/repos/ManageIQ/manageiq/badge.svg?branch=ivanchuk&service=github)](https://coveralls.io/github/ManageIQ/manageiq?branch=ivanchuk)
[![Security](https://hakiri.io/github/ManageIQ/manageiq/ivanchuk.svg)](https://hakiri.io/github/ManageIQ/manageiq/ivanchuk)
[![Open Source Helpers](https://www.codetriage.com/manageiq/manageiq/badges/users.svg)](https://www.codetriage.com/manageiq/manageiq)

[![Chat](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/ManageIQ/manageiq?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)
[![Translate](https://img.shields.io/badge/translate-zanata-blue.svg)](https://translate.zanata.org/zanata/project/view/manageiq)
[![License](http://img.shields.io/badge/license-APACHE2-blue.svg)](https://www.apache.org/licenses/LICENSE-2.0.html)


[![Build history for master branch](https://buildstats.info/travisci/chart/ManageIQ/manageiq?branch=ivanchuk&includeBuildsFromPullRequest=false&buildCount=50)](https://travis-ci.org/ManageIQ/manageiq/branches)

## Forked project

This fork of the official ManageIQ core app aimes at adding support for API and SUI auth token generation for SSO (SAML, OIDC) user authentication.

It simply has a modified Gemfile that points to a forked version of the official ManagegIQ Api plugin : https://github.com/guilrom/manageiq-api (which is based on this PR https://github.com/ManageIQ/manageiq/pull/14959/files by Abellotti)

To work properly, this forked version of ManageIQ app must be used alongside this forked version of the official ManageIQ Service UI app : https://github.com/guilrom/manageiq-ui-service

In order to use this forked project in a docker context, it is also advised to rely on this fork of manageiq-pods project to build proper docker images :
- https://github.com/guilrom/manageiq-pods

## Discover, Optimize, and Control your Hybrid IT

### Manage containers, virtual machines, networks, and storage from a single platform

ManageIQ is an open-source Management Platform that delivers the insight, control, and
automation that enterprises need to address the challenges of managing hybrid
IT environments.  It has the following feature sets:

* **Insight**: Discovery, Monitoring, Utilization, Performance, Reporting, Analytics, Chargeback, and Trending.
* **Control**: Security, Compliance, Alerting, Policy-Based Resource and Configuration Management.
* **Automate**: IT Process, Task and Event, Provisioning, Workload Management and Orchestration.
* **Integrate**: Systems Management, Tools and Processes, Event Consoles, CMDB, RBA, and Web Services.

## Get Started

*  [**Download community builds** for your platform](http://manageiq.org/download/)
*  [**Fork the source** to contribute](https://github.com/ManageIQ/manageiq)
*  [**Learn** to use ManageIQ](https://www.youtube.com/user/ManageIQVideo)

## Learn more

*  [**Read** developer guides](https://github.com/ManageiQ/guides)
*  [**Chat** with contributors on Gitter](https://gitter.im/ManageIQ/manageiq)
*  [**File or view bug reports and feature requests** using Issues on Github](https://github.com/ManageIQ/manageiq/issues?state=open)
*  [**Ask** questions of ManageIQ experts](http://talk.manageiq.org/)
*  [**Discuss** ManageIQ with developers and power users](http://talk.manageiq.org/)

We respectfully ask that you do not directly email any manageiq committers with
questions or problems. The community is best served when discussions are held in
public.

## Licensing

See [LICENSE.txt](LICENSE.txt).

Except where otherwise noted, all ManageIQ source files are covered by
the following copyright and license notice:

Copyright 2014-2019 ManageIQ Authors.

## Export Notice

By downloading ManageIQ software, you acknowledge that you understand all of the
following: ManageIQ software and technical information may be subject to the
U.S. Export Administration Regulations (the "EAR") and other U.S. and foreign
laws and may not be exported, re-exported or transferred (a) to any country
listed in Country Group E:1 in Supplement No. 1 to part 740 of the EAR
(currently, Cuba, Iran, North Korea, Sudan & Syria); (b) to any prohibited
destination or to any end user who has been prohibited from participating in
U.S. export transactions by any federal agency of the U.S. government; or (c)
for use in connection with the design, development or production of nuclear,
chemical or biological weapons, or rocket systems, space launch vehicles, or
sounding rockets, or unmanned air vehicle systems. You may not download ManageIQ
software or technical information if you are located in one of these countries
or otherwise subject to these restrictions. You may not provide ManageIQ
software or technical information to individuals or entities located in one of
these countries or otherwise subject to these restrictions. You are also
responsible for compliance with foreign law requirements applicable to the
import, export and use of ManageIQ software and technical information.
