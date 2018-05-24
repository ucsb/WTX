2017-01-17 WTX Metting
Created by Aaron Martin on Jan 17 2017 - 10:53am 
Last updated by Aaron Martin on Jan 18 2017 - 11:09am
Printer-friendly versionPrinter-friendly version
Date and Time: January 17, 2017 - 10:00am - 11:00am
Location:  6840 Ellison Hall
WTX Monthly Meeting

co-chairs Aaron Martin, Brian Wolf

Agenda: 
Co-Chair Election
Quick overview of composer/drush install of drupal 8 (AM)
d8.eri.ucsb.edu (venom)
Notes: 
Attendees: Aaron M., David G., Ian L.

Discussions:

composer/drush install of drupal 8
DG has seen some performance issues 5-10 minutes for things that seem like they should go faster
drupal 8 endpoints and issues
pathauto issue where aliases for other nodes were getting deleted because of a faulty sql match
d6-d8 migration
Lynda.com meeting a few days ago (AM)
quick summary of meeting
look into providing some reviews/testimonials/playlists from WTX
New drupal 7 library website
IL provided structure of the web service with 8 VMs:
diagrammed on board:
pair of HA Proxy servers
pair of varnish servers
pair of centos7 servers running nginx, maria and drupal 7
apache solr running in another vm
training servers (dev/stage) - training content providers
​libcal integration for hours
all code (drush core, all modules) in git repo
pull into a local dev - drush up - verify working - commit changes - push to repo - pull to live - update db
​​contracted with kwall (will be doing a site for bren as well)
optimizing drupal
reducing module count
example, replace a simple module that styles something with CSS functionality
views cache bully - by default, caches views (default is no caching, controls to activate are hidden)
logintoboggan - allows cascading login setup (ldap, then local, etc...)
pantheon workflow
how to push local dev to pantheon dev - possibly cant use rsync, git.  still scoping.  (DG)
updating large sites - test driven development
Tools available to automate testing:
Behat.org - drupal 7 behat module
jenkins
umi (?) module
RSpec
​​Requires additional time/resources.  Is it worth it for small to medium sized installs.
 