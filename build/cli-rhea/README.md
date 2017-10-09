Interconnect Client - Ansible role
=========

[![Build Status](https://travis-ci.org/Frawless/ansible-rhea-client.svg?branch=master)](https://travis-ci.org/ansible-rheal-client)

Interconnect ansible role for install client based on RHEA library.

## Supported systems
CentOS 6/7 and RHEL 6/7 (only 64b versions!)

## Tests
For testing we use the [provision_docker](https://github.com/chrismeyersfsu/provision_docker) playbook.

### Requirements
* dokcer_host (by default on localhost)

### How to run tests
```bash
$ cd test && make all
```

## License
Apache 2.0

## Author Information
Messaging QE team @ redhat.com
