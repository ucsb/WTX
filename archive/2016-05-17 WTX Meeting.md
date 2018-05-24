2016-05-17 WTX Meeting
Created by Aaron Martin on Apr 19 2016 - 12:47pm 
Last updated by James Colon on Sep 6 2016 - 8:37am
Printer-friendly versionPrinter-friendly version
Location:  Library 1523
Monthly Web Technology Exchange Meeting

Chairs: Aaron Martin and Brian Wolf

Agenda: 
Administrative:

Review discussions - Approve minutes/notes from previous meeting
Future Meetings: 2016-06-21
Presentations Queue - (just the ones that people have actually said they would be willing to do) :
React.js (KW)
DrupalCon update ?? (BW)
Intro to jade templating in node.js (AM)
Modern web-dev tools (KW)
Exploration of headless drupal with angular (JW)
User friendly editing tools (BW)
Intro to mobile web app development (KW)
Creating apparent app from web-app (AM? or other)
Scheduled discussion items:
TBA
Open discussion:
Various Topics
Schedule upcoming presentations - possible topics (presenter):
Drupal 8 series (various)
More depth on paragraphs module (BW)
Front End Tools (BW)
Adaptive Theme (JW)
Wordpress Intro? (GS)
Cucumber (http://cukes.info) and Capybara (http://jnicklas.github.io/capybara/) (AM?)
More depth on multi vhost SSL unders apache (MF)
Remote Drupal Admin - (BW)
front-end developement
revision control - git
engineering has git enterprise???  May share with campus???
angular
node.js
grunt
gulp
ionic
less
dev-ops
appengine
azure (MF)
d8
mobile news feed aggregator (DS)
code reviewing software for campus?  other than AMP
heat maps - identify popular pages on your web site
crazy egg - $$$ but neat
click heat?
piwik - v2 can provide some of this (RE)
Exploration of headless drupal with Angular (JW)
Interested in use cases explorations, ideas
Front End/User based Editing tools (BW)
Intro to mobile web app development (KW)
Creating apparent apps on iOS (and others) for web based apps.
drupal features demo/howto
Notes: 
Attendees:  Aaron M., Kevin W., David G., Ian L., Elda S., Alex D., Brian W.

Discussions:

Hosting and aging infrastructure of this site
DrupalCon report by Brian:
drupal supporting big pipe, async rendering, performance
education summit: Brian working with UC level drupal cooperation
Proposing education funding model of some sort
Drupal and Acquia expressing interest
Discussion of governance concerns: board?, committee?
conversations with UCSF about HIPA/FERPA information submitted via forms in drupal
Brian working on a Drupal 8 lab framework
paragraphs module
Intro to React + Redux by Kevin:
Quick review of aspects of a web app: browser side vs server side
Demo with code review of basic react + redux application running in the browser
Being evaluated as possible system for modernizing legacy apps
React:
is rendering, view in MVC
React is not a framework, more of a library
JSX - pseudo HTML
uses components - begin with a capital letter 
lower case is straight HTML
Redux:
​​based on FLUX paradigm (as opposed to MVC)
involves unidirectional processing: Action -> Dispatcher -> Store -> View
Watched 1 minute of video at about 10:25 in of Rethinking web app development at facebook Explaining Flux
webpack/babel (via gulp) transpiles ES6 to single ES5 JS for browser
Training/Learning options:
Lynda.com
Facebook 
Redux Chrome Extension: Redux DevTools Chrome Extension
boilerplate redux: https://github.com/erikras/react-redux-universal-hot-example
​Slack channel for WTX?
Common languages for designers/marketers/developers - Atomic Design, pattern lab - (http://patternlib.io)
Ian's notes https://github.com/ilessing/ilessing.github.io/blob/master/_posts/2016-05-17%20WTX%20meeting%20n...
Kevin Wu wrote: Here are some links from my react + redux talk today:

Preamble Slidedeck http://slides.com/kevinwu-ucsb/webserver-browser-relationship#/

Greetings Source https://github.com/ginxwar/greetings-react-redux

Greetings Live App http://ginxwar.github.io/greetings-react-redux/

We also talked about how bootstrap works with react. It so happens that folks are working on this problem right now:
https://react-bootstrap.github.io/

Sources https://facebook.github.io/react/ https://facebook.github.io/flux/docs/overview.html (precursor to redux)http://redux.js.org (redux)

Redux is a portmanteau combining "reducer" + "flux" architecture pattern. At its core redux is billed as a state container for your JavaScript application. How it does this is through the "reducer composition pattern" described here http://redux.js.org/docs/basics/Reducers.html

Tons of example of shared on the Redux site, with a real world application showing how asynchronous calls are defined in your redux architecture. Redux is a super small library that one could argue that it's more of a design pattern than a library or framework.

Action Items:

none