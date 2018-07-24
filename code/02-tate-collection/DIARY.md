After focusing my previous project on the gender diversity of artists MoMA's collection, I've decided to look into other high profile art institutions. (This is the last art-museum-gender project from me for this class, I swear! Unless the Met makes more of their data available... in which case, I would love to answer the age-old question posed by the Guerilla Girls, "Do women have to be naked to get into the Met Museum?")

The Tate seems like a pretty progressive museum: They even publish gender pay gap and diversity reports about their workforce. But does their collection reflect their stated values? A cursory analysis below shows that their collection is 96% male, 4% female. That's pretty bad. I'd like to look into their acquisitions over time, as well as what kind of works (e.g. medium) they tend to acquire by male/female artists.

---------------
STEPS
----------------

-Looked at the data in pandas
-Merged two of the Tate's data sets: artwork data & artist data
-created a new "acquisition date" datetime column
-resampled and plotted acquisitions by gender over time
  -problem here: in 1856, it looks like they acquired. The museum didn't open until 1897, so this spike may be from Henry Tate's private collection
-Looking into the data more, the huge spike in 1856 appears to be mostly JMW Turner works. At around 40,000, the Tate owns the biggest collection of works by JMW Turner.
-Replotted acquisitions by gender over time, this time beginning in 1897. This gives us a better idea of the gender ratio of acquisitions since the museum opened to the public, but doesn't accurately reflect the museum's entire collection
-Plotted bar graphs showing the gender:
  -one reflects the entire collection (up until 2014, when the dataset ends): 96% male, 4% female
  -one reflects the collection with acquisitions after 1897: 91% male, 9% female. Not that much better!
-Plotted pie charts of most common mediums for male and female artists. Not very noteworthy
-Plotted bar charts of the nationalities of male, female, and all artists from the collection: Not very interesting, since the Tate is predominantly British art
-Looked at the years of birth for male and female artists, but again, the data was skewed heavily by the JMW Turner works, since his birth year (1770) showed up nearly 40k times
-Decided to pivot the previous plot to be a bar chart based on death year (if null, they're still alive as of 2014). 
  -works by female artists are 49% by dead artists
  -works by male aritsts are 89% by dead artists
-Turned my gender split bar chart into a waffle chart. Did this because it's larger and more visually impactful, and I think it will be more amenable to annotation. It'll be easier to show the scope of the collection, and to point out that JMW Turner accounts for a large part of it.