ImageMagick Ansilb Role
=========

Install ImageMagick from source

Requirements
------------

None.

Role Variables
--------------

```
imagemagick_version: "7.0.7-23"

imagemagick_configure_options: ""
imagemagick_install_path: "/opt/imagemagick"

imagemagick_optional_dependencies: []
```

Dependencies
------------

None.

Example Playbook
----------------

```
- hosts: servers
  roles:
    - { role: cimon-io.imagemagick, imagemagick_version: '7.0.7-23' }
```

License
-------

MIT
