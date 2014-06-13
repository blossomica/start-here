Start Here
==========

> Start where you are. Use what you have. Do what you can. 
> ~ [Arthur Ashe](http://en.wikipedia.org/wiki/Arthur_Ashe)

A Quick-start Guide for People who want to build awesome apps.

## (Start with) Why?

The world is not perfect. <br />
We have all worked somewhere we *didn't* ***love***. <br />
We have all experienced using products that had flaws. <br/>
Rather than waiting for someone else to solve our "problems" 
we are taking on the challenge ourselves.


## Who?

Who is "We"? <br />
For now we are just three people: 
[@iteles](https://twitter.com/iteles),  [@mmendes](https://github.com/mmendes999)
and 
[@nelsonic](https://twitter.com/nelsonic)

Join us in finding something you ***love*** working on.


## What?

We are building the web/mobile applications that we wish existed.

- Card App [working title]
- ideaQ [record, prioritise, share & collaborate on your ideas]
- *Your Idea Here*?


### Scratching Your Own Itch

We believe in scratching our own itches.
Scratching your own itch means solving a problem you (or someone *close* to you) *personally* have.
If you (or someone close to you) don't have any personal experience in a field 
you aren't going to do a good job of spotting/solving a problem in that area.

Read:
https://gettingreal.37signals.com/ch02_Whats_Your_Problem.php


## Web Fundamentals

### HTML5

### CSS

### JavaScript

Love it or hate it, JavaScript is Ubiquitous. Learning it well is *essential*.
[Ines](http://github.com/iteles) has prepared a great notes on
[JavaScript The Good Parts](https://github.com/iteles/Javascript-the-Good-Parts/blob/master/Notes-on-Javascript-the-Good-Parts.md)

#### Server Side = Node.js

- Download: http://nodejs.org/download/ (all platforms)
- Node.js (books): https://github.com/Pana/node-books 
- Node.js style guide: https://github.com/felixge/node-style-guide



### Testing

Testing is often left as an afterthought or ommitted completely from 
"beginner" tutorials or books. That will not be the case here.
You will learn *why* testing is not just a "nice-to-have".

### Service Oriented Architecture with (REST) APIs

We will be building our apps with RESTful 
[Service Oriented Architecture](http://en.wikipedia.org/wiki/Service-oriented_architecture)
Backend. This has *several* advantages:

1. Each piece of functionality is run as a service (so its easy to isolate, test and scale)
2. The client we build (web app or mobile app) both (independently) "consume" the same service via REST API 
(which means that the font-end is completely decoupled from the backend of the app - easier to change/itterate)
3. If our app/product gets popular we already have an API built and can allow 3rd party integration/extensions.


I'm busy preparing a *detailed* tutorial for doing exactly this using Hapi.js
at: https://github.com/nelsonic/learn-hapi
You can already get started reading it and the supporting links
And watch as the tutorial progresses.


>> Watch: https://www.youtube.com/watch?v=uDzME15UxVM (Share.js)


### Which Client MVC Framework?

- Angular.js - Mature and full-featured. 
- ~~Backbone.js~~ 
- Riot.js - Minimalist (learn it in 2h)

Right now I'm toying with the idea of using either Angular or Riot.

Ultimately we want to wrap our JS as PhoneGap app (see mobile below)
so that the app can be run as a semi-native app (download from app store,
local/offline storage, etc.) and it makes sense to keep it as small as possible.



### Which Datbase?

- Postgres - The best relational dabase for 
- MongoDB  - Good balance of features, performance and ease of use.
- CouchDB  - Great reliability, master-master replication and simplicity.

Having recently used MongoDB for a client project I'm swaying towards using it
for my next app. But I'm a huge fan of CouchDB.
We need to spend a bit of time investigating features before deciding...



## Mobile

### Phonegap

We are using PhoneGap to *rapidly prototype* "hybrid" mobile applications.

#### What is the Difference between Native and Hybrid Apps?

- Jacob Nielson explains Native vs Hybrid: 
http://www.nngroup.com/articles/mobile-native-apps
- Is Hybrid ready? http://venturebeat.com/2013/11/20/html5-vs-native-vs-hybrid-mobile-apps-3500-developers-say-all-three-please/ (the short answer is ***Yes***!)

A good (but *long*) intro tutorial to PhoneGap V.3 was recorded 
[@LXJS](http://2013.lxjs.org/guide) in October 2013: 
http://phonegap.com/blog/2013/11/12/lxjs-workshop/

