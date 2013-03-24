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

## First Day

### Talks

#### DevOps For Dinosaurs - Niek Bartholomeus 

http://vimeo.com/62491557

https://speakerdeck.com/niekbartho/devops-for-dinosaurs

* Business asks Dev to be fast in producing the software and asks Ops to be reliable in running that same software. Software delivery does not work.
* "Buy before build" rule leads to very Heterogeneous environments and focus on Integration
* Modern companies are build with automation in mind. It's in their DNA
* Change Management in Traditional Company. CMMI

#### Checking DevOps’ vital signs - John Clapham & Paul Swartout

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

#### StartOps: Growing an ops team from 1 founder - David Mytton

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

#### Adding Business Metrics - Deri Jones

* Ads have been commoditizated (both Google and Social)
* The differentiator can be the UX on your site
* Tech metrics *alongside* Business metrics
* Graph of Lost Sale: Graph of sale of typical week * outages
* Drives priorities for fixing

### Ignites

#### What if config management was created by Game Designers - @patrickdebois

http://www.slideshare.net/jedi4ever/what-ifconfigmgtwasdesignedbygamers

* Brilliant!

### Open Space

* OpenStack has won the race for standard
* Pulp for configuration management
* ZooKepper for dynamic configurations + source for static info
* GridMaster

Runny nose is ruining my evening.. 
No beer for me.. 
1.5g of paracetamol later..

## Second Day

### Talks

#### DEVOPS and the traditional enterprise IT - Thomas Falkenberg

http://vimeo.com/62330884

* The company is called payback and they have a marketing made video of what the company does. Cool! We could make one for our company too!
* ICINGA
* Mesh by common goals
* Common language
* QDOS = QA Dev Ops

#### DevOps in the Hell of a Thousand Different Platforms - Sam Eaton

http://vimeo.com/62330508

https://speakerdeck.com/sameaton/devops-in-the-hell-of-a-thousand-different-platforms

* Failcake. Failcake is a brilliant idea! blame free post mortem.
* Failcake extended itself to non tech people. This thing is powerful!
* Using the message queue as the integration point promotes transparency
* DevOps is more like Anarcho-syndicalism than Communism. (Worker self-management, Direct action, Worker solidarity)
* Deliver first. Evangelize later
* ops.failcake.net

#### How Can We Better Sell DevOps - Gene Kim 

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

### Ignites

#### Threshold Voting Workshops

http://vimeo.com/62491065

#### NoSQL and CD by @simonvc

http://www.slideshare.net/SimonVansColina/simonvc-bashonosqlinacontinuousdeliveryworld

* +1!

#### StackKicker by @simonmcc

http://vimeo.com/62491069

http://www.slideshare.net/simonmccartney/stack-kicker-devopsdayslondon2013

* "Tools I wish I had found first" slide should be mandatory on tools talks! 
* +1!

#### Using Honeyd & for testing a load balancer

http://vimeo.com/62491068

* mock the internet 
* Goooooood idea!

#### Clean Cloud Computing

http://vimeo.com/62491067

#### ZeroTurnaround - Install It Maybe

http://www.youtube.com/watch?v=oIu15zIsjQg

### Open Space

#### Improving feedback from Ops to Dev

* Have a product owner responsible from features to running to end life
* Put monetary value on downtime
* Leak pipe -> lost costumer at the stacktrace
* mesure happyness by drawing harirs on sad, happy and meh faces (simpler alternative to niko niko)

#### Dashboard for metrics

* we all use graphite
* Descartes
* Gdash is missing tests
* Graphite is moving toward decopuling the frontned from the backend
* Kibana3 has awesome dashboards & demos demo.kibana.org
* AppDynamic DynaTrace
* Metric Sampler - JMX

#### DevOps Community

* We are doing an awesome job: Talking about comunity and everyone is looking at his phone @thesamoth
* IRC - Freenode - ##infra-talk
* IRCCloud
* London DevOps (google group)
* we meet in the Forward offices
* Fosdem
* LeanIT
* Scrum
* Monitorama
* WebPerformance Meetup
* Open Tech Calendar (Scottland)
* Lanyrd
* ScaleCamp
* BarCamp London
* LunchOps
* MonkyGras, redmon, the thing organized by James Governor
* Twitter about tech
* Mary from O'Reilly
* DevOps for Developers
* Getting real
* Rework
* Lean Principles
* DevOps Angle
* The Ship Show
* Food Fight Show
* DevOps Cafe
* Floss Weekly
* Planet DevOps
* cfengine papers
* DevOps December Sysadmin Guest Posts
* QCon (or QCom?)
* DevOps Reactions

### Later at the Euston Tap

* TIMGroup is the most numerous company
* War Stories

### Final Considerations

See you at the next event, on IRC and Twitter

Long Live RSS & Atom!!
