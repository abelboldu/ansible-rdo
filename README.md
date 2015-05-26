rdo
=========

Ansible role to add Openstack RDO repository

Requirements
------------

RHEL or CentOS 

Role Variables
--------------

Just define openstack version codename:

    openstack_version: juno


Example Playbook
----------------


    - hosts: servers
      roles:
         - { role: abelboldu.rdo , openstack_version: kilo  }

License
-------

Apache 2.0

Author Information
------------------

Abel Boldú < abel.boldu (-) gmx.com >
