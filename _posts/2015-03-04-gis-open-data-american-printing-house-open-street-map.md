---
layout: post
title: Helping the Visually Impaired Navigate Louisville Using Open Data
description: "The Civic Data Alliance has taken open GIS data from the city of Louisville and organized volunteers to load it into Open Street Map so the American Printing House can use it in their mobile app for the visually impaired."
modified: 2015-03-06
tags: [louisville,gis,aph,american printing house,open street map,hackathon,lojic]
comments: true
image:
  feature: banner-osmbuildings.png
  credit: Open Street Map
  creditlink: https://www.openstreetmap.org/#map=15/38.2361/-85.7220
---
Winter weather could not stop [CodeAcross 2015](http://www.codeforamerica.org/events/codeacross-2015/) in Louisville last Saturday, February 22nd. Dedicated volunteers braved the icy streets and converged on the  Urban Design Studio for a day of Open Streets Maps editing, in support of the American Printing House for the Blind’s ‘Nearby Explorer’ app.  Nearby Explorer is an advanced GPS solution recently released for Android smartphones by the American Printing House for the blind. The app gives the visually impaired and the blind audible cues about their immediate surroundings, and directions to places they would like to go. 

During CodeAcross, The Civic Data Alliance took newly open GIS data (precise locations of buildings and address information) from the city of Louisville and [organized](http://wiki.openstreetmap.org/wiki/Louisville,_Kentucky/Building_Outlines_Import/Contributor_Guide) volunteers to load it into Open Street Map so the American Printing House can use it to improve Nearby Explorer.

We taught volunteers how to use OSM's [Task Manager](http://tasks.openstreetmap.us/job/50) to load buildings and addresses, one neighborhood at a time, and made initial progress toward adding the data for the entire city into Open Street Maps. There is still a lot of work to be done to get all the buildings and addresses loaded, so please join us for Part 2 of the effort Saturday, March 21st at the American Printing House for the Blind. [Sign up here](http://www.meetup.com/Louisville-Civic-Data-Alliance/events/220786152/)

For this event there is actually zero programming needed.  All you need is a laptop, following written and spoken instructions, and an attention to detail.  Any other skills are just a bonus.  


**CDA Work Before the Event**

The core CDA put in about 140 volunteer hours to prep for the project and event. Here's what we did.

1. Identify the need from APH during our December meetup.
2. Work with LOJIC and Metro Louisville to add an appropriate open data license to [portal](http://portal.louisvilleky.gov/content/terms-use-accessibility-data-policy) and [FTP](ftp://ftp.lojic.org/pub/federal/) site.
3. Work with the OSM import community [mailing](https://lists.openstreetmap.org/listinfo/imports) [lists](https://lists.openstreetmap.org/listinfo/imports-us) to get approval for our import.
4. Create [OSM Wiki pages](http://wiki.openstreetmap.org/wiki/Louisville,_Kentucky/Building_Outlines_Import) that show [qualitative](http://wiki.openstreetmap.org/wiki/Louisville,_Kentucky/Building_Outlines_Import/OSMvsGISOverlapExamples) and [quantitative](http://wiki.openstreetmap.org/wiki/Louisville,_Kentucky/Building_Outlines_Import#Building_Outlines) data analysis, tagging, reconciliation plan, and user accounts process.
5. Research the best methods for importing data [properly](http://wiki.openstreetmap.org/wiki/Import/Guidelines) into OSM: [JOSM](https://josm.openstreetmap.de/), Task Manager.
6. Write a step-by-step [Contributor Guide](http://wiki.openstreetmap.org/wiki/Louisville,_Kentucky/Building_Outlines_Import/Contributor_Guide) that can volunteers can follow, showing all scenarios
7. Run geospacial analysis on the data to merge building footprints with address data.
8. Create multiple OSM import [files](https://github.com/civicdata/louisville-buildings/tree/data-bg/osm) using a [fork of existing code](https://github.com/civicdata/louisville-buildings) from NOLA's import.
9. Contact NOLA import lead to ensure our process and data is good.
10. Create a [Task Manager](http://tasks.openstreetmap.us/job/50) job after getting OSM admin access.
11. Generate a [JSON file](https://raw.githubusercontent.com/civicdata/louisville-buildings/master/blockgroups-importurl-900913.geojson) with areas of the city broken into 575 census block groups for use in Task Manager.
12. Core CDA members load some areas of the city in preparation for the event.
13. Organize, promote, and run Code Across event with our wonderful attendees!

**Outcomes**

Between February 21 and March 6, 10 people have collaboratively worked on 127 areas of the city, and validated (or invalidated) 76 of those, for an estimated 90 hours of work.

*"This is simply amazing that it shows up so quickly.   I am amazed to see the power of CDA and what a group of dedicated people can actually accomplish. It is amazing how much actually got done in one day. We can easily tell!"* - Larry at APH

*"I'm amazed! I was testing on a bus around the time the CDA added the data north of Brownsboro Rd, and when it showed up, I thought I was running the wrong build of our app. Should have checked my email before trying to confirm I was running the right build!"* - Rob at APH

[![OSM Building Import Progress](/images/screenshot-building-march7.png)](http://tasks.openstreetmap.us/job/50)

**Tweets During CodeAcross**

<blockquote class="twitter-tweet" lang="en"><p>Helping <a href="https://twitter.com/APHfortheBlind">@APHfortheBlind</a> to map Louisville, KY to assist blind pedestrians with <a href="https://twitter.com/codeforamerica">@CodeForAmerica</a> and <a href="https://twitter.com/CivicDataAlly">@CivicDataAlly</a> <a href="http://t.co/HLJejvRmcT">pic.twitter.com/HLJejvRmcT</a></p>&mdash; Dave Mattingly (@blackwyrm) <a href="https://twitter.com/blackwyrm/status/569187903739441152">February 21, 2015</a></blockquote>

Collaborating and learning how to put buildings and addresses into Open Street Map.

<blockquote class="twitter-tweet" lang="en"><p>Happy <a href="https://twitter.com/hashtag/CodeAcross?src=hash">#CodeAcross</a>! Civic hackers braved the wintry mix this morning to code for Louisville with <a href="https://twitter.com/CivicDataAlly">@CivicDataAlly</a> <a href="http://t.co/tMl29O3M5E">pic.twitter.com/tMl29O3M5E</a></p>&mdash; ladyson (@ladyson) <a href="https://twitter.com/ladyson/status/569180801256062976">February 21, 2015</a></blockquote>

Resident Open Street Map expert Jeff McAdams (has the most edits in the city) discussing the details of our building import.

<blockquote class="twitter-tweet" lang="en"><p><a href="https://twitter.com/CivicDataAlly">@CivicDataAlly</a> <a href="https://twitter.com/codeforamerica">@codeforamerica</a> Louisville KY kicks off <a href="https://twitter.com/hashtag/CodeAcross?src=hash">#CodeAcross</a> to assist <a href="https://twitter.com/APHfortheBlind">@APHfortheBlind</a> ! <a href="http://t.co/pfTgYQiEkp">pic.twitter.com/pfTgYQiEkp</a></p>&mdash; Chris Harrell (@TheHarrell) <a href="https://twitter.com/TheHarrell/status/569160729246498816">February 21, 2015</a></blockquote>

Listening to Larry Skutchan from the American Printing House talk about how the data can help his [Nearby Explorer app](https://play.google.com/store/apps/details?id=org.aph.avigenie) users.

<blockquote class="twitter-tweet" lang="en"><p>Adding all buildings/address to <a href="https://twitter.com/openstreetmap">@openstreetmap</a> Louisville for <a href="https://twitter.com/APHfortheBlind">@APHfortheBlind</a> app <a href="https://twitter.com/brianherbert">@brianherbert</a> <a href="https://twitter.com/ladyson">@ladyson</a> <a href="https://twitter.com/hashtag/codeaccross?src=hash">#codeaccross</a> <a href="http://t.co/2Q4m8Emb1F">pic.twitter.com/2Q4m8Emb1F</a></p>&mdash; Pat Smith (@CityResearch) <a href="https://twitter.com/CityResearch/status/569215416767115265">February 21, 2015</a></blockquote>

Brian Herbert from Ushahidi (middle) lending his expertise, adding mapping data to Louisville.

<blockquote class="twitter-tweet" lang="en"><p>Just made my first contribution to <a href="https://twitter.com/openstreetmap">@openstreetmap</a> ever here at <a href="https://twitter.com/hashtag/CodeAcross?src=hash">#CodeAcross</a> Louisville <a href="https://twitter.com/CivicDataAlly">@CivicDataAlly</a> <a href="http://t.co/o2dKIlyvYu">pic.twitter.com/o2dKIlyvYu</a></p>&mdash; ladyson (@ladyson) <a href="https://twitter.com/ladyson/status/569188814725488640">February 21, 2015</a></blockquote>

Lauren Dyson, Content Manager with Code for America, dropped by to lend a hand.

<script async src="//platform.twitter.com/widgets.js" charset="utf-8"></script>





**Links to more info**

- [CodeAcross](http://www.meetup.com/Louisville-Civic-Data-Alliance/events/219829803/)
- [CodeAcross 2](http://www.meetup.com/Louisville-Civic-Data-Alliance/events/220786152/)
- [CfA CodeAcross](http://www.codeforamerica.org/events/codeacross-2015/)
- [Nearby Explorer](https://play.google.com/store/apps/details?id=org.aph.avigenie)
- [Contributor Guide](http://wiki.openstreetmap.org/wiki/Louisville,_Kentucky/Building_Outlines_Import/Contributor_Guide)
- [Task Manager](http://tasks.openstreetmap.us/job/50)
- [OSM](https://www.openstreetmap.org/#map=15/38.2361/-85.7220)
- [OSM Import Data](http://wiki.openstreetmap.org/wiki/Louisville,_Kentucky/Building_Outlines_Import)
