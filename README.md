JEM207 Data Processing in Python, Final Project, 
Onďřej Charvát, Richard Karolík

Our first topic proposal was more related to summary of the surf forecast. However, during the process of scraping of the website
www.magicseaweed.com we run into troubles. First big trouble was the html code hidden behind java.script, we manage
to oercome this problem, although then there was trouble with not straightforward html structure so we decided, to make
out project based on the data from the website worldsurfleague.com

Our analysis of the Championship Tour data will take you littlebit into the surfing world. We gathered almost every relevant information 
about the contestant from the last season. To scraping, we developed class Athletes(), what we used for downloading data.

Then we looked at the data and got rid of all outliers, missing values or some mistakes, which could break our analysis.
After initial cleaning, we moved to the visualisation. For the visualisation we used mainly package Plotly, what we found
very usefull and interactive.

As a last step, we commented on our results and our approach.