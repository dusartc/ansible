===================================
Prometheus.Prometheus Release Notes
===================================

.. contents:: Topics


v0.3.1
======

Bugfixes
--------

- fix: Don't log config deployments (https://github.com/prometheus-community/ansible/pull/73)
- fix: correct quotation of flags in systemd config file (https://github.com/prometheus-community/ansible/pull/71)
- fix: version bumper action (https://github.com/prometheus-community/ansible/pull/75)

v0.3.0
======

Minor Changes
-------------

- feat: Add mysqld_exporter role (https://github.com/prometheus-community/ansible/pull/45)

Bugfixes
--------

- fix: policycoreutils python package name (https://github.com/prometheus-community/ansible/pull/63)

v0.2.1
======

Bugfixes
--------

- fix: policycoreutils python package name (https://github.com/prometheus-community/ansible/pull/63)

v0.2.0
======

Minor Changes
-------------

- feat: add systemd exporter role (https://github.com/prometheus-community/ansible/pull/62)

Removed Features (previously deprecated)
----------------------------------------

- removed: community.crypto is only needed when testing (https://github.com/prometheus-community/ansible/pull/56)

Bugfixes
--------

- fix: Fix typo on Install selinux python packages for RedHat family (https://github.com/prometheus-community/ansible/pull/57)

v0.1.5
======

Bugfixes
--------

- fix: follow PEP 440 standard for supported ansible versions (https://github.com/prometheus-community/ansible/pull/46)
- fix: various role argument specs (https://github.com/prometheus-community/ansible/pull/50)

v0.1.4
======

v0.1.3
======

v0.1.2
======

v0.1.1
======

v0.1.0
======

Minor Changes
-------------

- feat: Allow grabbing binaries and checksums from a custom url/mirror (https://github.com/prometheus-community/ansible/pull/28)

Removed Features (previously deprecated)
----------------------------------------

- removed: remove lint from molecule to avoid repetition (https://github.com/prometheus-community/ansible/pull/35)

Bugfixes
--------

- fix: Force push git changelogs (https://github.com/prometheus-community/ansible/pull/36)
- fix: Remove unnecessary dependency on jmespath (https://github.com/prometheus-community/ansible/pull/22)
- fix: ansible 2.9 workaround for galaxy install from git (https://github.com/prometheus-community/ansible/pull/37)
- fix: avoid installing changelog tools when testing (https://github.com/prometheus-community/ansible/pull/34)
- fix: grab dependencies from github to avoid galaxy timeouts (https://github.com/prometheus-community/ansible/pull/33)

v0.0.3
======

v0.0.1
======

Major Changes
-------------

- Initial Release
