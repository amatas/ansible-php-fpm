PHP-fpm
=======

Installs and configures a PHP-fpm service.

Requirements
------------

- The application is self-contained as it use a sqlite database at the moment.

Role Variables
--------------

- Take a look to [defaults file](defaults/main.yml)

Dependencies
------------

- None dependencies so far.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    ---
    
    - hosts: all
      sudo: true
    
      roles:
        - php-fpm

License
-------

MIT.

Author Information
------------------
