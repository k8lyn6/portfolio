---
layout: page
title: Discovering Optimal Digitization Specs for OCR Output
date: Posted March 23, 2017
img:
---
<br/>
As part of my work on the NEH grant project, "Ethical Access to *Music Time in Africa*," I conducted a study to find the optimal digitization specifications for our scripts to produce the cleanest possible optical character recognition (OCR) transcripts. We hope to use the OCR transcripts in the background of the access system to allow users to search for words that aren't included in catalog records.

The collection of scripts is mostly comprised of photocopies of the original scripts typed on dot matrix paper, but we also have some original typed scripts on dot matrix paper. The photocopies aren't the most pristine -- most appear visibly fuzzy and contain handwritten notes. This creates a lot of noise when we run the digitized scripts through the OCR software.

Some of this noise will always affect the OCR output, but we hoped that increasing the resolution of the digital images would create cleaner OCR output. We hoped by finding the best digitization specifications for our collection, we could minimize the amount of cleanup needed for the OCR transcripts.
<br/>
<br/>
# A note on the concept of "important words" in the scripts
<br/>
When the *Music Time in Africa* project first began, we thought we would rely most on the audio recordings of the radio broadcasts because we had no idea how many scripts for the individual broadcasts we had in the collection. Once we inventoried the reel-to-reel tapes, we discovered that we had scripts for a large portion of the collection.

This switched our approach for cataloging. Instead of having to listen to each thirty-minute program to figure out what it was about, we could read the scripts. We also discovered the wealth of information contained within the scripts. Even though we could not include all of the information in the individual catalog records for the access system, we thought it would be important for that information to be searchable. We decided that it would be a worthy effort to run each digitized script through an OCR program to mine this information.

However, we recognized that since these OCR transcripts would not be front-facing, we weren't striving for 100% accuracy for the OCR. We came up with the concept of "important words" to clarify which words were important to clean up once the scripts are run through the OCR tool (a modified TESSERACT OCR software within the ResCarta Toolkit, which we are using for cataloging). "Important words" are any of the following:

- Personal names (such as artists' names, ethnic groups, musical groups, etc)
- Musical instruments
- Musical genres
- Locations (specific, not general; could you stick a pin in the map for this location?)
- Descriptive words about the music (such as "regimental dance," "vocals," or "lyrical")

We include a subset of these words in the catalog record for each script, but we decided that all of these words must be identified and checked during OCR cleanup. Other words that do not fall into these categories do not matter.
<br/>
<br/>
# Conducting the study
<br/>
I selected three representative scripts for digitization: a pink dot matrix script, a white dot matrix script, and a photocopied script. All three scripts were relatively clean scripts, as we wanted to see what the upper limit of our accuracy could be, and handwriting instances likely will always cause headaches with OCR regardless of the digitization specifications.

I digitized each of the three scripts at 300 DPI, 400 DPI, and 600 DPI in color, then converted those tests into bitonal for a total of six test instances for each script. I ran all test instances through the ResCarta OCR tool and used the OCR cleanup tool to evaluate the accuracy of the transcripts.

I chose a section of less than 100 words for each script and counted the number of words incorrectly read by the OCR tool. I identified these test sections by choosing a paragraph that described a musical insert and therefore contained a large portion of "important words." I first got a total count of the words in the paragraph, then I individually checked each word to see whether it contained any kind of error from the OCR. Once I had counted the test sections for each of the test instances for each script, I compared the results.

<div class="img_row">
	<img class="col three" src="/img/script-example.png" alt="Digitized copy of a pink dot matrix script"/>
</div>
<div class="Example script exerpt">
The 88 words used to check the accuracy of the OCR transcripts from the pink dot matrix script.
</div>
<br/>
<br/>

# 300 DPI???
<br/>
We found that the 300 DPI color scans produced more accurate OCR transcripts than any other test instance for each of the three scripts.

...what??

Yeah, we were surprised too. And for some of the scripts, the difference wasn't a matter of one or two words. The OCR software wasn't even able to read one word of one of the 600 DPI bitonal scripts. See the chart below for a comparison for each test instance.  

<div class="img_row">
	<img class="col three" src="/img/ocr-chart.png" alt="Table depicting OCR errors in 18 scripts" title="OCR errors"/>
</div>
<div class="col three caption">
Results of OCR test for pink and white dot matrix scripts scanned at 300 DPI, 400 DPI, and 600 DPI in color and bitonal. Most accurate transcripts for each script are bolded.
</div>
<br/>
<br/>

We think that the increased resolution made the noise on our our already less-than-perfect scripts stand out even more, which created more errors in the OCR output.
<br/>
<br/>
# Why does that matter for the project?
<br/>
Our initial goal was to figure out what the best digitization specifications were to minimize OCR cleanup time. However, because 300 DPI color scans are best for OCR, this means we only have to scan each script one time instead of having to make a bitonal scan for the OCR and a color scan for the access system. This saves us a significant amount of time.

In addition, it takes almost twice as long to digitize a script at 600 DPI than it does to digitize it at 300 DPI. Saving time during all of these steps saves money for the project and means we can spend more time focusing on the access system.
<br/>
<br/>
# So, now what?
<br/>
Our results certainly surprised us, because 300 DPI is less than the current recommendation for digitization for OCR output. It's also the minimum standard for archival digitization. I'm hoping to continue to learn more about what the current recommendations are and why we got the results we did. How does this study fit into other recent and ongoing projects? What discussions are going on in the archival field about digitizing for OCR output?

Throughout this process, I have also personally become quite interested in OCR software and using OCR in cultural heritage projects. For this study, we used Tesseract, which is a Google-supported, open-sourced software. I also performed a study comparing Tesseract with ABBYY FineReader (which MLibrary uses), and I found that Tesseract was much more accurate than FineReader for our collection. I would like to learn more about how these softwares work to understand why Tesseract worked better for us.

Ultimately, it seems that each OCR project is slightly different and require different digitization settings. I'm interested to continue understanding OCR softwares and how archivists, librarians, and digital humanists are using them for their work.
