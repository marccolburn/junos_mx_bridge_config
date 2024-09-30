MX Bridge Domains Configuration
=========

Configure MX Bridge Domains for Junos.

Requirements
------------


Role Variables
--------------
bridge_domains: List of Dictionaries containing MX Bridge Domains




Dependencies
------------

N/A

Example Playbook
----------------

    - hosts: all
      roles:
         - { role: junos_mx_bridge_config }

License
-------

BSD

Author Information
------------------

Marc Colburn Juniper
