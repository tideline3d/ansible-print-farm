Role Name
=========

Deploy and configure [Loki/Promtail](https://github.com/grafana/loki) using Ansible.

Requirements
------------

- Ansible >=  2.9

Example Playbook
------------

Install Loki and Promtail in local machine

```yml
  - hosts: servers
    roles:
        - { role: diogenxs.loki, loki_bins: ['loki', 'promtail'] }
```

License
-------

WTFPL see [LICENSE](license)

Author Information
------------------

https://diogenxs.dev