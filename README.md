# geoip
This is a complete guide about how to set up your own geo DNS via gdnsd backend and maxmind database

Some useful links:

1) wikipedia set up about their DNS infra
https://wikitech.wikimedia.org/wiki/DNS#Installation_steps_for_a_Wikimedia_authoritative_DNS_server

Centos Installation: ( Centos has a lower inotify version and banned by gdnsd)
https://extremeshok.com/6890/centos-6-rhce-6-gdnsd-geo-dns-latest-from-source/

2) bind zone configuration file explanation in detail
https://www.centos.org/docs/5/html/Deployment_Guide-en-US/s1-bind-zone.html

3) build configuration
--disable-silent-rules  verbose build output (undo: "make V=0")

4) monit service is required for monitoring
