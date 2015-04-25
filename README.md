hate10-contentutopia
====================

Small web application to generate JSON substitution lists for the [FoxReplace
Firefox add-on](https://addons.mozilla.org/de/firefox/addon/foxreplace/).
Quickly produced for a friend to use at [#hate10](http://hate10.com).

Setup
-----

    git clone https://github.com/nning/hate10-contentutopia.git
    cd hate10-contentutopia
    bundle
    rake db:migrate

Startup
-------

    rails s -b ::

Reset Substitutions
-------------------

    rake substitutions:reset
