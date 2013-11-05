===
mvn
===

Formula to set up and configure Apache Maven

.. note::

    See the full `Salt Formulas installation and usage instructions
    <http://docs.saltstack.com/topics/conventions/formulas.html>`_.

Available states
================

.. contents::
    :local:

``mvn``

Downloads the tarball from the master (must exist as mvn/files/<tgz>) or downloads from the source URL if configured and installs the package. It will then configure alternatives and place /etc/profile.d/mvn.sh.  Please see the pillar.example for configuration.

Requires RedHat/CentOS 5.X or RedHat/CentOS 6.X - should also work on Debian/Ubuntu.

