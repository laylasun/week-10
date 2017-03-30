***Really sorry for the late submission! I have gone through something very unexpected
and tiring ever since I came back from spring break. All I hope right now is to graduate
(so that I can continue dealing with all these issues...)...Sorry again...***
# Final Project Proposal

Your assignment this week is to write a detailed proposal for your final
project. In proposing your final, try to address each of the following
areas.

## Problem / Question

Applications are ultimately just tools. What problem or question does
your application attempt to resolve or grapple with? How does your
application speak to this problem/question?

This won't be a highly interactive app but more like a storyboard with more information.
I do not like the inaccuracy of the Mapzen search results; so, I try to avoid things involving
searh functions...

I really like the philly-building-benchmarking example and want to do something similar in format
but with different sets of information on philly.

All the information will be focused on the potential sites for Amazon Go store when it comes to Philly.
Hence, info comparison can be taken place in census tract levels or/and neighborhood level. This project
will be done together with the one for data-viz class and will be also used as a web app for my capstone
project whose final delivery will be a paper.

## The data

Geospatial applications are all about working with data. What datasets
would you plan/like to use? If the data you'll be working with isn't
already stored in a way that you can use, how will you be storing your data?

All data that I can get from OpenData Philly and some from the other class,
such as retailers in philly. Also, there will be some web-map data scraping
(most likely manually from ArcMap online since i have no ArcPro account).

Potentially, there will be a lot of conversions of datasets into geojson files;
so, I would choose geojson datasets rather than creating such files by myself; when
necessary, I have to use R to add fields onto the geojson datasets. But, this is more
about whether I should use Carto to do the analysis online or to use R to do the analysis first and then
plot the pre-processed outcomes right onto the maps (method with R is more for D3 data-viz).


## Technologies used

Which technologies covered in class (or discovered on your own!) do you
plan to use? How do you anticipate using each of these technologies?
Review the APIs/online examples of leaflet, turf, jQuery, underscore (or
any library not explicitly covered in class) for functions/uses which
you'd like to explore. Briefly describe how you might use them.

leaflet and more plugins, jQuery, underscore, D3,
Carto (if not loading forever when dealing with large database),
maybe not bootstrap since I dislike the rounding on corners

## Design spec

#### User experience

At a high level, how do you expect people to use your application?
- Who are the users? - people who are interested in Amazon Go stores
- What do they gain from your application' use? - info on possible locations of AmazonGo stores in philly
- Are there any website/application examples in the wild to which you can compare your final?
  - http://visualization.phillybuildingbenchmarking.com/#/map

#### Layouts and visual design

So far, we've built all our applications with a side bar for
representing non-map content and navigation. This is not the only
successful design. Extra content could be displayed in a top bar,
through modals, through side bars on both sides, and any combination of
these as well as a number not mentioned. Try to describe your
application's visual layout. Conceptually (no need for extensive CSS
here), what will this design require?

very similar to http://visualization.phillybuildingbenchmarking.com/#/map ...

## Anticipated difficulties

Thinking about weaknesses can be useful. What do you anticipate being
most difficult about this project? How will you attempt to cope with
these difficulties? For example, asynchronous behavior (ajax, events)
are hard to use and think about. Global variables are a strategy for
coping with that difficulty by breaking data out of the asynchronous
context.

The logic of the story (my analysis);
Difficulty on dataset conversions;
The amount of time needed to combine D3 and all other techs into the app.

## Missing pieces

We've only managed to scratch the surface of the available technologies
by which you could construct an application. What use-cases haven't we covered
that you think would be useful? What technologies not covered seem exciting to
you (you don't necessarily have to fully understand what they're for,
this is a chance for you to get our help interpreting a technology's
purpose/usage).

how to easily edit/manipulate geojson files.
