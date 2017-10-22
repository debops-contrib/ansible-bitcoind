## [![DebOps](https://debops.org/images/debops-small.png)](https://debops.org) bitcoind

<!-- This file was generated by Ansigenome. Do not edit this file directly but
     instead have a look at the files in the ./meta/ directory. -->

[![Travis CI](https://img.shields.io/travis/debops-contrib/ansible-bitcoind.svg?style=flat)](https://travis-ci.org/debops-contrib/ansible-bitcoind)
[![test-suite](https://img.shields.io/badge/test--suite-ansible--bitcoind-blue.svg?style=flat)](https://github.com/debops/test-suite/tree/master/ansible-bitcoind/)
[![Ansible Galaxy](https://img.shields.io/badge/galaxy-debops--contrib.bitcoind-660198.svg?style=flat)](https://galaxy.ansible.com/debops-contrib/bitcoind)


The `debops-contrib.bitcoind` role allows you to manage and configure [bitcoind].
bitcoind can be used to run a [full node]  in the distributed cryptocurrency network [Bitcoin].
A full node is a program that fully validates transactions and blocks and
therefore enforces all of the rules of Bitcoin.

[Bitcoin]: https://bitcoin.org
[bitcoind]: https://en.bitcoin.it/wiki/Bitcoind
[full node]: https://en.bitcoin.it/wiki/Full_node

### Installation

This role requires at least Ansible `v2.1.5`. To install it, run:

```Shell
ansible-galaxy install debops-contrib.bitcoind
```

### Documentation

<!-- FIXME: Change to the canonical URL when it has been setup. https://github.com/debops/docs/issues/111 -->
More information about `debops-contrib.bitcoind` can be found in the
[official debops-contrib.bitcoind documentation](https://debops-contrib.readthedocs.io/en/latest/ansible/roles/ansible-bitcoind/docs/).

### Contributing

Please note that this repository is not the upstream repository where changes should be contributed to.
Head over to https://github.com/debops/debops where you can find the contents of this repo and where changes are welcome.



### Are you using this as a standalone role without DebOps?

You may need to include missing roles from the [DebOps common
playbook](https://github.com/debops/debops-playbooks/blob/master/playbooks/common.yml)
into your playbook.

[Try DebOps now](https://debops.org/) for a complete solution to run your Debian-based infrastructure.





### Authors and license

- [Robin Schneider](https://docs.debops.org/en/latest/debops-keyring/docs/entities.html#debops-keyring-entity-ypid) (maintainer) | [e-mail](mailto:ypid@riseup.net) | [GitHub](https://github.com/ypid)

License: [GPL-3.0](https://tldrlegal.com/license/gnu-general-public-license-v3-%28gpl-3%29)

***

This role is part of [DebOps Contrib](https://github.com/debops-contrib/debops-contrib). README generated by [ansigenome](https://github.com/nickjj/ansigenome/).
<!-- Ansigenome sources: https://github.com/ypid/ypid-ansible-common/tree/master/template_READMEs/debops-contrib -->
