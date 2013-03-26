# Notes from DevOpsDays London

I'm mostly a developer but with also a system administration background

I was on lease to the infra team (devops) when the DevOpsDays were happening here in London - I'm such a lucky guy!

So I went there and took ~20 pages of notes (I write in large and leave a lot of white lines)

The following is a raw, unfiltered, report of what happened to me at DevOpsDays London. As a transcript of my notes.

## My "Ah ha!" Moment

@KrisBuytaert "The people in this room are the 1% , we live in a paralellel fantasy world of how things should be . @realgenekim #devopsdays"

## Best giveaway

Signed copy of "The Phoenix Project" thanks to bmcsoftware http://www.bmc.com/

## General Links

* http://vimeo.com/album/2312414

## Talks

### DevOps For Dinosaurs - Niek Bartholomeus

http://vimeo.com/62491557

https://speakerdeck.com/niekbartho/devops-for-dinosaurs

* Business asks Dev to be fast in producing the software and asks Ops to be reliable in running that same software. Software delivery does not work.
* "Buy before build" rule leads to very Heterogeneous environments and focus on Integration
* Modern companies are build with automation in mind. It's in their DNA
* Change Management in Traditional Company. CMMI

### Checking DevOps’ vital signs - John Clapham & Paul Swartout

They want metrics for the company culture to see if DevOps is working

* Organizational Health Index - Expansive
* Agile & Scrum check-lists
* Beliefs -> Attitude & Values -> Behaviour
* Behaviours are measurable (even if they are just a consequence)
* Make life less miserable (objective of DevOps)
* KPI: Dev Cycle Time (Story to Production)
* Shared purpose
* Motivation
* Collaboration
* Effectiveness
* How to collect the data?
  * Interview
  * Questionnaire (they have chosen this)
  * Raw Data
  * Spying
* Data > Opinions
* Opinions matched Data

### StartOps: Growing an ops team from 1 founder - David Mytton

How to apply DevOps even if you are a start-up, without huge cash and not based in Frisco

http://blog.serverdensity.com/growing-an-ops-team-from-1-founder/

* Server Density, we make a dashboard for MongoDB
* Instead of documentation: Failure scenario. Write washing machine style issue resolution guide for your systems
* Every manual process should have a check-list
* Uptime reporting
* Detailed external (and internal) communication in case of outages. Think Heroku status pages
* Simulated outages
* HipChat
* serverdensity.com/dd
* Migrated from Bamboo to Travis to avoid wasting time managing internal services

### Adding Business Metrics - Deri Jones

* Ads have been commoditizated (both Google and Social)
* The differentiator can be the UX on your site
* Tech metrics *alongside* Business metrics
* Graph of Lost Sale: Graph of sale of typical week * outages
* Drives priorities for fixing

### DEVOPS and the traditional enterprise IT - Thomas Falkenberg

http://vimeo.com/62330884

* The company is called payback and they have a marketing made video of what the company does. Cool! We could make one for our company too!
* ICINGA
* Mesh by common goals
* Common language
* QDOS = QA Dev Ops

### DevOps in the Hell of a Thousand Different Platforms - Sam Eaton

http://vimeo.com/62330508

https://speakerdeck.com/sameaton/devops-in-the-hell-of-a-thousand-different-platforms

* Failcake. Failcake is a brilliant idea! blame free post mortem.
* Failcake extended itself to non tech people. This thing is powerful!
* Using the message queue as the integration point promotes transparency
* DevOps is more like Anarcho-syndicalism than Communism. (Worker self-management, Direct action, Worker solidarity)
* Deliver first. Evangelize later
* ops.failcake.net

### How Can We Better Sell DevOps - Gene Kim

http://vimeo.com/62491066

http://www.slideshare.net/realgenekim/how-can-we-better-sell-devops

