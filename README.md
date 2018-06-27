netbox-db
=========

Ensures that a database exists for the [NetBox](http://netbox.readthedocs.io/) application.

Role Variables
--------------

  - `netbox_database_name`: The database name
  - `netbox_database_user`: Username to connect to the database with
  - `netbox_database_password`: Password for the database user

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
        - name: netbox-db
          netbox_database_name: netbox_db_name
          netbox_database_user: username
          netbox_database_password: p@$$w0rd

License
-------

Apache 2.0
