============================================
middleware_automation.keycloak Release Notes
============================================

.. contents:: Topics

This changelog describes changes after version 0.2.6.

v1.0.2
======

Minor Changes
-------------

- Make ``keycloak_admin_password`` a default with assert (was: role variable) `#26 <https://github.com/ansible-middleware/keycloak/pull/26>`_
- Simplify dependency install logic and reduce play execution time `#19 <https://github.com/ansible-middleware/keycloak/pull/19>`_

Bugfixes
--------

- Set ``keycloak_frontend_url`` default according to other defaults `#25 <https://github.com/ansible-middleware/keycloak/pull/25>`_

v1.0.1
======

Release Summary
---------------

Minor enhancements, bug and documentation fixes.


Major Changes
-------------

- Apply latest cumulative patch of RH-SSO automatically when new parameter ``keycloak_rhsso_apply_patches`` is ``true`` `#18 <https://github.com/ansible-middleware/keycloak/pull/18>`_

Minor Changes
-------------

- Clustered installs now perform database initialization on first node to avoid locking issues `#17 <https://github.com/ansible-middleware/keycloak/pull/17>`_

v1.0.0
======

Release Summary
---------------

This is the first stable release of the ``middleware_automation.keycloak`` collection.

