bbaassssiiee.sonar
=========

Sonar is a source-code quality tool.

Requirements
------------

Sonar can use either a MySQL variant, or PostgreSQL, as a database. You should select just one of these using the features.

    features:
      mysql: false
      postgresql: true


Role Variables
--------------

defaults/main.yml and vars/main.yml contain variables. Please change the sonar_password first. For advanced users the sonar_plugins might be interesting.

Dependencies
------------

dockpack.base_postgres
dockpack.base_base_java8

Example Usage
----------------

Refer to a complete build server https://github.com/bbaassssiiee/buildserver

License
-------

BSD

Author Information
------------------

Bas Meijer
@bbaassssiiee
