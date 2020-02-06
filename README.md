# loumaris.docker

A small playbook to setup a default docker env for rancher.

## usage

Example inside a playbook:

```yaml
- name: apply common configuration to all nodes
  hosts: all
  roles:
    - loumaris.docker
```
## configuration

Possible parameter with default:

* `loumaris_default_docker_version`: _5:18.09.6~3-0~ubuntu-bionic_