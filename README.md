# README - Groundwork Statics

---------------------------------

The purpose of this project is to provide a starting point for webapps. While
we do install Ruby, Node.js, and PostgreSQL, this is primarily geared towards
static web apps (Ruby is there in case you want to use sass/compass, node is
there to install bower, yeoman, etc). Apache is installed as well so you just
need to go to http://10.10.10.10 (the directory for that application would
go into application/html).

For installation/getting started, read INSTALL.md.

NOTE: If you are running ubuntu, there is an issue with Apache not installing. The current workaround is to remove apache from ansible/site.yml and once you vagrant ssh into the server, you can have grunt start up a web server by running (inside your application directory):

```
  grunt serve
```
