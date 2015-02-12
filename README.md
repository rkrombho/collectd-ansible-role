# CollectD Ansible role for CentOS/RHEL 7

example usage:

```yaml
#site.yml
---
- hosts: webserver
  user: root
  roles:
  - { role: collectd, graphite_host: <your_graphite_hosts> }

```

