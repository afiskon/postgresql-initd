# postgresql-initd

PostgreSQL init.d script, mirror of http://blog.2ndquadrant.com/creating-a-postgresql-service-on-ubuntu/

Usage:

```
sudo vim /etc/init.d/postgresql
sudo chmod u+x /etc/init.d/postgresql
sudo update-rc.d postgresql defaults
sudo service postgresql start
```
