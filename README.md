OpsView Agent Role
=========

Ansible role to install and configure OpsView agent on Linux and Windows hosts.

Requirements
------------

None

Role Variables
--------------

- opsview_server_ip: # OpsView Server IP Address (Required)
- snmpd_community: " SNMPD Community String (Optional)

Dependencies
------------

- libyanspider.firewall_ansible_role

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

```yaml
    - hosts: servers
      roles:
         - { role: libyanspider.opsview_agent_role, opsview_server_ip: 127.0.0.1, snmpd_community: public}
```

License
-------

BSD

Author Information
------------------

Ahmed Shibani (#shumbashi)
sheipani@gmail.com