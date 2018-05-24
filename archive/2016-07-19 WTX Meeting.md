2016-07-19 WTX Meeting
Created by Aaron Martin on Jul 19 2016 - 11:53am 
Last updated by James Colon on Sep 8 2016 - 8:44am
Printer-friendly versionPrinter-friendly version
Date and Time: July 19, 2016 - 10:00am - 11:00am
Location:  Ellison 6840
WTX Monthly Meeting

co-chairs Aaron Martin, Brian Wolf

Agenda: 
Node, Express, HTML drag and drop, jade intro by AM
Notes: 
Attendees: Gary S., Eric R., Mihoko J., Tiye B., David G., Kevin W., Shane G., Ian L., Aaron M.

Presentations:

Node, express, jade, html drag and drop (AM)
HTML5 drag and drop functionality - based on (http://www.w3schools.com/html/html5_draganddrop.asp)
JS - draggable, ondragstart, ondragover​
javascript filtering of data to avoid some inheritance side effects (able to drop elements onto other elements of same type
Basically change drop target to parent in those cases
jade (now pug) 
concise templating engine
heirarchy determined by indent (think python)
Shares some CSS syntax - "#" indicate ids and "." represents classes
can also assign attributes in a function like fashion
jade template inheritance, overriding block content in layout
discussion of production deployment (on servers)
PM2, forever, supervisor.  
could be run through nginx caching
many large, production deployments using node.  Wal-mart is mentioned.
node incredibly lean and lightweight
single threaded, but avoids extra code to handle threading
some ERI node apps demonstrated
dnsZoneDisplay shown
Ansible (https://www.ansible.com) and Vagrant (IL)
​Ansible
provisioning and setting up environment
uses "playbooks" to provide functionality
puppet can still be used for user management and IDS (protecting specific files)
Ansible Galaxy (https://galaxy.ansible.com) - lots of useful playbooks
Jeff Geerling (http://www.jeffgeerling.com) authors several of IL's favorites
Allows predicable deployment of services
Vagrant (https://www.vagrantup.com) vm deployment 
Uses VirtualBox under the hood
Files shared with host OS
Allows files to be edited by host OS editor without having to access the VM
workflow can be done variety of ways, IL uses github.
drupalvm (http://docs.drupalvm.com/en/latest/)
​​

Discussions:

UCCSC meeting (http://uccsc.ucsc.edu)
300 attendees, 100 or so new
3 UCSB speakers
Interesting talk about San Francisco replacement for their student system (equiv to UCSB "Gold").
built on swagger (http://swagger.io)
implementation, not perfect, but is so much better than previous version
vanilla bootstrap
Action Items:

none

