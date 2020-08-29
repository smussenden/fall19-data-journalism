# Data Analysis Project

This project will give you a chance to go through the process of analyzing a complex database on your own in order to discover newsworthy information.

## The topic and data

You have three options for this project.  

### 1) Work with opioid data  

You can work with the DEA's ARCOS database, using the slice released by the Washington Post that contains detailed information on hydrocodone and oxycodone shipments between 2006 and 2014.  

To obtain the data, you will work with the ARCOS R package produced by the Washington Post.  You will also be required to bring additional data to bear on this question, depending on the questions you want to ask.

### 2) Work with COVID-19 data

* https://covidtracking.com/ and https://www.nytimes.com/article/coronavirus-county-data-us.html and https://coronavirus.jhu.edu/map.html
* Use Rtweet to pull in president trump or other tweets.
* Stanford's BIG LOCAL NEWS project is also collecting interesting data_acquisition_project https://biglocalnews.org/#
  * Tweets by governors
  * CDC Social Vulnerability Index The index indicates the relative vulnerability of each Census tract or county. Social vulnerability refers to the resilience of communities when confronted by external stresses on human health, stresses such as natural or human-caused disasters, or disease outbreaks.
  * AHA hospital beds data at state and metro areas provided by USA TODAY for use by journalists in Coronavirus reporting.
  * https://www.cdc.gov/asthma/asthmadata.htm
* https://www.kaggle.com/allen-institute-for-ai/CORD-19-research-challenge

### 3) Work with some other data

Got an idea for a project on some other topic.  Let's chat!

## How to approach

You are a reporter for a national news organization. You are interested in doing an original analysis to identify some describe broad trend or pattern, based on a hypothesis founded on reporting and research you have done.

Unless you get specific permission from me, your analysis must include some sort of "enterprise join", where you combine two or more data sets to find something original and newsworthy.   

It's possible your original hypothesis will not stand up to your first cut at analysis. A lack of a result may be newsworthy, but you should also be prepared to pivot.    

You should find experts familiar with your topic to help put your findings in context and to ensure that your analysis method is logically and statistically sound. You should also, through your analysis, identify geographic locations that exemplify the trends you've uncovered where you may be able to identify characters to bring a story to life.    

## Many stories to tell

Here are two examples of opioid stories that were founded on the kinds of analysis appropriate for this project:  

