# Ansible Role: RabbitMQ

Installs RabbitMQ service on RHEL/CentOS.
RabbitMQ is an open-source message-broker software that originally implemented the Advanced Message Queuing Protocol (AMQP). Currently this role installs RabbitMQ pre-configured with defaults tuned for Magento. 

## Requirements

None.

## Role Variables

See `defaults/main.yml` for details.

## Dependencies

* `classyllama.rabbitmq`

## Example Playbook

    - hosts: all
      vars:
      roles:
        - { role: classyllama.rabbitmq }

## License

This work is licensed under the MIT license. See LICENSE file for details.
