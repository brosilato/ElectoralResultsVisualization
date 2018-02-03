# ElectoralResultsVisualization
Author: Adrian Varela-Alvarez
Python notebook intended to highlight the striking differences between presidential and governor elections regarding the ratio of republican/democrat vote. 
Two well-known "liberal" regions of the United States have been chosen: 
1) Washtenaw County, MI. This county includes cities such as Ann Arbor and several universities such as University of Michigan at Ann Arbor.
2) Middlesex County, MA.This county includes cities such as Cambridge and several universities such as MIT and Harvard University.

The general perception about these two counties is that they are very liberal areas where the republican party has nearly nothing to do. 
This is an impression derived from elections at the federal level (for example, presidential elections) and 
the question is it that picture remains true at the state level (governor elections).

Michigan's data comes from the following website:
http://www.michigan.gov/sos/0,4670,7-127-1633_8722---,00.html
Following the links, tab separated values files for all the elections can be downloaded. For example:
http://miboecfr.nictusa.com/election/results/2016GEN_CENR.html

Massachusetts' data comes from the following website:
https://www.sec.state.ma.us/ele/
Following the links, tables with electoral data can be accessed and used to generate csv files. For example:
http://electionstats.state.ma.us/elections/view/40060/

The plot is designed to follow Alberto Cairo's principles of truth, beauty, function, and insight:
1)Truthfulness: The y-axis was not cut (it goes from 0 to 100%). The side to side presentation helps to compare both counties more accurately. All the lines represented 
use the same units (vote percentages).
2)Beauty. The ggplot style was used to get profesional looking plots. Also the traditional colors of the democratic and republican parties were used for the lines. 
Grey filling between lines helps the message to stand up (huge gap between the democratic and republican parties for president elections).
3)Functionality: I have use the same scales for both plots and a grid to easily get rough estimates of the values. Also markers allow for quick identification of governor and 
presidental electoral years.
4)Insightfulness: For both counties there are huge gaps between democratic and republican vote percentages for the president elections, favoring always the democratic party. 
For both counties, democratic and republican vote percentages for the governor elections exhibit wild changes and they cut in some points. 
The behavior of the voters is completely different for each type of elections.