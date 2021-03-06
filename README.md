## [![DebOps project](http://debops.org/images/debops-small.png)](http://debops.org) slapd

[![Travis CI](http://img.shields.io/travis/debops/ansible-slapd.svg?style=flat)](http://travis-ci.org/debops/ansible-slapd) [![test-suite](http://img.shields.io/badge/test--suite-ansible--slapd-blue.svg?style=flat)](https://github.com/debops/test-suite/tree/master/ansible-slapd/)  [![Ansible Galaxy](http://img.shields.io/badge/galaxy-debops.slapd-660198.svg?style=flat)](https://galaxy.ansible.com/list#/roles/2243)


This role installs and manages `slapd`, OpenLDAP server. It will
automatically generate and store secure passwords for administrator
accounts and install useful scripts.

### Installation

This role requires at least Ansible `v1.8`. To install it, run:

    ansible-galaxy install debops.slapd

Additional Ansible modules, `ldap_attr` and `ldap_entry` can be found in
[DebOps playbooks](https://github.com/debops/debops-playbooks/) repository.

### Documentation

More information about `debops.slapd` can be found in the
[official debops.slapd documentation](http://docs.debops.org/en/latest/ansible/roles/debops.slapd.html).


### Role dependencies

- `debops.ferm`
- `debops.secret`
- `debops.tcpwrappers`

### Are you using this as a standalone role without DebOps?

You may need to include missing roles from the [DebOps common
playbook](https://github.com/debops/debops-playbooks/blob/master/playbooks/common.yml)
into your playbook.

[Try DebOps now](https://github.com/debops/debops) for a complete solution to run your Debian-based infrastructure.





### Authors and license

`slapd` role was written by:
- Maciej Delmanowski | [e-mail](mailto:drybjed@gmail.com) | [Twitter](https://twitter.com/drybjed) | [GitHub](https://github.com/drybjed)

License: [GPLv3](https://tldrlegal.com/license/gnu-general-public-license-v3-%28gpl-3%29)

***

This role is part of the [DebOps](http://debops.org/) project. README generated by [ansigenome](https://github.com/nickjj/ansigenome/).
