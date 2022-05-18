Filebeat-role
=========

Роль для установки Filebeat

Requirements
------------

Для ОС семейств debian и EL

Role Variables
--------------

|       vars       |          description          |
|:----------------:|:-----------------------------:|
| filebeat_version | Версия Filebeat для установки |


Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: filebeat-role }

License
-------

BSD

Author Information
------------------

Anna M
