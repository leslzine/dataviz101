# Zine Genres, by Lustrum

The 
[final assignment](https://github.com/dataviz-gc/intro-dataviz-summer18/blob/master/assignments/finalproject.md) for my 
[Data Visualization Class at the CUNY Graduate Center](https://github.com/dataviz-gc/intro-dataviz-summer18), taught by 
[Erin Daugherty](https://datadozen.com/about/) and 
[Michelle McSweeney](http://www.michelleamcsweeney.com/) was to articulate a research question, find data for it, and visualize it in three different ways. 

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

### Zine Genres

My first visualizations is a tree plot and sub plots, that show the moving collection percentages of fifteen zine genres employed at the Barnard Zine Library:

* **24-hour Zines**: zines conceived, created, and assembled in a 24-hour period
* **Art Zines**: zines comprised primarily of art work
* **Catalog Zines**: zines that sell things, often other zines
* **Compilation Zines**: zines edited by one or more people, comprised of contributed content, often related to a theme
* **DIY Zines**: (DIY stands for "Do It Yourself") zines that intend to educate the reader on how to do or make something. This category includes, but is not limited tok cooking, or "cookzines." 
* **Fanzines**: zines about a person, thing, or activity, often music
* **Mamazines**: zines about parenting, written by a person of any gender (this genre name should probably change!)
* **Minicomics**: zines comprised primarily of comics and cartoonlike images. They are generally smaller than comics, and more autobiographical
* **One-page Folding-Zines**: 
[zines made out of one sheet of paper, folded in eight, with a slit in the middle to make it fold into a book](http://www.readbrightly.com/how-to-make-zine/)
* **Personal Zines**: zines on personal topics, autobiographical creative nonfiction 
* **Political Zines**: explicitly political, sometimes action-oriented zines
* **Review Zines**: zines that review other zines and sometimes books, music, and comics, as well
* **School Zines**: any zine made for a class, grade, organization, or otherwise not 100% under the creator's impetus and control
* **Split Zines**: most often a zine with a *tête-bêche* or *dos-a-dos* binding, where one contributor's content is head-to-toe and front-to-back with the other contributors

## The Data: Visualized

### Treemap

{% include treeplot.html %}

If the embed link isn't functioning in your browser, here's a link to the 
[visualization on Tableau Public](https://public.tableau.com/profile/jenna.freedman#!/vizhome/Assignment3_435/TreeMapDashboard). 


#### Data Decisions

In my past visualizations I've used Tableau's color blind palette, but since it only has 10 colors, and my treemap has 15, I went with Tableau 20. I was concerned I wouldn't finish all three plots and the blog post in time, so I let that go, to be revisited before Thursday.

The top treemap shows zines, ranked by genre percentage over the whole 25-year period, with each genre assigned its own color. The exercise is repeated five times, once for each lustrum. Overall, personal zines comprise 44.33% of zine genre types and is the top-ranked genre throughout each lustrum, as well. This shows that zines held in the Barnard Library, a collection of zines predominantly made by women, are heavily focused on personal experiences. Political zines remain in the top five categories until the 2010-2014 lustrum, which bears out my theory that zines are less political now than they were in earlier years. Art zines are more heavily represented in each lustrum, giving credence to the other part of my hypothesis. 

### Line Graph

{% include linegraph.html %}

If the embed link isn't functioning in your browser, here's a link to the 
[visualization on Tableau Public](https://public.tableau.com/profile/jenna.freedman#!/vizhome/Assignment3-lines/Dashboard1). 

#### Data Decisions

Moving on from the treemap, I wanted to get a better look at zines by genre, so I chose to make one line graph of the top five zine genres over time and small multiples to illustrate the top ten individually. I don't know what happened with the missing lustra heading on Literary and Split Zines, so I'll figure that out for the final presentation. Another fix I need to make: the colors changed because I started a new workbook. 

The small multiples give a good snapshot of how each genre's representation in the Barnard Zine Library changed over time. 

### Gantt Chart

{% include gantt.html %}

If the embed link isn't functioning in your browser, here's a link to the 
[visualization on Tableau Public](https://public.tableau.com/profile/jenna.freedman#!/vizhome/Assignment3-dispersion/DispersionPlotDashboard). 

#### Data Decisions





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
