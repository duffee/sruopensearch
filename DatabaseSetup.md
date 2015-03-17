# Introduction #

Expanding on the notes for creating the mysql database


# Details #

Have a look in "support/mysql scripts" for the sql scripts that will create the tables.
(NB. capitalized terms are replaced with whatever is in db.php

In mysql:
  * create database dbname SEARCH\_TERMS\_DB;
  * use SEARCH\_TERMS\_DB;
  * source PATH/support/mysql scripts/search\_terms.sql;
and do the same for the EMAIL\_DB

create a user to access the databases and grant the privileges
  * create user 'DB\_USER'@'DB\_SERVER' identified by 'DB\_PASSWORD';
  * grant all on SEARCH\_TERMS\_DB.`*` to 'DB\_USER'@'DB\_SERVER';
  * grant all on EMAIL\_DB.`*` to 'DB\_USER'@'DB\_SERVER';