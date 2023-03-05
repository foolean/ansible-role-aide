# ansible-role-aide

Ansible role to manage aide


## Requirements

    None


## Dependencies

    None


## Role Variables

    * aide_state

    Specify whether or not AIDE should be  installed (present) or removed (absent).

    (default: present)


## Example playbook

    ```yaml
    ---
    - hosts: all

      roles:
          - foolean/aide
    ```


## Supported Operating Systems

    * Debian (11)
    * RedHat (8)
    * Rocky (8)

## Compliance

    * CIS Debian Linux 11 Benchmark v1.0.0
    * CIS RedHat Enterprise Linux 8 Benchmark v2.0.0
    * CIS Rocky Linux 8 Benchmark v1.0.0

## License

    BSD-3-Clause
