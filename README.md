# Kickstarting with Excel

## Overview of Project

### Determine whether plays in the KickStarter file were successful or unsuccessful at meeting their funding goals. Tables and charts were created to provide a visual of play outcomes based on funding goals and launch dates. The information in these worksheets will help Louise learn how fundraising for her play *Fever* did compared to other plays.
[Kickstarter_Challenge.xlsx](https://github.com/nabernal/Kickstarter-Challenge/files/9581215/Kickstarter_Challenge.xlsx)

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date

#### The *Outcomes Based on Launch Date* worksheet contains a pivot table. For the table, *Outcome* was placed in the legend and value sections, *date created conversion* was placed in the axis section, and *parent category* and *years* were set as filters. In order to filter by years a new colum had to be created in the Kickstarter worksheet. This was done by pulling the year from the *Date Created Conversion* column using the *=Year(Cell)* formula. 

####The fields above help provide a visual on kicktarter outcomes based on the month they were launched. Since Louise is fundraising for a play, the data is filtered so that only theater informatiion is displayed. To make the infromation easier to read, the *Row Labels* column is sorted in ascending order and the outcomes are in decending order. Filtering the data further might be helpful for Louise. For instance the years range from 2009 to 2017. It might be better to focuse on recent years. 

![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/108249510/190569471-bcdc8b54-3805-4466-aeae-b9a9168cf3fc.png)



### Analysis of Outcomes Based on Goals
####The table in the *Outcomes Based on Goals* worksheet displays different funding goal ranges. Kickstarter outcomes were categorized into one of the ranges using the *COUNTIF* formula. The percentage of successful, failed, and canceled outcomes for each range were calcualted using the *=(Part/Whole)x100=Percentage* formula. A chart was then created using the goal amount ranges and outcome percentages to give a visual of how successful and unsuccessful each funding goal range was. 

![Outcomes_vs_Goals](https://user-images.githubusercontent.com/108249510/190569205-88039072-8908-4095-90ba-e31788e58c2f.png)

### Challenges and Difficulties Encountered
#### The second deliverable took a while to complete. It took me about an hour to correctly write the *COUNTIF* formule. It was my first time working with the COUNTIFS formula therefore I did not know what part of the formula I was messing up. After rewatching the hint video in the module and searching online I confirmed everything was entered correctly. It turned out that I misspelled a word. Once That was resolved everything else moved along smoothly.  

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
    - Based on the data, May seems to be the best time to launch a kickstarter. It has the most successful number of kickstarters compared to other months.       On the contrary, December seems to be the worst time to start a kickstarter. Only 37 kickstarters were successful and 35 kickstarters failed in             December. 

- What can you conclude about the Outcomes based on Goals?
    - The most successful funding goal is between $1000 to $4999. This range includs 534 kickstarters, and of those, 72% were successfull. In addition, the       chart shows that as the funding goal increases the chances of a kickstarter being successful is less likely. The cut off seems to be the $15000 to         $19999 funding goal range. There were the same amount of successful and failed kickstarters in this range. 

- What are some limitations of this dataset?
    - One limitation for the *Outcomes Based on Goals* dataset is that we do not know when the kickstarters launched. Adding this information would allow         us to see what months were the most successful whithin a range. Another limitation is not being able to filter by country. It could be that some           ranges are only successful in certain countries but not in others.

- What are some other possible tables and/or graphs that we could create?
    - Adding filters to both of the existing tables would allow Louise to look more closely at outcomes as they relate to her cercumstances. For example,         she could look at outcomes in specific countries or based on subcategories. Adding a bar graph could provide a better visual of the number of               successful and failed kickstarters for each month.   
