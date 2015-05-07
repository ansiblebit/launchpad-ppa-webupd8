# ansiblebit.launchpad-ppa-webupd8

[![License](https://img.shields.io/badge/license-New%20BSD-blue.svg?style=flat)](https://raw.githubusercontent.com/ansiblebit/launchpad-ppa-webupd8/master/LICENSE)
[![Build Status](https://travis-ci.org/ansiblebit/launchpad-ppa-webupd8.svg?branch=master)](https://travis-ci.org/ansiblebit/launchpad-ppa-webupd8)

[![Platform](http://img.shields.io/badge/platform-debian-a80030.svg?style=flat)](#)
[![Platform](http://img.shields.io/badge/platform-ubuntu-dd4814.svg?style=flat)](#)

[![Project Stats](https://www.openhub.net/p/ansiblebit-launchpad-ppa-webupd8/widgets/project_thin_badge.gif)](https://www.openhub.net/p/ansiblebit-launchpad-ppa-webupd8/)

An [Ansible](http://www.ansible.com) role to setup the [webupd8](http://www.webupd8.org/) launchpad apt repository. 

## Requirements

- ansible >= 1.8.4

## Role Variables

| variable | description |
|:----------------------------:|:-----|
| launchpad_ppa_webupd8_cache_valid_time | the amount of time in seconds the apt cache is valid. |

## Dependencies

None.

## Playbooks

Including an example of how to use your role
(for instance, with variables passed in as parameters)
is always nice for users too:

    - hosts: servers
      roles:
         - { role: ansiblebit.launchpad-ppa-webupd8, launchpad_ppa_webupd8_cache_valid_time: 3600 }

## Changelog

- v3.0.0 : 7 May 2015
    - synchronized major version with primogen for easier reference
- v1.1.2 : 5 May 2015
    - standardize tests with primogen v2.2.0
- v1.1.0 : 30 April 2015
    - ansible minimum requirements now set to 1.8.4
    - renamed ppa_webupd8_cache_valid_time to launchpad_ppa_webupd8_cache_valid_time
    - standardized testing with primogen v2.0.6
    - added test/support for debian jessie
    - added test/support for ubuntu vivid
- v1.0.4 : 28 April 2015
    - update_cache is now run with sudo privileges
- v1.0.2 : 17 April 2015
    - update_cache=yes when adding new repositories
- v1.0.0 : 4 April 2015
    - initial release

## Links


## License

BSD

## Author Information

- [steenzout](http://github.com/steenzout)

## Links

- [WebUpd8 team : Oracle Java (JDK) 7 / 8 / 9 Installer PPA](https://launchpad.net/~webupd8team/+archive/ubuntu/java)
