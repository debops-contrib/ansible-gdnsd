## [![DebOps](https://debops.org/images/debops-small.png)](https://debops.org) gdnsd

[![Travis CI](http://img.shields.io/travis/debops-contrib/ansible-gdnsd.svg?style=flat)](https://travis-ci.org/debops-contrib/ansible-gdnsd)
[![test-suite](http://img.shields.io/badge/test--suite-ansible--gdnsd-blue.svg?style=flat)](https://github.com/ganto/debops-test-suite/tree/master/ansible-gdnsd/)
[![Ansible Galaxy](https://img.shields.io/badge/galaxy-debops--contrib.gdnsd-660198.svg?style=flat)](https://galaxy.ansible.com/debops-contrib/gdnsd)

### Warning, this is a Beta role

This role has been marked by the author as a beta role, which means that it
might be significantly changed in the future. Be careful while using this role
in a production environment.

***

[gdnsd](http://gdnsd.org/) is a powerful Authoritative-only DNS server with
some advanced features such as geographic (or other sorts of) balancing,
redirection, wighting and service-state-conscious failover at the DNS layer.

The `ganto.gdnsd` Ansible role installs and configures the name service and
is able to generate zone files from name records defined in the Ansible
inventory and properly increase the serial on zone updates.


### Installation

This role requires at least Ansible `v1.9.0`. To install it run:

```Shell
ansible-galaxy install debops-contrib.gdnsd
```


### Documentation

Currently the documentation is only available in raw format in the
[docs](/docs/) directory.


### Are you using this as a standalone role without DebOps?

You may need to include missing roles from the [DebOps common
playbook](https://github.com/debops/debops-playbooks/blob/master/playbooks/common.yml)
into your playbook.

[Try DebOps now](https://debops.org/) for a complete solution to run your Debian-based infrastructure.


### Authors and license

The content of this repository was written by:

- [Reto Gantenbein](https://linuxmonk.ch/) | [e-mail](mailto:reto.gantenbein@linuxmonk.ch) | [GitHub](https://github.com/ganto)

License: [GPLv3](https://tldrlegal.com/license/gnu-general-public-license-v3-%28gpl-3%29)

