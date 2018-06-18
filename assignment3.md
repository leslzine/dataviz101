# Zine Genres, by Lustrum

The 
[final assignment](https://github.com/dataviz-gc/intro-dataviz-summer18/blob/master/assignments/finalproject.md) for my 
[Data Visualization Class at the CUNY Graduate Center](https://github.com/dataviz-gc/intro-dataviz-summer18), taught by 
[Erin Daugherty](https://datadozen.com/about/) and 
[Michelle McSweeney](http://www.michelleamcsweeney.com/) was to articulate a research question, find data for it, and visualize a 
it in three different ways. 

## The Data: Background

I chose to work with data about the 
[Barnard Zine Library](https://zines.barnard.edu/), which I founded in 2003 and continue to curate. I am frequently asked how zines have changed over time. Since I catalog zines as they are acquired, and not by decade (or 
[lustrum](https://en.oxforddictionaries.com/definition/lustrum), which is what a five-year period is called, and the unit of measure I have chosen for this project), I have don't have the clearest sense of how zine genres and contents have shifted. I have theories, which I will test here.

By comparing the percentage of 
[zine genres](https://zines.barnard.edu/about/genres) in the Barnard Zine Library, correlated to the five-year the zines were published, I hope to illustrate the emphases of each era. 

### The Research Question

My suspicion is that zine creators in the 1990s wrote more about sexual assault and critiqued capitalist systems of oppression more than their 2010s counterparts, who are more likely to write about mental health and friendship, and turn to more artistic expressions of their times. 

### The Audience

I frequently get asked about how zines have changed over the years--by journalists, undergraduates, senior scholars, zine makers, librarians, and audience members at panels. How zines have changed over the years could be of interest to people doing work with girls and women's studies, gender studies, creative nonfiction, media studies, cultural studies, punk history, social justice, sociology, psychology, history of the book, English, library and information studies, and in other disciplines, as they imagine. Maybe it will be appealing to data scientists, too.

### Visualization Description

Below we see three paned bar charts: 

* Consultations Given
* Classes Taught
* Reference Questions Answered

A 1-3 colored bar represents each month of the year 2017, and the colors correspond to role: communications, personal librarian, and zine librarian. Each chart is crossed with an average line, to help the reader see which months are busier and less busy than usual. 

## The Data: Visualized

### Tree Plot

{% include treeplot.html %}

If the embed link isn't functioning in your browser, here's a link to the 
[visualization on Tableau Public](https://public.tableau.com/profile/jenna.freedman#!/vizhome/Assignment3_435/TreeMapDashboard). 


#### Data Decisions

### Line Graph

{% include linegraph.html %}

If the embed link isn't functioning in your browser, here's a link to the 
[visualization on Tableau Public](https://public.tableau.com/profile/jenna.freedman#!/vizhome/Assignment3-lines/Dashboard1). 

#### Data Decisions

### Gantt Chart

{% include gantt.html %}

If the embed link isn't functioning in your browser, here's a link to the 
[visualization on Tableau Public](https://public.tableau.com/profile/jenna.freedman#!/vizhome/Assignment3-dispersion/DispersionPlotDashboard). 

#### Data Decisions



#### Data Decisions

* Colors were chosen for a color blind compliance, rather than for general aesthetics. 
* This visualization shows the number of research consultations I gave, instruction sessions I led, and reference questions I responded to in the year 2017. I have data from December 2015-April 2018 that I am happy to share, but showing just the most recent year for which I have complete data seemed like it would give a good enough picture of how I divide my time, at least in those three areas, in a cleaner manner than including the other months. 
* I originally envisioned this data in a line graph, rather than a bar chart. I switched when I realized that lines indicate trends, and while my work is cyclical one month's numbers don't necessarily relate to those of the previous or next month's. 
* There were many fields in my initial dataset that I chose not to include in the visualization because they were extraneous or inconsistently reported. That includes, e.g., the medium of reference questions--if they came in via email, Tweet, IM, or in person. The granularity would have muddied, rather than improved the visualization. 
* I would have liked and would like to before too long, add in some of the columns in my dataset that I didn't include, but for now, the granularity of the columns I did include feel like scope creep. 
* I had intended to include description information in the rollover text. I got that working for sections where there is only one of a kind, e.g., one consultation for a role in one month, but not when there are multiple of a kind in a month. Lauren managed it in her Amazon visualization, so I'm hoping I might get help and figure that out before the pin up! 

### Next Steps

Once I complete my monthly report for May (soon!) I could make calendars for academic years 2016/17 and 2017/18, which would be more applicable in the higher ed setting. Still, I consider this visualization dangerous in isolation for the reasons I mentioned in the background section above. Without representing all of the other work I do in communications and zine librarianship, the loads may appear more balanced than they actually are. 

I do include additional information about my communications and zine work in my monthly reports, but it is harder to compare across departments. How many events hosted or tweets tweeted equal how many zines cataloged or presentations given? That's not to say that there isn't Womens, Gender, and Sexuality Studies librarian (personal librarian) work that isn't represented on the simple charts, too, e.g., outreach to students and building research guides. 

Finally, I'm not sure if I answered the "am I a slacker or a driven workaholic" question with this one series of visualization. I would need to normalize it somehow. I don't think comparing my work to that of colleagues would be useful because no one has the same balance of jobs that I do, I have fewer PL departments than others, etc. I could try mathing it to a 35-hour work-week and account for holidays, vacation (27 use-em-or-lose-em days), professional leave, and affordances for MALS coursework. And, of course, figure out how to quantify or otherwise evaluate the data not included. 

I will adapt my monthly reports to this format, though, going forward!

### Further Reading

For more about my process and choices, see 
[my proposal and notes](https://docs.google.com/document/d/e/2PACX-1vR9Hru-QwifG4TzU1egp_Q2hKXJ79FAydYmmFAU4hyz9kGYSynlxleg53SiA_U7tlJxgNoDVzK2t-X1/pub). You'll find there information on how I reformattted and cleaned my data, fields included in the dataset but not the visualization, inconsistent reporting, database crashes, and a brief ode to the sketch, along with my initial sketch itself. 

I didn't do as much tweeting this week, but do check out
[my thread](https://twitter.com/zinelib/status/1005544964703576064) for a panda gif trolling Tableau, 
[my cat's commentary](https://twitter.com/zinelib/status/1005515362631344129), and a 
[hint of desperation](https://twitter.com/zinelib/status/1005507326009335813). 

### [Home](https://leslzine.github.io/dataviz101/)
