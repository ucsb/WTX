# 2017-10-17 WTX Meeting
## Created by Aaron Martin on Oct 16 2017 - 1:09pm 
## Last updated by Aaron Martin on Oct 17 2017 - 2:18pm
## Date and Time: October 17, 2017 - 10:00am - 11:00am
## Location:  6840 Ellison Hall
## Monthly WTX Meeting
## co-chairs: Aaron Martin, Brian Wolf

## Agenda: 
## Demos:

* CSS debugging (KW)
* Webpack (KW)
* Babel (time/energy permitting) (KW)
## Notes: 
### Attendees: Aaron M., Kevin W., Gary S., Eric R., Denise S., David G., Guylene G., Ian L., Mihoko J.

## Demos:

* CSS Debugging (KW)
* Nice tutorials at google developer site - developers.google.com - "Get Started with Viewing and Changing CSS"
* strikethrough - applied, but overridden by a more specific rule
* can modify/create rules on the fly
* same with html, can add classes etc on the fly.
* there is a way to setup a local directory to save changes to so that progress is not lost console 
```
$0 last element
$1 previous element (etc)
$0.getComputedStyle()
$x('//p')  #  grabs all <p>
$$('p')   # similar, but slightly different functionality
```
* elements -> styles -> computed
* breadcrumbs
* computed pane, allows you to dial into specific rule that causes that computed value 
* chrome -> canary as firefox -> firefox developer
* Webpack (KW)
  * new features allow it to provide some task running functions (ie: gulp, grunt, brocolli)
  * webpack --watch --progress)
  * webpack.js.conf
  * npm install webpack --save
  * node_modules/.bin/webpack --watch --progress
  * various cool options to set up env vars, etc...   --env.env
  * can add scripts that call various webpack commands
  * npm run dev
* Babel (KW)
  * .babelrc
  * Babel site has a scaffolding setup to provide templates for various goodies
  * npm install babel --save
  * node_modules/.bin/babel index.js --out-file output.js
  * compatibility chart at: 
* https://kangax.github.io/compat-table/es6/
