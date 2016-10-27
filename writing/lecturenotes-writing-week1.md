# Writing class notes week 1
#

##Introductions
* You, 
* Us,
* Goals for the course

## Readings

#### Elliot Jaspin, [racial cleansing story](http://historynewsnetwork.org/article/35847)

We aren't reading the book, Buried in Bitter Waters, and the stories are difficult to find. But this story goes through how he found the story. Discussion around the process of using ideas, questions, etc. lead you to data work, rather than the other way around. What questions do you have about New York that could drive a data story, that is more of a narrative rather than a study? (Note that "turn of the century" in this piece means 1900, not 2000. )

Good stories in archives, history? 

#### [Donald Trump spending story](http://www.nytimes.com/2016/02/06/us/politics/donald-trumps-campaign-billed-as-self-funded-risks-little-of-his-fortune.html), from the primaries

An example of short-term news folo, about a week or two after a filing deadline. How did we put together the numbers in a way that gave you a good sense? It's not like there's some button that says: "here's how you put together his spending on his own companies with his loans..." What had to go into that? 

Talk about how a numbers-heavy story is written, organized.

What order do you do things in? Street reporting, writing, data -- and how do they interact in a story like this? 

In this case, we had the broad outline of the data -- we knew how much he'd loaned himself, how much spent on hats, etc., how much spent on three companies that are related. So the top line data part is done at that point. It might not be all the way complete, but know there is a story. Then start sketching out the story and write sentences we want to fill in with data. While doing that, notice other things that we find interesting. 

#### [Police diversity](http://www.nytimes.com/2015/11/08/us/politics/police-chiefs-looking-to-diversify-forces-face-structural-hurdles.html) story 

Walkthru

#####Underlying data sets:

[Law Enforcement Management And Administrative Statistics (LEMAS)](http://www.bjs.gov/index.cfm?ty=dcdetail&iid=248)

The Justice Department routinely does a survey of law enforcement agencies, but changes the questions each time. We'd found the data after the Ferguson police shooting, but it only went through 2007, and used it for [this graphic story](http://www.nytimes.com/interactive/2014/09/03/us/the-race-gap-in-americas-police-departments.html).

We knew a newer version was on the way because I’d tracked down the form they were going to use through reginfo.gov. I had already gone through the form to see what might be interesting. But when we got the data, we were sorely disappointed -- there was no detail at all about what they meant by use of force, and major departments didn’t fill it out at all. 

The first story we did when it was released was not the diversity story. It was a story on use of force data, which no one else knew even existed. 

It was really frustrating: 
[“Data on Use of Force by Police Across U.S. Proves Almost Useless“,](http://www.nytimes.com/2015/08/12/us/data-on-use-of-force-by-police-across-us-proves-almost-useless.html) August 11. 


##### What did the data look like? 


Here is the [record layout from ICSPR](https://www.dropbox.com/s/4gowsv40tubz2tk/lemas2013_codebook.pdf?dl=0), a University of Michigan data repository that houses all of the Justice Department statistical surveys. This complexity is pretty typical of what’s called “microdata”, which is the individual responses to surveys like the Census. There are usually a lot of coded variables, but in return it’s pretty clean. We’ll compare to other things next. 


BUT one thing that is missing: a government code or something that would let me match up with the population served. Even though they selected their sample from the universal census of law enforcement agencies, they declined to put the code back into the data. This is why the diversity story took longer.

Here’s a piece of it that shows the[ use of force data](https://www.dropbox.com/s/6dk2eip8ft2hqag/uof_20150803.xlsx?dl=0), just for the largest (500 officer + ) agencies.  Given the number of large departments that didn’t report, and that there was no historical data to compare it to, there was little left to do but report out what we saw. 


#### The diversity exercise

##### Check understanding of the data and weighting scheme.

The Justice Department had published a summary report on part of the datasets in June, so I checked to make sure I could match their numbers. I could. 
 
##### Match back to jurisdictions to get population

This was the hardest part - there was no unique identifier, so we had to do fuzzy matching back to a state, place or county subdivision in the Census, then merge them all together. 

##### Look for outliers and trends

We'd talked about the challenge of turning this story into something more than "here's some updated numbers." In fact, that's why it took so long -- we were having trouble getting motivated since we didn't really see any news in the overall trends, which were the same as in 2007.

In an effort to salvage the story, I started just looking at any agency that covered a community with at least 50% black residents, but less than 20% black officers. (a difference of at least 30 percentage points) and just started Googling the cities -- and found Inkster! We knew we'd found the hook for the story, and were lucky that Chief Riley had just started his job over the summer.

##### How is the story written?

Go through the story and see how we weaved the data in with the other sources. It has expert comment, other examples, voices, and anecdotes along with data.

## Lede-writing exercise: New York crime reports

The NYPD doesn't give much background on its CompStat report. These are crime reports written up by the police department. Any crimes not reported or seen by police are not included, such as domestic or sexual assaults never reported to the police. The "Part I" crimes -- the seven serious felonies -- are defined by the FBI. The lower level crimes (Transit, Housing, etc.) are crimes that NYPD chooses to publicize. You'll notice there are plenty of crimes untallied, such as any drug arrests. 

Your job is to find a newsy tidbit every week from the Compstat crime data published by NYPD. Take 15 minutes to explore the data here
[https://compstat.nypdonline.org](https://compstat.nypdonline.org)

To get a sense of what they are talking about, it's a little easier to read one weeks' report -- this is what you're choosing from: 
[http://www.nyc.gov/html/nypd/downloads/pdf/crime_statistics/cs-en-us-city.pdf](http://www.nyc.gov/html/nypd/downloads/pdf/crime_statistics/cs-en-us-city.pdf)

Write a lede for this week, or for an enterprise story you would finish reporting, based on this data.