* DevOps helps the Business
* We know how to fix it not how to make another (system/server)
* Failure & Powerless
* Stories
* Burnout in IT is worse than first response and military (Can't find the source. http://www.secburnout.org/ maybe?)
* You are bringing the stress home
* Cost of IT failure: 3T$/year
* The Goal -> The Phoenix Project
* Storytelling
* DevOps Cookbook
* Slide of the downward spiral & find your business problem

## Ignites

### Threshold Voting Workshops

http://vimeo.com/62491065

### NoSQL and CD by @simonvc

http://www.slideshare.net/SimonVansColina/simonvc-bashonosqlinacontinuousdeliveryworld

* +1!

### StackKicker by @simonmcc

http://vimeo.com/62491069

http://www.slideshare.net/simonmccartney/stack-kicker-devopsdayslondon2013

* "Tools I wish I had found first" slide should be mandatory on tools talks!
* +1!

### Using Honeyd & for testing a load balancer

http://vimeo.com/62491068

* mock the internet
* Goooooood idea!

### Clean Cloud Computing

http://vimeo.com/62491067

### ZeroTurnaround - Install It Maybe

http://www.youtube.com/watch?v=oIu15zIsjQg

### What if config management was created by Game Designers - @patrickdebois

http://www.slideshare.net/jedi4ever/what-ifconfigmgtwasdesignedbygamers

* Brilliant!

## Open Space

* OpenStack has won the race for standard
* Pulp for configuration management
* ZooKepper for dynamic configurations + source for static info
* GridMaster

### Improving feedback from Ops to Dev

* Have a product owner responsible from features to running to end life
* Put monetary value on downtime
* Leak pipe -> lost costumer at the stacktrace
* mesure happyness by drawing harirs on sad, happy and meh faces (simpler alternative to niko niko)

### Dashboard for metrics

* we all use graphite
* Descartes
* Gdash is missing tests
* Graphite is moving toward decopuling the frontned from the backend
* Kibana3 has awesome dashboards & demos demo.kibana.org
* AppDynamic DynaTrace
* Metric Sampler - JMX

### DevOps Community

We are doing an awesome job: Talking about comunity and everyone is looking at his phone -- @thesamoth

* Tools
  * IRC
    * Freenode
      * ##infra-talk
    * IRC Cloud https://www.irccloud.com/
  * Twitter
    * Twit about the tech you use
  * LdnDevOps Google Group https://groups.google.com/forum/?fromgroups=#!forum/london-devops
    * we meet in the Forward offices http://forwardtechnology.co.uk/events
* People
  * Mary Rotman/Thengvall Community Manager @ O'Reilly https://twitter.com/mary_grace
* Sites
  * DevOps December Sysadmin Guest Posts https://puppetlabs.com/blog/looking-back-at-devops-december/
  * DevOps Reactions http://devopsreactions.tumblr.com/
  * cfengine author's papers http://cfengine.com/markburgess/index.html
  * Planet DevOps http://www.planetdevops.net/
  * DevOps Angle http://www.devopsangle.com/
  * Open Tech Calendar http://opentechcalendar.co.uk
* Podcasts
  * Floss Weekly http://twit.tv/show/floss-weekly
  * DevOps Cafe http://devopscafe.org/
  * Food Fight Show http://foodfightshow.org/
  * The Ship Show http://theshipshow.com/
* Books
  * Lean Principles - not sure
  * DevOps for Developers https://www.google.co.uk/shopping/product/1712181197592230257
  * Getting real https://www.google.co.uk/shopping/product/9515751910094167853
  * Rework https://www.google.co.uk/shopping/product/2753713951273839343
* Conferences/Events
  * Find conferences with Lanyrd http://lanyrd.com/
  * QCon http://qconlondon.com/
  * MonkiGras http://monkigras.com/
  * LunchOps https://groups.google.com/forum/?fromgroups=#!topicsearchin/london-devops/subject:LunchOps
  * BarCamp London http://barcamplondon.org/
  * ScaleCamp http://www.scalecamp.org.uk/
  * WebPerformance Meetup http://www.meetup.com/London-Web-Performance-Group/
  * Monitorama http://monitorama.com/
  * Fosdem https://fosdem.org/
* Other
  * Lean IT http://en.wikipedia.org/wiki/Lean_IT

## Later at the Euston Tap

* TIMGroup is the most numerous company
* War Stories

## Final words

See you at the next event, on IRC and Twitter

Long Live RSS & Atom!!
