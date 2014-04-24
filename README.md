mustached-bear
==============

Clone/Fetch all openstack repos

* Keep your local OpenStack repos up to date.
* Create a separate directory for each organization
* skips stackforge repos if that aren't already cloned locally
* If repo already exists call `git fetch`

Usage
-----

Install requirements:

    $ pip -r requirements.txt

Just run in the directory where you wish to keep your repos:

    $ ./update
