# ansible-apps_windows_exporter

[![Galaxy Role](https://img.shields.io/badge/galaxy-apps_windows_exporter-purple?style=flat)](https://galaxy.ansible.com/lotusnoir/apps_windows_exporter)
[![Version](https://img.shields.io/github/release/lotusnoir/ansible-apps_windows_exporter.svg)](https://github.com/lotusnoir/ansible-apps_windows_exporter/releases/latest)
[![GitHub repo size](https://img.shields.io/github/repo-size/lotusnoir/ansible-apps_windows_exporter?color=orange&style=flat)](https://galaxy.ansible.com/lotusnoir/apps_windows_exporter)
[![downloads](https://img.shields.io/ansible/role/d/)](https://galaxy.ansible.com/lotusnoir/apps_windows_exporter)
[![Ansible Quality Score](https://img.shields.io/ansible/quality/)](https://galaxy.ansible.com/lotusnoir/apps_windows_exporter)
[![License](https://img.shields.io/badge/license-Apache--2.0-brightgreen?style=flat)](https://opensource.org/licenses/Apache-2.0)

## Description

Install and configure node exporter for windows
## Requirements

none

## Role variables

See [variables](/defaults/main.yml) for more details.

## Examples

        ---
        - hosts: apps_windows_exporter
          become: true
          become_method: sudo
          gather_facts: true
          roles:
            - role: ansible-apps_windows_exporter


## License

This project is licensed under Apache License. See [LICENSE](/LICENSE) for more details.

## Author Information

- [Philippe LEAL](https://github.com/lotusnoir)
