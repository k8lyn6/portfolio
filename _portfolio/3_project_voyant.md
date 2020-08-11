---
layout: page
title: Text Mining the Music Time in Africa scripts
date: Posted March 16, 2017
img: /img/voyanticon.png

---
<br/>
# The value of Voyant for *Music Time in Africa*
<br/>
In my [previous digital humanities class](http://ricedh.github.io/), my classmates and I collaboratively worked on a project involving runaway slave advertisements in Texas newspapers. We each had the opportunity to work extensively with a particular DH tool. My group used Palladio to map locations mentioned in jailer's notices, but I got to hear from another group who used Voyant to analyze our corpus of advertisements. The Voyant group pointed out in their write up that Voyant was helpful because runaway slave advertisements tend to follow the same patterns of writing and format, <strong>which makes it difficult to do close readings because everything looks very similar.</strong>

I thought that using Voyant to do a distance reading of some of the *Music Time in Africa* scripts might be helpful for the same reasons. Each script has a very similar format and follows a standard flow through the program with similar words and phrases. Once you get to know this flow, it can be easy to scan and pick out key phrases, but it is quite time consuming and not always accurate. Unlike some scholars, who may be able to learn something concrete using Voyant and make arguments with the data, I hoped to use Voyant to explore what might be possible to learn from our collection of scripts.

In particular, **I hoped to see how Voyant could help us identify unique scripts or identify what a particular script might be about.** Currently, we are choosing around thirty *Music Time in Africa* programs as an initial test bed for our access system. We wanted to identify scripts that represented particular gems in the collection, as well as distinctive and unique programs that show the value of the collection.

Because we have not digitized the scripts, run OCR, and cleaned them yet (that's what we'll be doing with these thirty!), one of our principle investigators went through the hundreds of the scripts by hand and skimmed them for important information. She marked ones that she thought would be good candidates with a small post it note with a one or two word description. Overall, she identified around 150 candidates, which we then narrowed down to thirty simply by looking at the one word descriptions.

She was able to complete this rather quickly, and her domain knowledge was useful in this endeavor. However, in the future, this is not the most efficient way to take a broad look at the subjects of the programs.
<br/>
<br/>
# Methods and process
<br/>
I started by creating a corpus of five scripts to run through Voyant. I chose the five scripts I have been using extensively for my OCR study because I have read these scripts many times and have gotten quite familiar with them. Since I know how time consuming it can be to clean OCR, I hand typed the scripts for the sake of time. I included the markers in the script, such as "VOICE:" and "MUSIC CUT," though I later wish I had taken these out. I saved each script in a separate .txt file within the same folder. I named each document by its date in ISO format.

I then uploaded the five .txt files to Voyant and evaluated my results overall. From the beginning, **it was clear that I would need a specific set of stop words** -- obviously, the scripts contain many instances of the words "music," "time," and "Africa," but I already knew that. I created another .txt file to keep track of the stop words I used, since Voyant does not save any of this information between sessions. I made a list of common stop words and appended a few of my own ("music," "time," "Africa," "voice," and "cut").

<div class="img_row">
	<img class="col three" src="/img/voyant-post/first-wordcloud.png" alt="Word cloud of Musc Time in Africa most used words" title="MTiA Word Cloud"/>
</div>
<div class="col three caption">
	Voyant's first word cloud, without stop words
</div>
<br/>
<br/>

With these new results, I set to work exploring each tool within Voyant.
<br/>
<br/>
# "More grease to your elbows, friends"
<br/>
One thing that immediately struck me after I removed the stop words was how large the word "friends" was in the new word cloud. Leo Sarkisian, the creator and writer of the show for the majority of our collection, was extremely interested in developing and maintaining the show's fan base. Every week, he would answer all of the fan mail he received and send free *Music Time in Africa* goodies to anyone who wrote in. He also thanked fans by name during the radio show.

Through reading many scripts, I had noticed that Leo used the word "friends" pretty frequently, but I did not realize just how frequently until this analysis. I typed the word "friends" into the Contexts box in Voyant and took a look. "Friends" had 23 contexts in the five scripts, and each script contained 4-6 individual instances of the word. Through looking at the results in the contexts box, it appears that almost every time the host, Rita Rochelle, directly spoke to the fans, she used the word friends.

<div class="img_row">
	<img class="col three" src="/img/voyant-post/friends-voyant.png" alt="Charts depicting data on the word friends in the scripts" title="Usage of the word friends in MTiA scripts"/>
</div>
<div class="col three caption">
	Voyant's results for the word "friends" for all five scripts
</div>
<br/>
<br/>

Though we already knew that a purpose of *Music Time in Africa* was to build and maintain relationships and ties between the United States and countries in Africa, the use of the word "friends" further shows how the show attempted to accomplish this purpose.

Next, I turned to the summary box in the lower left corner of Voyant to take a better look at the most frequent words in the corpus. It was interesting to see that Nigeria was one of the most frequently used words across the scripts, because each script generally focuses on one particular genre of music or country. If Nigeria was one of the most frequently used words, then they likely were playing music from Nigeria each week or they were receiving lots of fan mail from Nigeria.

I looked to the Contexts box again to get a better understanding of when Nigeria was used. Almost every single context was in relation to fans. **This means that they were indeed receiving lots of fan mail from Nigeria.** It would be interesting to further explore from which countries *Music Time in Africa* fans were writing.

<div class="img_row">
	<img class="col three" src="/img/voyant-post/nigeria-voyant.png" alt="List of instances of the word Nigeria used in the scripts" title="Instances of the word Nigeria used in scripts"/>
</div>
<div class="col three caption">
	Instances of the word "Nigeria" used in scripts. Almost all instances are preceded or followed by fan names, indicating they are associated with people who wrote to Leo.
</div>
<br/>
<br/>
<br/>
# Distinctive words in the scripts
<br/>
Then, I examined the list of each script's distinctive words, since that was my main goal of the analysis.

<div class="img_row">
	<img class="col three" src="/img/voyant-post/distinctive-words-voyant.png" alt="List of five most distinctive words per scripts" title="Distinctive words"/>
</div>
<div class="col three caption">
	The five most distinctive words per script
</div>
<br/>
<br/>

Some of the results were less helpful than others, so I took a closer look in particular at the countries listed and any words that looked like musical genres or groups of people. **From my knowledge of these scripts, I knew that Voyant had successfully identified the main subjects of each radio program.**

Voyant identified "muchongolo," "ihubo," and "nguni" as distinctive words for the April 29, 1979 script. This particular program was about the music of Niger, specifically the Muchongolo dance of the Nguni. Similarly, the May 6, 1979 script is about music from Mozambique, which Voyant singled out as the first most distinctive word in the document. The last three scripts (May 13, May 20, and May 27) were about particular countries, all of which were  identified as distinctive words.

Overall, the results of the distinctive words seems promising for quickly identifying what a particular radio broadcast might be about or what might be distinctive about a particular broadcast.
<br/>
<br/>
# Next steps
<br/>
This analysis revealed two major questions when using Voyant with the *Music Time in Africa* scripts. First, I used five cleanly typed scripts for this Voyant analysis, but the reality of this project is that our OCR transcripts will not be 100% accurate. **It would be interesting to see how Voyant analyzes scripts where only the most "important words" are cleaned up** (for more information on this, see my post on the OCR work I've done with this collection). Will the information be as valuable?

In addition, I only used five scripts for this analysis, which makes me wonder how Voyant will analyze distinctive words. We're currently hypothesizing that *Music Time in Africa* reused a lot of the same music (and potentially the same broadcasts) across the years. **How would this reuse impact the results in Voyant?**

This analysis, however, showed me the possibilities of using Voyant to explore a similarly structured collection of materials. Though I could not make any new findings or strong arguments from the results, the Voyant data served as a different way to explore the scripts and find commonalities I would not have been able to find as easily through a close reading.
