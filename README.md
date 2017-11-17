Role Name
=========

This role install go.cd Continous Delivery Agent

Requirements
------------

None

Role Variables
--------------

The variables that can be passed to this role and a brief description about
them are as follows:

```yaml
    go_server_hostname:   # Hostname or IP address of gocd server
    go_server_ssl:  8154  # Default ssl listen port for agents
    go_environment        # go.cd initial configured environment
```

Dependencies
------------

None

Example Playbook
----------------

Register the role in requirements.yml:

```yaml
    - src: capitanh.goagent-ansible-role
      name: goagent
```
Include it in your playbooks:

```yaml
    - hosts: servers
      roles:
      - goagent
```

License
-------

BSD

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
