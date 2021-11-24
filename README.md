Ansible role: microk8s
=========

![main Build status](https://github.com/Provizanta/ansible-role-microk8s/actions/workflows/main.yml/badge.svg)

Install and configure a microk8s Kubernetes instance

Requirements
------------

None

Role Variables
--------------

These variables are defined in [defaults/main.yml](./defaults/main.yml):

    microk8s_addons: []

    microk8s_channel: "latest/stable"


Dependencies
------------

None

Example Playbook
----------------

    - name: Converge
      hosts: all
      roles:
        - role: ansible-role-microk8s
          vars:
            microk8s_addons:
              - dns
              - storage
            microk8s_channel: latest/stable

License
-------

MIT

Author Information
------------------

Tibor Csóka
