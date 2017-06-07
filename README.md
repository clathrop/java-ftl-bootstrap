Java Freemarker Bootstrap Project

Setup:
Install postgresql with homebrew (skip the lunchy part): https://www.moncefbelyamani.com/how-to-install-postgresql-on-a-mac-with-homebrew-and-lunchy/

Startup the postgresql db with 

pg_ctl -D /usr/local/var/postgres -l logfile start

run - mvn clean install

TODO:

currently build failing, need to create postgres role and dbs i'm sure

