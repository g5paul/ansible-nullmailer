nullmailer
========

Configures nullmailer in Debian-like systems.

Role Variables
--------------

 * *nullmailer_remotes* - array of smarhosts (default: [ mail ])
 * *nullmailer_defaultdomain* - content of /etc/nullmailer/defaultdomain
 * *nullmailer_defaulthost* - content of /etc/nullmailer/defaulthost
 * *nullmailer_me* - content of /etc/nullmailer/me
 * *nullmailer_mailname* - content of /etc/mailname (if not defined: *ansible_fqdn*)
 * *apt_cache_valid_time* - cache ttl for apt (default: 3600)

License
-------

MIT

Author Information
------------------

Sergey Korolev (<korolev.srg@gmail.com>)
