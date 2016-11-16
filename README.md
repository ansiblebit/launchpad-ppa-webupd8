# ansiblebit.launchpad-ppa-webupd8

[![License](https://img.shields.io/badge/license-New%20BSD-blue.svg?style=flat)](https://raw.githubusercontent.com/ansiblebit/launchpad-ppa-webupd8/master/LICENSE)
[![Build Status](https://travis-ci.org/ansiblebit/launchpad-ppa-webupd8.svg?branch=master)](https://travis-ci.org/ansiblebit/launchpad-ppa-webupd8)

[![Platform](http://img.shields.io/badge/platform-debian-a80030.svg?style=flat)](#)
[![Platform](http://img.shields.io/badge/platform-ubuntu-dd4814.svg?style=flat)](#)

[![Project Stats](https://www.openhub.net/p/ansiblebit-launchpad-ppa-webupd8/widgets/project_thin_badge.gif)](https://www.openhub.net/p/ansiblebit-launchpad-ppa-webupd8/)

An [Ansible](http://www.ansible.com) role to setup the [webupd8](http://www.webupd8.org/) launchpad apt repository. 


## Tests

| Family | Distribution | Version | Test Status |
|:-:|:-:|:-:|:-:|
| Debian | Debian  | Jessie    | [![x86_64](http://img.shields.io/badge/x86_64-passed-006400.svg?style=flat)](#) |
| Debian | Ubuntu  | Precise   | [![x86_64](http://img.shields.io/badge/x86_64-passed-006400.svg?style=flat)](#) |
| Debian | Ubuntu  | Yakkety   | [![x86_64](http://img.shields.io/badge/x86_64-passed-006400.svg?style=flat)](#) |
| Debian | Ubuntu  | Xenial    | [![x86_64](http://img.shields.io/badge/x86_64-passed-006400.svg?style=flat)](#) |
| Debian | Ubuntu  | Trusty    | [![x86_64](http://img.shields.io/badge/x86_64-passed-006400.svg?style=flat)](#) |
| Debian | Ubuntu  | Vivid     | [![x86_64](http://img.shields.io/badge/x86_64-passed-006400.svg?style=flat)](#) |
| Debian | Ubuntu  | Wily      | [![x86_64](http://img.shields.io/badge/x86_64-passed-006400.svg?style=flat)](#) |


## Requirements

- ansible >= 1.9.4

# Facts

| variable | description |
|:-:|:--|
| launchpad_ppa_webupd8_os_supported | fact set by this role to determine if the host OS is supported. |


## Role Variables

None.


## Dependencies

None.


## Playbooks

    - hosts: servers
      roles:
         - role: ansiblebit.launchpad-ppa-webupd8
           launchpad_ppa_webupd8_cache_valid_time: 3600


## Links

- [WebUpd8 team : Oracle Java (JDK) 7 / 8 / 9 Installer PPA](https://launchpad.net/~webupd8team/+archive/ubuntu/java)
