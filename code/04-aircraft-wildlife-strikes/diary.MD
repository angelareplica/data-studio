Steps:

-Download the entire FAA wildife strikes database

-Convert .accdb to several CSVs; read in pandas and merge the CSVs

-Explore the data and read through its documentation. Unfortunately, the data often doesn't cohere to what the documentation says..

-Create some simple charts:
-Bar chart showing the number of wildlife-aircraft collisions per year. There's a noticeable upward trend here. Look for comparison data on whether air traffic is going up/more flights are occurring.
-Bar chart showing which airlines are involved in the most wildife strikes
-Bar chart showing what animal species are involved in the mostwildlife strikes
-Bar chart showing which airports are involved in the most wildlife strikes

-More charts -- this time focused on repairs costs:
-Bar chart showing which species are the costliest to hit
-Bar chart showing the total money spent on wildlife-strike aircraft repairs each year

-I'd like to create a stacked bar chart showing which types of operators are involved in crashes -- military, commercial, private, government, etc -- but the documentation does not match the data. The data does not break them down so cleanly -- instead, it has the names of the airlines instead of the type of operator under the "OPERATOR" column. 

-I'd similarly like to create a stacked bar chart showing the proportion of species types involved in the crashes -- bird, terrestrial animals, etc.



-Looped through every species listed to assign "terrestrial" or "bird/bat" to it. I think I was pretty thorough, but it's definitely possible that I missed some terrestrial birds or overlooked something, since there were over 700 speices listed.

-Created two stacked bar charts: one showing the proportion of bird/bat and terrestrial animals hit overall, and one showing bird/bat and terrestrial animals in collisions that caused damage.