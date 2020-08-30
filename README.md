Role Name
=========

Role to install Graylog-Sidecar replacing Collector-Sidecar

Requirements
------------

None

Role Variables
--------------

The role accepts two variables:
- server_url: This is Graylog API URL
- server_api_token: This is Graylog API Token

Dependencies
------------

- None

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: graylog-sidecar-ansible-role, graylog_url: https://graylog.server/api/, graylog_api_token: "SECRETTOKEN" }

License
-------

BSD

Author Information
------------------

Ahmed Shibani
sheipani@gmail.com