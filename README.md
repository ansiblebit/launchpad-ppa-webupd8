# ansiblebit.launchpad-ppa-webupd8

[![Build Status](https://travis-ci.org/ansiblebit/launchpad-ppa-webupd8.svg?branch=master)](https://travis-ci.org/ansiblebit/launchpad-ppa-webupd8)
[![License](https://img.shields.io/badge/license-New%20BSD-blue.svg?style=flat)](https://raw.githubusercontent.com/ansiblebit/launchpad-ppa-webupd8/master/LICENSE)

[![Project Stats](https://www.openhub.net/p/ansiblebit-launchpad-ppa-webupd8/widgets/project_thin_badge.gif)](https://www.openhub.net/p/ansiblebit-launchpad-ppa-webupd8/)

An [Ansible](http://www.ansible.com) role to setup the [webupd8](http://www.webupd8.org/) launchpad apt repository. 

A brief description of the role goes here.

## Requirements

- ansible >= 1.7.2

## Role Variables

| variable | description |
|:----------------------------:|:-----|
| ppa_webupd8_cache_valid_time | the amount of time in seconds the apt cache is valid. |

## Dependencies

None.

## Example Playbook

Including an example of how to use your role
(for instance, with variables passed in as parameters)
is always nice for users too:

    - hosts: servers
      roles:
         - { role: ansiblebit.launchpad-ppa-webupd8, ppa_webupd8_cache_valid_time: 3600 }

## Changelog

- v1.0.4 : 28 April 2015
    - update_cache is now run with sudo privileges
- v1.0.2 : 17 April 2015
    - update_cache=yes when adding new repositories
- v1.0.0 : 4 April 2015
    - initial release

## License

BSD

## Author Information

- [steenzout](http://github.com/steenzout)

## Links

- [WebUpd8 team : Oracle Java (JDK) 7 / 8 / 9 Installer PPA](https://launchpad.net/~webupd8team/+archive/ubuntu/java)
