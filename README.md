# openstack-project-names

A command to search and clone openstack projects.

Installation
============

    $ pip install osnames

Usage
=====

Find projects by name

    $ osnames find keystone
    openstack/keystone
    openstack/keystone-specs
    openstack/keystonemiddleware
    openstack/python-keystoneclient
    openstack/python-keystoneclient-federation
    openstack/python-keystoneclient-kerberos
    stackforge/keystone-salt-formula
    stackforge/puppet-keystone

Clone projects by name

    $ osnames --cache clone keystone
    openstack/keystone
    openstack/keystone-specs
    openstack/keystonemiddleware
    openstack/python-keystoneclient
    openstack/python-keystoneclient-federation
    openstack/python-keystoneclient-kerberos
    stackforge/keystone-salt-formula
    stackforge/puppet-keystone
    Do you want to clone all the above projects [Y/n]? y
    git clone https://git.openstack.org/openstack/keystone openstack/keystone ...
    Cloning into 'openstack/keystone'...
    remote: Counting objects: 59772, done.
    remote: Compressing objects: 100% (28402/28402), done.
    Receiving objects:  15% (9152/59772), 3.29 MiB | 131.00 KiB/s
