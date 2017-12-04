====================
Zaqar Tempest Plugin
====================

Tempest plugin for Zaqar project.

It contains the tempest plugin for the functional testing of Zaqar Project.

* Free software: Apache license
* Documentation: http://docs.openstack.org/developer/zaqar
* Source: http://git.openstack.org/cgit/openstack/zaqar-tempest-plugin
* Bugs: http://bugs.launchpad.net/zaqar

Running the tests
-----------------

To run all tests from this plugin, install Zaqar into your environment
and from the tempest repo, run::

    $ tox -e all-plugin -- zaqar_tempest_tests

To run all tempest tests including this plugin, run::

    $ tox -e all-plugin
