# Ansible role: docker

Install docker community edition on EL7

## Requirements

None.

## Role Variables

  * `docker_users` list of users to add to docker group

## Dependencies

None.

## Example Playbook

    - hosts: docker
      roles:
        - dragomirr.docker

## License

GPLv3
