# CollectD Ansible role for CentOS/RHEL 7

Just add this repo as a git submodule to your playbook like that:
```bash
git submodule add https://github.com/rkrombho/collectd-ansible-role.git roles/collectd
```
and than use it like that in your playbook:

```yaml
#site.yml
---
- hosts: webserver
  user: root
  roles:
  - { role: collectd, graphite_host: <your_graphite_hosts> }

```

