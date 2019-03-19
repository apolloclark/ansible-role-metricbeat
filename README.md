# Ansible Role: metricbeat

Ansible Role to install and configure Elastic Metricbeat for Ubuntu.


## Requirements

None.

## Role Variables

Available variables are listed below, along with default values (see `defaults/main.yml`).
You can overload the variables by creating a dictionary called "metricbeat", ex:

    metricbeat:
      version: 6.6.2

## Dependencies

None.

## Example Playbook

    - hosts: all
      roles:
        - apolloclark.metricbeat

## License

MIT / BSD

## Author Information

This role was created in 2017 by [Apollo Clark](https://www.apolloclark.com/)
