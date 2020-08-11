---
layout: page
title: Topic Modeling Music Time in Africa Scripts
date: Posted March 23, 2017
update: Updated April 21, 2017
description:
img:
---
<br/>
# Topic Modeling and Music Time in Africa
<br/>
Another method, another set of Music Time in Africa experiments! In class, we have moved to topic modeling. Though I had an introduction to topic modeling, I have never tried to run a topic model myself.

My methods sections this week is rather short, because I was slightly discouraged by the topics I got, and I was unsure of how to improve them. I used the same five test scripts that I used for the Voyant experimentation, since they were already typed out. I removed all of the more "formatting"-related words (such as VOICE: and lines that tell the audio engineer which insert to play) so I was left with just the spoken content of the script. Then, I ran the txt files through MALLET for 20 topics.
<br/>
<br/>
# Refining the models
<br/>
Once the topic model was finished running, I took a look at the models. They seemed to be nonsense, and I was not quite sure what to do with them and whether they were really representative of my data.

<div class="img_row">
	<img class="col three" src="/img/topicmodeling.png" alt="results of topic model" title="Topics from MTIA"/>
</div>
<div class="col three caption">
	The topics MALLET returned for the five MTIA scripts. I can't make sense of them.
</div>
<br/>
<br/>


[Ted Underwood](https://tedunderwood.com/2012/04/07/topic-modeling-made-just-simple-enough/) makes the point that topics that make sense aren't really meaningful. Being able to see to see that "sea sailor boat" all go together does not provide any new insights you would not have already known by doing a close reading. What is helpful, he says, is topic models identifying discourse, such as poetry.

This does not really apply to MTIA, but it raises some questions for me. How can you evaluate a topic that is not "obvious?" In theory, a scholar will be able to evaluate whether or not a topic makes sense because she will have a deeper understanding of the corpus. But to what extent could someone be reading too much into the corpus through topic modeling? When do you know when you've made an "accurate" or "useful" topic model?

My limited understanding of how topic models work did not provide a solid answer for these questions. Perhaps these questions show my distrust of the method, but because I do not know enough about the theory, I am slightly distrustful. I know that scholars probably would not be using topic modeling if they did not think it would produce useful and reliable models. I personally will want to learn more about how topic modeling works before I can dive deeper into any personal topic modeling projects.
<br/>
<br/>
# What MTIA could do with topic modeling
<br/>
Despite my misgivings, I think topic modeling has the potential to be useful with the force of the whole MTIA data set. [Blei](http://journalofdigitalhumanities.org/2-1/topic-modeling-and-digital-humanities-by-david-m-blei/) states that "a topic model takes a collection of texts as input. It discovers a set of 'topics' — recurring themes that are discussed in the collection — and the degree to which each document exhibits those topics." Based on this, I would think that topic modeling could possibly be used to pull together scripts with similar music/themes. Like with Voyant, this would be helpful to understand what materials we have and what scripts might be related through music or instruments. This is data that we are cleaning up in our OCR transcripts but not including in our metadata records, so there is currently no way for us to collect this data other than with a close reading.

[Ted Underwood](https://tedunderwood.com/2012/12/14/what-can-topic-models-of-pmla-teach-us-about-the-history-of-literary-scholarship/) also planted the seed in my head that some interesting things can be done to look at topics over time. This could potentially be interesting for the MTIA programs because we could see if the change in topics they focused changed on over time. This would be especially interesting if we juxtaposed this with major historical events, such as wars, independence, and border changes. MTIA played, and to some extent, still plays a cultural ambassador role within VOA, so this kind of analysis could potentially produce interesting results.
<br/>
<br/>
# Final thoughts
<br/>
Overall, I am not entirely impressed with topic modeling when your data set is small. I would like to see more examples of massive data sets that use topic modeling and what conclusions the authors found, and I hope that scholars continue to experiment with what can be done. I would also like to learn more about how topic modeling works so that I can understand how to better refine my results and critique other topic modeling projects. My data set (and probably a lot of other data sets), however, was simply too small to get a good picture of the potential of topic modeling.