* The Washington Post looked at the [relationship between death rates and opioid sales in select communities](https://www.washingtonpost.com/investigations/opioid-death-rates-soared-in-communities-where-pain-pills-flowed/2019/07/17/f3595da4-a8a4-11e9-a3a6-ab670962db05_story.html).
* The Tampa Bay Times looked at politicians backing [drug companies as the crisis deepened](https://www.tampabay.com/florida-politics/buzz/2019/07/25/floridas-opioid-crisis-billions-of-pills-millions-in-campaign-cash/)

Here are two examples of a COVID-19 story with analysis that would be appropriate for this project:

* [US hospitals will run out of beds if coronavirus cases spike](https://www.usatoday.com/in-depth/news/investigations/2020/03/13/us-hospitals-overwhlemed-coronavirus-cases-result-in-too-few-beds/5002942002/)
* [A likely but hidden coronavirus risk factor: pollution](https://publicintegrity.org/health/coronavirus-and-inequality/a-likely-but-hidden-coronavirus-risk-factor-pollution/)

## Motivating questions

You should develop a motivating question or working hypothesis to test with your analysis.  These questions should be developed by doing research, reading news stories and/or discussions with experts.  

Here are some examples of a working hypothesis that can be tested:

* Chain pharmacies played an outsize role in driving the opioid crisis.
* The DEA only took enforcement action against a small percentage of pharmacies with questionable levels of opioid sales.
* Places with large elderly populations are seeing higher rates of death from COVID-19.
* Republican governors have been less likely to call for shelter in place orders than Democratic governors, even when controlling for scope of infection spread.       

## Requirements

* This analysis should be sufficiently complex.  You should be asking basic questions that we've asked so far in class.  But you should be pushing beyond that, trying to discover something new.  
* You must make use of:
  * R, R Markdown, the Tidyverse and GitHub.
  * At least two data sources to do an enterprise join.
  * At least two data visualizations in R.
* Your analysis must be original.  It's fine to use other stories done by other journalists as inspiration (with credit), but you must ultimately find something new, not just replicating their work.  

## Deliverables and deadlines

**Week 10:** project introduced

**Week 11:** Data analysis forum post 1
*  In about 400-500 words, write up a memo that explains how you plan to proceed with your data analysis project. You should hit the following points:
  * Share the questions you'd like to investigate for your data analysis project.  What's your hypothesis for what you think you'll find? What gives you confidence that your hypothesis is correct?  
  * Include at least a few references (and links if applicable) to academic research; government or non-profit organization reports; or news stories that give you some confidence that your ideas are worth investigating. Have other news organizations written a story you could build on?
  * Explain what other data, beyond the ARCOS data, you will need to analyze.  You should use at least one other data set in reporting this out.  Does the data exist?  If you don't have it yet, how will you get it?
  * Include a few names of people or organizations who you can talk with as you go about doing this analysis and reporting out a story. Are there academics who have done similar studies?
  * Explain why you think your analysis will likely lead to something newsworthy.  

**Week 13:** Data analysis forum post 2
* Update on exploratory analysis and draft markdown file.
  * In less than 300 words, describe what you've done so far, what you've found so far, what problems you've had and where you plan to go next.  Is your original hypothesis holding up, or do you need to pivot?
  * Also provide a link to your class GitHub repo, where you've created a well commented R Markdown file that shows your initial attempts at loading, cleaning, understanding and analyzing the data you're using. Make sure the repo is public.
  * Your analysis should be halfway done at this point.

**Week 15:** Data analysis forum post 3
* Update on exploratory analysis and draft markdown file.
  * In less than 300 words, describe what you've done so far, what you've found so far, what problems you've had.  
  * Also provide a link to your class GitHub repo, where you've created a well commented R Markdown file that shows your initial attempts at loading, cleaning, understanding and analyzing the data you're using. Make sure the repo is public.
  * Your analysis should be substantially finished at this point.  

**Week 16:** Story pitch memo and a clean GitHub repo with R Markdown file that you used to produce the findings detailed in your memo. Your final markdown file should only contain those queries and visualizations used to support your analysis, not everything you've done.

## Final story Memo

This story memo should pitch a story idea derived primarily from your analysis of the database, including a discussion of what you found that was newsworthy when you analyzed the data, how the data could be used to develop the story, and what additional steps would be needed to complete the reporting of this story.

The story memo should be written as if you were trying to get the attention of a very busy editor and convince that editor to give you the opportunity to pursue a story you believe is suggested by your analysis.

The final story memo should include the following:

* A strong statement at the top. Write this as if I am your editor and you are competing for my attention with reporters pitching other story ideas. That is, don’t start by saying, “I sat down and launched R and looked at the database and sorted it 10 different ways.” Tell me right up front what you found that was interesting or what you found that suggests a dynamite story. Tell me how your most newsworthy findings relate to what you found in your research about prior uses of similar data for stories elsewhere. Do not pitch your findings for more than they are worth, however, or make assertions not supported by your work.
* A summary of the results of your analysis. Describe results that are germane to the main thrust of the story you are pitching and, if appropriate, relevant results that suggest other interesting avenues to explore. Indicate whether your findings are new or whether they present a local angle for similar findings reported elsewhere.
* Pros and cons of the data. Discuss both the strengths and limitations of the data.
* How you would verify your findings. Identify the specific reporting and data steps would you take and the types of information you would use to determine whether the results of your analysis are accurate and significant. If your analysis suggests fault or issues of accountability on the part of public or private figures, indicate whom you would need to contact for response to ensure that your reporting was fair and accurate.
* Bringing it home. Indicate the specific steps you would need to take to finish reporting the story. Include the people you would contact and, if relevant, the places you would visit. Indicate how you would make the story real to readers.
* Editors are not interested in process. Don’t fill the memo with what steps you took.

## Grading

This project is worth 30 percent of your grade, broken up into assignments throughout the semester.  

* Story memo: 10 percent
* Final GitHub repo: 10 percent.
* Other in-process deliverables: 10 percent.
