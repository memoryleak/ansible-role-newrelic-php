memoryleak.newrelic-php
====================

Installs New Relic PHP APM.

Requirements
------------

None

Role Variables
--------------

See defaults/main.yml

Dependencies
------------

None

Example Playbook
----------------

    - name: memoryleak.newrelic
      newrelic_restart_php: true
      newrelic_ini_config:
        - name: newrelic.license
          value: "asdfads"

        - name: newrelic.appname
          value: "My PHP Application"

License
-------

BSD

Author Information
------------------

Haydar Ciftci <haydar.ciftci@gmail.com>