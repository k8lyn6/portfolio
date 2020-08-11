---
layout: page
title: "Mapping Leo Sarkisian's Field Recordings"
date: Posted March 19, 2017
img: /img/mtiamap.png
---
<br/>
# Challenges in mapping
<br/>
As we move through different digital humanities tools and methods in this class, I have seen a few themes emerge across the discipline. First is the theme of scholarly review. We have discussed the need for more avenues of (and just more, in general) reviewing and critiquing digital humanities scholarship. We have talked about digital means of publication and communication (such as Twitter and blogs) that allow scholars to share ideas and scholarship while inviting feedback. However, many digital humanities methods rely on those critiquing to understand the methods to be able to provide helpful and solid criticism. Scholars must also be willing and able to provide their methods within their scholarship for others to review. Both of these seem to be challenges within the field.

The second theme I have observed is reuse. While exploring digital humanities projects that have used GIS mapping tools, I noticed that very few of the projects shared the data they used to create the maps. Not only does this make it difficult for others to critique the methodology, it makes it impossible for other scholars to build upon others' scholarship. Though some projects provided references from which they gathered their data, it would be extremely time consuming to replicate the collection process. If more scholars shared their data, others could build upon their work rather than having isolated instances of digital humanities methodology scattered and isolated throughout disciplines.

I see both of these themes emerge within mapping. Though maps are used in many other disciplines, scholars within history may be unfamiliar with mapping methodologies and tools. One problem I saw when reading about projects that used mapping technologies was that the maps did not always seem to serve a useful purpose within the argument. Whether in a blog post, a paper, or a book, scholars should clearly articulate why they chose to use a map, how they made the map, and how it is being used. They should distinguish between methodological arguments and contributions to their field. When possible, scholars should also share their data so that others can continue to contribute to the arguments and ideas they have presented. Tenure review committees could also recognize these efforts to share data as contributions to scholarship, so that scholars have more incentive to share their data.
<br/>
<br/>
# My mapping endeavors
<br/>
Since I am an information student and not a history student, I do not have research of my own. With Paul Conway's permission, I decided to use data from the *Music Time in Africa* NEH grant project that I am working on to learn how to use QGIS (for more information about the grant project, visit [the website](http://mtia.sites.uofmhosting.net/)). We have digitized and are building an access system for over 900 of Voice of America's broadcasts of the radio program. The collection also includes many reels of Leo Sarkisian's live field recordings used as part of *Music Time in Africa* broadcasts. Leo Sarkisian, the creator and long-time writer of the program, spent years traveling around Africa recording popular and up-and-coming musicians representing popular and traditional genres within each country. Another research student put together a spreadsheet with data about Leo's field recordings that I thought could be useful for mapping.

<div class="img_row">
	<img class="col three" src="/img/field-recording-screenshot.png" alt="Spreadsheet of field recording data" title="Field Recording Data"/>
</div>
<div class="col three caption">
	A screenshot of the field recording spreadsheet
</div>
<br/>
<br/>
When I first set out on my mapping endeavor, I knew that my data would relate to countries in Africa, although I was unsure what other data I would be using. I started out by searching for a shapefile of the continent that included country borders. I immediately ran into some issues as I searched. I first explored a [LibGuide from Northwestern](http://libguides.northwestern.edu/c.php?g=115072&p=749535) that provided resources for shapefiles and data for GIPS projects hoping to come across a useful map of Africa. However, three of the four links within the Africa section were broken.

Another quick google search eventually led me to a [shapefile from the ArcGIS website](https://www.arcgis.com/home/item.html?id=16da193d9bcd4ae0b74febe39730658a). When I opened the shapefile in QGIS, it proved to be a good enough map for my learning purposes. As I played around with some of my data, however, I realized that this shapefile might be too modern for my needs. Leo's recordings span from the mid 1960s to XXXX. However, I had difficulty finding a shapefile that better met my needs, and since I do not know how to create one myself, I had to make do with what I could find. I also felt slightly uncomfortable that I was using map data that I did not feel qualified to evaluate myself. The site contained no information about the shapefile, and I am not experienced enough to know whether it was made well. I had to trust something I did not fully understand, which would have produced major methodological issues if I had not simply been exploring.

I followed [Fred Gibbs' tutorial on using QGIS](http://fredgibbs.net/tutorials/) and started playing around with the field recording data. I added up all of the tracks listed per country and created a simple spreadsheet that I saved as a CSV to upload into QGIS. I then associated the country column in my own spreadsheet with the country column in the shapefile spreadsheet and properly styled the data. Though many of the countries showed colors according to how many tracks of music we had, I noticed that a lot of the countries were missing colors and borders. I opened the spreadsheet again and realized that the two spreadsheets used different names for the same countries, so they were not associated with each other. I went back and cleaned up my spreadsheet for consistency of names and tried again. This time, all of the countries had the proper borders and colors.
<br/>
<br/>
# Reflections on the field recording map
<br/>
<div class="img_row">
	<img class="col three" src="/img/mtiamap.png" alt="Map of Africa with countries highlighted based on number of field recordings" title="Number of field recording tracks per country"/>
</div>
<div class="col three caption">
	Map of the number of Leo Sarkisian field recordings by country
</div>
<br/>
<br/>
I created this map primarily for my own educational purposes, but also to explore our data for the *Music Time in Africa* project. Once we have digitized and cataloged all of the broadcasts we have, we hope to be able to cross reference musical inserts from individual programs with Leo's original field recordings to understand how those field recordings were used throughout the show. This map provides a first step to visualizing what field recordings we have. Though it shows data we could have explored ourselves via the spreadsheet, I did find it helpful to see it connected to the geography rather than just the country name. At the height of his sound recording career, Leo lived in Guinea Bissau, and the Voice of America's African headquarters and recording studio were located in Monrovia, Liberia. This map shows that much of the collection is associated with countries in that western heel of the continent. This realization is not a major one, but it does help us as archivists to understand our collection a little bit better and provides us room to further explore the connections between the primary source materials and the radio programs within the collection.
