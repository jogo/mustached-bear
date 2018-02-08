mustached-bear
==============

Clone/Fetch all openstack repos

* Keep your local not only OpenStack but also GitHub repos up to date.
* Create a separate directory for each organization
* skips stackforge repos if that aren't already cloned locally
* If repo already exists call `git fetch`

Usage
-----

Install requirements:

    $ pip -r requirements.txt

Just run in the directory where you wish to keep your repos:

    $ ./update

If you want to keep GitHub repos:

    $ ./update --repos-url "https://api.github.com/users/jogo/repos?per_page=1000"
