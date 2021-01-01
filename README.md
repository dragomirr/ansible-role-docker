# Ansible role: docker

Install docker community edition on EL 7/8 and ubuntu 18.04/20.04. Probably works on fedora/debian, didn't test.

## Requirements

None.

## Role Variables

  * `docker_users` -- list of users to add to docker group
  * `docker_containers` -- list of containers with properties
  * `docker_package_state` -- use latest if docker update required

## Dependencies

None.

## Example Playbook

```yaml
- hosts: docker
  become: yes
  gather_facts: yes

  roles:
    - dragomirr.docker
```

## License

GPLv3
