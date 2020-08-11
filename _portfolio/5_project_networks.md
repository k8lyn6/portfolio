---
layout: page
title: "Visualizing the Network of the Battle of Hogwarts"
description: Posted April 8, 2017
update: Updated April 21, 2017
img: /img/network-post.png
---
<br/>
# Choosing a topic
<br>
This week's challenge was to demonstrate an example of network analysis in our research. Since I'm an aspiring librarian with no real subject research interests, I've been trying to use data from *Music Time in Africa*, the archival project I'm currently working on.

However, I thought and thought about how I could apply a network analysis to MTIA. Ultimately, at least for the stage we're at now, I came up with nothing that would be useful or feasible for a network graph. I could have just used the data provided in the [Programming Historian's tutorial](http://programminghistorian.org/lessons/creating-network-diagrams-from-historical-sources) for creating data for a network analysis, but I wanted to practice thinking about what kind of data would be necessary for a network analysis and to try to conceptualize an idea through nodes and edges.

I thought to myself, "what's some fun data I could collect that represents connections between people?" The answer: spells cast during the epic Battle of Hogwarts in *Harry Potter and the Deathly Hallows*.
<br/>
<br/>
# My data collection process
<br/>
I'll admit upfront that my data collection was not perfect or thorough, as my main goal was to collect a small set of data to play with rather than come up with interesting conclusions. To gather the data, I read through the two chapters of HP7 that described battle scenes. Every time a spell was mentioned, either by name or by incantation, I recorded the following in a spreadsheet:
- who cast the spell
- who was impacted by the spell (created multiple rows if more than one person was impacted)
- which side each person was on (Death Eaters or Hogwarts)
- the incantation of the spell (if unknown, wrote unknown)
- whether the spell was offensive or defensive
- whether the spell hit its mark

Honestly, I was winging it when it came to decisions about what data to record. I was thinking about things I could possibly care about in a network graph. This information provided the basics of my data spreadsheet, but in hindsight, I wish I had recorded the page number of each so I could go back and look at some of the data after the fact. Some of the data I collected ended up not being useful, and other parts I wish I had collected better.
<br/>
<br/>
# Creating the graphs
<br/>
Once I had the spreadsheet, I followed the basic instructions in Palladio to create the network graph. I quickly realized how many errors I had made collecting data. Even though the Programming Historian gave some good tips for collecting data, I still messed some things up. First, my names weren't standardized. Then, I realized that especially for Gephi, I probably should have coded my data using integers rather than strings. I also had to separate my data into nodes and edges for Gephi. [The spreadsheet I ended up using for Gephi](https://docs.google.com/spreadsheets/d/1TjwKxdYzM2_wsfYLCfNDpdAahVcmOdB8G1P51jFb6iY/edit?usp=sharing) looked very different than the original one I created.

Creating the graph in Palladio was pretty straightforward. It didn't appear that there were as many options to change the different settings as there were with Gephi. Palladio did provide a good first visualization of my data. I adjusted the node sizes based on the number of spells cast, but that was the only real change I made.

<div class="img_row">
	<img class="col three" src="/img/network-post/palladio.png" alt="Network graph of Harry Potter characters" title="Palladio network graph"/>
</div>
<div class="col three caption">
	Network graph created with Palladio
</div>
<br/>
<br/>

However, I was interested in seeing how I could incorporate directionality in the graph, as I thought it was important to show the direction of spells cast between people. I moved over to Gephi, but I quickly became overwhelmed by the number of things I could change on the graph. I used Martin Granjean's [tutorial](http://www.martingrandjean.ch/gephi-introduction/) to explore the kinds of things I could change.

I ended up changing the color of the nodes based on whether the person was a Death Eater or a Hogwarts fighter. I also added arrows and changed the size based on their ranking. However, I felt like I was just messing around with the different settings rather than changing them methodically.

<div class="img_row">
	<img class="col three" src="/img/network-post/gephi.png" alt="Network graph of Harry Potter characters" title="Gephi network graph"/>
</div>
<div class="col three caption">
	Network graph created with Gephi
</div>
<br/>
<br/>

# Reflections
<br/>
I'm not sure that these graphs showed me anything particularly noteworthy from a scholarly point of view. The data collection gave me the opportunity to think about what kind of information might be useful for a network graph. I also realized that a lot of the spells and the people impacted weren't actually described in the two chapters. Since the book is written from Harry's perspective, it makes sense that Harry is a major focal point for the graph.

I think I came out of this exercise with more questions than answers in terms of methodology. There's a lot I  I'll need to learn about methods and theories and terminology of network diagramming before I can fully understand how to critique and create network graphs. I had a hard time wrapping my head around the concept of nodes and edges, but now that I've done it once, I feel like I have a slightly better understanding.
