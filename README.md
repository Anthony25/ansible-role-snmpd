## [![DebOps project](http://debops.org/images/debops-small.png)](http://debops.org) snmpd

[![Travis CI](http://img.shields.io/travis/debops/ansible-snmpd.svg?style=flat)](http://travis-ci.org/debops/ansible-snmpd) [![test-suite](http://img.shields.io/badge/test--suite-ansible--snmpd-blue.svg?style=flat)](https://github.com/debops/test-suite/tree/master/ansible-snmpd/) 

[SNMP](https://en.wikipedia.org/wiki/Simple_Network_Management_Protocol) is
an universal protocol which can be used to monitor and manage networked
devices. `debops.snmpd` role can be used to configure `snmpd` service on
a Debian or Ubuntu host, which in turn can be used to monitor that host
resources like CPU utilization, memory and storage capacity, network usage
and more.


### Role dependencies

- `debops.ferm`
- `debops.secret`
- `debops.apt_preferences`
- `debops.tcpwrappers`

### Are you using this as a standalone role without DebOps?

You may need to include missing roles from the [DebOps common
playbook](https://github.com/debops/debops-playbooks/blob/master/playbooks/common.yml)
into your playbook.

[Try DebOps now](https://github.com/debops/debops) for a complete solution to run your Debian-based infrastructure.





### Authors and license

`snmpd` role was written by:
- Maciej Delmanowski | [e-mail](mailto:drybjed@gmail.com) | [Twitter](https://twitter.com/drybjed) | [GitHub](https://github.com/drybjed)

License: [GPLv3](https://tldrlegal.com/license/gnu-general-public-license-v3-%28gpl-3%29)

***

This role is part of the [DebOps](http://debops.org/) project. README generated by [ansigenome](https://github.com/nickjj/ansigenome/).
