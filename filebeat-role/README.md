Filebeat role
=========

Роль для установки filebeat на хостах с ОС: Debian, Ubuntu, CentOS, RHEL.

Requirements
------------

Поддерживаются только ОС семейств debian и RHEL.

Role Variables
--------------

| Variable name | Default | Description |
|-----------------------|----------|-------------------------|
| filebeat_version | "7.14.1" | Параметр, который определяет какой версии filebeat будет установлен |


Example Playbook
----------------

    - hosts: all
      roles:
         - filebeat_role

License
-------

MIT

Author Information
------------------

JZ:ee.jzabelin@gmail.com
