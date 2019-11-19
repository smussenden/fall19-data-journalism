# Data Analysis Project

This project will give you a chance to go through the process of analyzing a complex database on your own in order to discover newsworthy information.

## The data

You will work with the DEA's ARCOS database, using the slice released by the Washington Post that contains detailed information on hydrocodone and oxycodone shipments between 2006 and 2012.  

To obtain the data, you will work with the ARCOS R package produced by the Washington Post.  You will also be required to bring additional data to bear on this question.

## Your motivation

You should approach this assignment through one of three lenses.  The data has just been released by the Washington Post, and you should approach this project as:

* A reporter for a local news organization, primarily interested in using the data to find trends and examples that affect one specific area (a county or group of counties), and then putting what you find in state and national context.   
* A reporter for a national news organization, interested in using the data to describe broad nationwide trend, and then finding specific locations and examples that are emblematic of that trend.

In both cases, you are interested in using your analysis as the foundation for a specific, newsworthy story angle (or angles) that has not been reported by another news organization.  Your story should shed some light on how free-flowing sales of prescription opioids helped drive the opioid crisis in the United States.    

## Many stories to tell

News organizations have used this data to tell all kinds of specific stories.

* The Charleston (Wv.) Gazette-Mail focused on [sales by chain stores](https://www.wvgazettemail.com/news/health/chain-drug-stores-brought-millions-of-opioids-to-wv-as/article_258d176e-c87d-5c96-bd29-2402dc844b30.html).
* The Washington Post, among other stories, looked at [sales by a handful of generic drug companies](https://www.washingtonpost.com/investigations/little-known-generic-drug-companies-played-central-role-in-opioid-crisis-documents-reveal/2019/07/26/95e08b46-ac5c-11e9-a0c9-6d2d7818f3da_story.html).
* The Post also looked at the [relationship between death rates and opioid sales in select communities](https://www.washingtonpost.com/investigations/opioid-death-rates-soared-in-communities-where-pain-pills-flowed/2019/07/17/f3595da4-a8a4-11e9-a3a6-ab670962db05_story.html).
* The Tampa Bay Times looked at politicians backing [drug companies as the crisis deepened](https://www.tampabay.com/florida-politics/buzz/2019/07/25/floridas-opioid-crisis-billions-of-pills-millions-in-campaign-cash/)
* AL.com looked at how pills flooded into Alabama, and also looked at how [different racial groups were affected by the sales](https://www.al.com/news/2019/07/where-the-opioid-epidemic-hit-hardest-alabama.html).

## Motivating questions

You should approach the assignment with several motivating questions (or even hypotheses) to test with your analysis.  You should come up with these on your own.  They could be things like:

* How did the flow of pills into Montgomery County, Maryland change over time?
* Which distributors were most responsible for flooding pills into Virginia at the height of the opioid crisis?
* Did opioid deaths follow the same trendline as opioid shipments in Philadelphia?
* Were there any people who shouldn't have been licensed as pharmacists selling these pills in a local area?
* What did DEA enforcement of questionable pill sales look like?  Does it seem like there are any obvious examples of places with strange levels of sales that should have been caught that weren't?
* Purdue Pharma is often credited with/blamed for launching the opioid crisis. What do the flow of sales from that drug company look like?
* Was the opioid death rate worse in more economically depressed areas of the country? And did more pills flow to those places?
* How many people who prescribed opioids in a given place had their license suspended?

## Requirements

* This analysis should be sufficiently complex.  You should be asking basic questions that we've asked so far in class.  But you should be pushing beyond that, trying to discover something new.  
* You must make use of:
  * R, R Markdown, the Tidyverse and GitHub.
  * Opioid data acquired via the Washington Post ARCOS API package.
  * At least one additional data source you pull in to do an enterprise join.
  * At least two data visualizations in R.
* Your analysis must be original.  It's fine to use other stories done by other journalists as inspiration (with credit), but you must ultimately find something new, not just replicating their work.  

## Deliverables and deadlines

**Week 8:** project introduced

**Week 9:** a 400-word max status memo as a forum post, explaining the following:
  * What motivating questions you think might drive your work. You should have a few different groups of questions for approaches at this point.  We will work together to pick one.  
  * What specific opioid data from the WashingARCOS API will help answer these questions.
  * What additional data sources will be required to answer these questions.
  * What else has been written (including links) that is related to your questions.  

**Week 11:** Forum post update on exploratory analysis and draft markdown file.
  * In less than 300 words, describe what you've done so far, what you've found so far, and where you plan to go next. You should pull this from your Markdown file. Is there something you're having problems with, either conceptually or technically? Post it here.
  * Also provide a link to your class GitHub repo, where you've created a well commented R Markdown file that shows your initial attempts at loading, cleaning, understanding and analyzing the data. It should contain at least 15 specific questions, answers and code to produce the answers those questions.  Make sure the repo is public.

**Week 14:** a link to your repo with updated data analysis. It should contain at least 30 specific questions, answers and code to produce the answers to those questions.  

**Week 15:** Story pitch memo and a clean GitHub repo with R Markdown file that you used to produce the findings detailed in your memo.

**Week 16 (During Exam Block):** "pitch your editor" presentations.  

## Story Memo

This story memo should pitch a story idea derived primarily from your analysis of the database, including a discussion of what you found that was newsworthy when you analyzed the data, how the data could be used to develop the story, and what additional steps would be needed to complete the reporting of this story.

The story memo should be written as if you were trying to get the attention of a very busy editor and convince that editor to give you the opportunity to pursue a story you believe is suggested by your analysis.

The final story memo should include the following:

* A strong statement at the top. Write this as if I am your editor and you are competing for my attention with reporters pitching other story ideas. That is, don’t start by saying, “I sat down and launched mysql and looked at the database and sorted it 10 different ways.” Tell me right up front what you found that was interesting or what you found that suggests a dynamite story. Tell me how your most newsworthy findings relate to what you found in your research about prior uses of similar data for stories elsewhere. Do not pitch your findings for more than they are worth, however, or make assertions not supported by your work.
* A summary of the results of your analysis. Describe results that are germane to the main thrust of the story you are pitching and, if appropriate, relevant results that suggest other interesting avenues to explore. Indicate whether your findings are new or whether they present a local angle for similar findings reported elsewhere.
* Pros and cons of the data. Discuss both the strengths and limitations of the data.
* How you would verify your findings. Identify the specific reporting and data steps would you take and the types of information you would use to determine whether the results of your analysis are accurate and significant. If your analysis suggests fault or issues of accountability on the part of public or private figures, indicate whom you would need to contact for response to ensure that your reporting was fair and accurate.
* Bringing it home. Indicate the specific steps you would need to take to finish reporting the story. Include the people you would contact and, if relevant, the places you would visit. Indicate how you would make the story real to readers.
* Editors are not interested in process. Don’t fill the memo with what steps you took.

## Story Pitch

This isn't a class presentation in the traditional sense.  You and I will sit at the front of the room and you'll talk directly to me, while the rest of the class watches.

Here's the scenario:

We're going to pretend we're in a newsroom. I'm your very busy editor. You're a beat reporter, with a lot of daily responsibilities.  

You've done a bunch of great data analysis and have the foundation for what you think will be a good story, but you need a little bit of time to do some reporting to flesh out a story based on that analysis.  

You think this is the kind of enterprise story that will be a centerpiece of your clip package or reel. The kind that gets you your next job.   

So, you need to convince me that I should give you a week free of other duties to do the reporting needed to bring this story home.  Giving you time means I give your responsibilities to someone else -- or they just don't get done. So you really have to sell me.  

You have three minutes. Do this:

* Start by asking me: "I think I have the makings of a good story, can I talk to you about it."
* Describe the most newsworthy thing you found.
* Describe in detail what you think you need to do to report out this story and verify your findings. Who would you talk to? Where would you need to go? How would you make people care about this story?
* Describe what work others have done on this, but how this breaks new ground.
* Finish by handing me the memo you wrote up and asking if I have any questions?


## Grading

This project is worth 30 percent of your grade, broken up into assignments throughout the semester.  

* Story pitch: 5 percent
* Story memo: 7.5 percent
* Final GitHub repo: 7.5 percent.
* Other in-process deliverables: 10 percent.
