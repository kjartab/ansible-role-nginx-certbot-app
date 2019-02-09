Nginx-Certbot-App
=========

Setup of SPA using NGINX and Letsencrypt


Role Variables
--------------

- nginx_app_config_template
- nginx_app_webroot
- nginx_app_domain_name
- letsencrypt_email

Dependencies
------------

NGINX must be installed

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: username.rolename, x: 42 }

License
-------

MIT

Author Information
------------------

Kjartan Bjørset