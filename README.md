# Ansible Role: update system

Ansible generic role to update system 

## Requirements

None.

## Role Variables

Available variables are listed below, along with default values:

    # Exlude a package (or list of package) from update
    exclude:
  		- dummypackage

## Dependencies

None.

## Install role

    ansible-galaxy install gaeldb.update

## Example Playbook

    - hosts: servers
      roles:
        - role: gaeldb.update
          become: yes

## License

MIT / BSD

## Author Information

This role was created in 2023 by [Gael Barbier](https://www.linkedin.com/in/gael-barbier/), founder of [Skalab](https://www.skalab.fr).
