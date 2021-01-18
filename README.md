# documentation

## ubuntu 18 commands

If you really need to do a full purge and reinstall, first make sure PostgreSQL isn't running. ps -C postgres should show no results.

Now run:

apt-get --purge remove postgresql\*
