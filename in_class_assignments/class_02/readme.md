# In Class Assignment 2

## Purpose

Today's in-class assignment is designed to reinforce the techniques you learned in the second lab, and give you more experience in doing journalistic data analysis working with opioid data in its more original form.

We'll also learn a bit about using a data dictionary (sometimes also called a record layout or data documentation) to understand how to interpret a data set and use it responsibly.   

## Setup

1.  Download the "ARCOS Registrant Handbook", which provides detailed information on how to interpret the data in the DEA's ARCOS database.  Most large, complex government data sets you'll ever work with will have a similar document, though they aren't all as complex as this.  You may hear less complicated versions called a "data dictionary" or "record layout." These documents are key to understanding how to analyze a given data set responsibly. [ARCOS Registrant Handbook](https://www.deadiversion.usdoj.gov/arcos/handbook/full.pdf)

1.  Download raw data for Mingo County, West Virginia from the [Washington Post "Digging into the DEA's pain pill database" page](https://www.washingtonpost.com/graphics/2019/investigations/dea-pain-pill-database/).  If you're having trouble, the data is available [in this folder](data/).

2.  Create a new Google Sheets workbook and name it "In_Class_Assignment_02 YOUR NAME Sheet".  Set the permissions to "anyone with link can edit".  

3.  Upload the tab-delimited text file into a new sheet inside of the workbook you created.  Rename the sheet with "Mingo-working". Don't worry about making a copy of the sheet to preserve the original.  It's too massive, and having two copies will crash Google Sheets.  You have the original text file if you need to start over. Create a new spreadsheet called "Source" that describes the source, date and details of the data.

4.  Set up the sheet as you learned in the first tutorial video. This sheet is too big to do a traditional four-corners check looking for strange or missing values.  But you can get do a version of this check by turning on filters and examining the values in each column.  Add a "record number" column to give each row a unique record number.  Freeze the first row. Format the numbers nicely.

5.  Create a Google Doc called "In_Class_Assignment_02 YOUR NAME memo". Set the permissions to "anyone with the link can edit". Paste the questions below into this memo document. Also paste a link to your spreadsheet.

## Questions

Answer the following questions.

**Unless the question notes otherwise, you must create a single pivot table to answer each group of questions.   For example, # 3 has three separate questions.  Build one pivot table to answer all three. At least one question requires you to use filters.  Label each new pivot table with the number of the question grouping.**

1.  What was the name of the pharmacy that received the most total pills in Mingo County, West Virginia between 2006 and 2012? Build a pivot table to answer this question.

2. Pills are sent from a manufacturer ("labeler") to a distributor ("reporter") and then to a pharmacy, retailer or related business ("buyer").  In Mingo County, West Virginia between 2006 and 2012, which combo of those three (total pills from one manufacturer > to one distributor > to one pharmacy) was responsible for the largest number of pills? Name the three entities? How many total pills?

3. What is the "DRUG_CODE" for hydrocodone? What is the "DRUG_CODE" for oxycodone? What percentage of all pills sent to Mingo County, West Virginia were hydrocodone and what percentage were Oxycodone?

4. How many different "TRANSACTION_CODES" are there?  What does "S" stand for?  You must review the ARCOS handbook to find out, don't guess.   

5. Which state sent the most pills to Mingo County, West Virginia?  Use the distributor state to calculate this.

6. On what date did the single largest transaction (total number of pills) take place?  Describe the transaction in as much detail as the data will allow.  You do not need to do a pivot table to do this, but you're welcome to create one if you like.

7. What data is stored in the NDC_NO field? Find the documentation and answer in a paragraph what the number represents.

8. Develop four separate questions of your own that you think might yield newsworthy information that requires a pivot table to answer. Then build a pivot table to answer those questions.  Talk to your neighbors or me if you like, or refer back to previous assignments.  It's fine to ask similar questions to what we've already asked.    

## Turning it in

Upload a link to your completed spreadsheet and memo on ELMS.  See the links on the syllabus.
