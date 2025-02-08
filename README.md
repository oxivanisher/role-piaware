piaware
==========
[![Ansible Lint](https://github.com/oxivanisher/role-piaware/actions/workflows/ansible-lint.yml/badge.svg)](https://github.com/oxivanisher/role-piaware/actions/workflows/ansible-lint.yml)

Setup piaware on Raspberry Pis.

Role Variables
--------------

| Name            | Comment                              | Default value                    |
|-----------------|--------------------------------------|----------------------------------|
| piaware_deb_url | The debian package location for piaware. | `https://de.flightaware.com/adsb/piaware/files/packages/pool/piaware/f/flightaware-apt-repository/flightaware-apt-repository_1.2_all.deb` |


Dependencies
------------

None

Example Playbook
----------------
```yaml
- name: Debian clients
  hosts: debian
  roles:
    - role: oxivanisher.raspberry_pi.piaware
```

License
-------

BSD

Author Information
------------------

This role is part of the [oxivanisher.raspberry_pi](https://galaxy.ansible.com/ui/repo/published/oxivanisher/raspberry_pi/) collection, and the source for that is located on [github](https://github.com/oxivanisher/collection-raspberry_pi).
