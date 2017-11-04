## [![DebOps](https://debops.org/images/debops-small.png)](https://debops.org) rabbitmq_management

<!-- This file was generated by Ansigenome. Do not edit this file directly but
     instead have a look at the files in the ./meta/ directory. -->

[![Travis CI](https://img.shields.io/travis/debops/ansible-rabbitmq_management.svg?style=flat)](https://travis-ci.org/debops/ansible-rabbitmq_management)
[![test-suite](https://img.shields.io/badge/test--suite-ansible--rabbitmq__management-blue.svg?style=flat)](https://github.com/debops/test-suite/tree/master/ansible-rabbitmq_management/)
[![Ansible Galaxy](https://img.shields.io/badge/galaxy-debops.rabbitmq_management-660198.svg?style=flat)](https://galaxy.ansible.com/debops/rabbitmq_management)


[RabbitMQ](https://www.rabbitmq.com/) is an Open Source message broker which
supports AMQP, STOMP and MQTT protocols.

This ansible role can be used to enable and configure the
[RabbitMQ Management Console](https://www.rabbitmq.com/management.html).
The role can configure the plugin in a locally installed RabbitMQ service, or
configure a reverse proxy to a remote instance of RabbitMQ.

See the `debops.rabbitmq_server` Ansible role for general RabbitMQ service
deployment and configuration.

### Installation

This role requires at least Ansible `v2.3.0`. To install it, run:

```Shell
ansible-galaxy install debops.rabbitmq_management
```

### Documentation

More information about `debops.rabbitmq_management` can be found in the
[official debops.rabbitmq_management documentation](https://docs.debops.org/en/latest/ansible/roles/ansible-rabbitmq_management/docs/).



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