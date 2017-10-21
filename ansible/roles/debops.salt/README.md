## [![DebOps](https://debops.org/images/debops-small.png)](https://debops.org) salt

<!-- This file was generated by Ansigenome. Do not edit this file directly but
     instead have a look at the files in the ./meta/ directory. -->

[![Travis CI](https://img.shields.io/travis/debops/ansible-salt.svg?style=flat)](https://travis-ci.org/debops/ansible-salt)
[![test-suite](https://img.shields.io/badge/test--suite-ansible--salt-blue.svg?style=flat)](https://github.com/debops/test-suite/tree/master/ansible-salt/)
[![Ansible Galaxy](https://img.shields.io/badge/galaxy-debops.salt-660198.svg?style=flat)](https://galaxy.ansible/com/debops/salt)


The `debops.salt` Ansible role can be used to install and configure
[SaltStack](https://saltstack.com/) Master service. It is expected that Salt
Minions are installed using host deployment methods like PXE/preseeding, LXC
template scripts, etc. and contact the Salt Master service over DNS.

### Installation

This role requires at least Ansible `v2.2.0`. To install it, run:

```Shell
ansible-galaxy install debops.salt
```

### Documentation

More information about `debops.salt` can be found in the
[official debops.salt documentation](https://docs.debops.org/en/latest/ansible/roles/ansible-salt/docs/).



### Are you using this as a standalone role without DebOps?

You may need to include missing roles from the [DebOps common
playbook](https://github.com/debops/debops-playbooks/blob/master/playbooks/common.yml)
into your playbook.

[Try DebOps now](https://debops.org/) for a complete solution to run your Debian-based infrastructure.





### Authors and license

- Maciej Delmanowski | [e-mail](mailto:drybjed@gmail.com) | [Twitter](https://twitter.com/drybjed) | [GitHub](https://github.com/drybjed)

License: [GPLv3](https://tldrlegal.com/license/gnu-general-public-license-v3-%28gpl-3%29)

***

This role is part of [DebOps](https://debops.org/). README generated by [ansigenome](https://github.com/nickjj/ansigenome/).