Playbook
=========

Interconnect ansible play for create network topology with Router, Broker, Clients and deploy it.

Build/Test Status
------------
[![Build Status](https://travis-ci.org/rh-messaging-qe/iqa-topologies.svg?branch=master)](https://travis-ci.org/rh-messaging-qe/iqa-topologies)
[![GitHub Issues](https://img.shields.io/github/issues/rh-messaging-qe/iqa-topologies.svg)](https://github.com/rh-messaging-qe/iqa-topologies/issues)
[![GitHub Issues](https://img.shields.io/github/issues-pr/rh-messaging-qe/iqa-topologies.svg)](https://github.com/rh-messaging-qe/iqa-topologies/pulls)
![Contributions welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg)
[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)

## Supported systems
CentOS 6/7 and RHEL 6/7

## Tests
For testing we use the [provision_docker](https://github.com/chrismeyersfsu/provision_docker) playbook.

### Requirements
* docker_host (by default on localhost)

### How to run tests
```bash
$ make test
```

## License
Apache 2.0

## Author Information
Messaging QE team @ redhat.com
