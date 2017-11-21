MDSS
====

This role only supports the `Full` installation set.

A list of models to manage needs to be specified in `mdss_install_model`, there is no default.

Requirements
------------
See `meta/main.yml`.

Role Variables
--------------
See `defaults/main.yml` for all options.

Dependencies
------------
None.

Example Playbook
----------------
Example:
```
- hosts: server
  roles:
    - mdss
```

TODO
----
- Support other installation sets
- Improve documentation

Licence
-------
Released under the [MIT license](https://opensource.org/licenses/MIT).

Author Information
------------------
Luis Gracia while at [The Rockefeller University](https://www.rockefeller.edu):
- lgracia [at] rockefeller.edu
- GitHub at [luisico](https://github.com/luisico)
- Galaxy at [luisico](https://galaxy.ansible.com/luisico)
