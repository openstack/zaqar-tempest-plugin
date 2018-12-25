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

To run all tests from this plugin, install zaqar, zaqar-tempest-plugin and
tempest into your environment, make sure to configure the tempest correctly,
and then from the tempest repo, run::

    $ tempest run --regex zaqar_tempest_plugin --config-file /etc/tempest/tempest.conf
