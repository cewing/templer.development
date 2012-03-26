Templer Development Buildout
============================

This buildout is intended to support the development of the templer system.

To run this buildout::

    $ git clone git@github.com:cewing/templer.development.git
    $ cd templer.development
    $ python bootstrap.py
    ...
    $ bin/buildout

The buildout uses mr.developer to control checkout of the templer source
packages. Once it is complete, you will have the templer command script in
bin, along with the test runner.  You can run tests with a simple::

    $ bin/test

Please ensure that test are passing before committing changes to any packages.

