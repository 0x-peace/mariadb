Role Name
=========

Installing mariadb opensource relational database.

Requirements
------------

No.

Role Variables
--------------

| Variable         | Description |
|------------------| -------------------------------------------------- |
| `mariadb_version` | default 10.3|
| `mariadb_bind_address`   | Binding address, default 127.0.0.1         |
| `mariadb_root_password` | mariadb root password, default generated    |

other variables in defautls/main.yml

Dependencies
------------

No.

Example Inventory
----------------

    [mariadb]
    192.168.10.11


Example Playbook
----------------

    - hosts: mariadb
      roles:
        - mariadb

License
-------

BSD

Author Information
------------------

An optional section for the role authors to include contact information, or a
website (HTML is not allowed).
