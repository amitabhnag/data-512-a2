CC-By# Analyzing biases in Wikipedia data
## Overview:
This project analyzes bias on wikipedia by computing and analyzing two metric: 
a) # of articles per country 
b) Ratio of high quality articles to article count

Analysis involves observing the top and bottom 10 countries for the above two metric. 
Countries that are low on "# of articles per country" metric, are under-represented on wikipedia and vice versa. 
Countries with low "ratio of high quality articles to article count" metric have low representation of good quality articles on wikipedia and vice versa

## Quick Start Guide:
1) Download page data from: https://ndownloader.figshare.com/files/9614893 on your computer. This data is provided by Oliver Kyes, Human Centered Design (HCD), University of Washinton

2) Download population data from: http://www.prb.org/DataFinder/Topic/Rankings.aspx?ind=14 on your computer. Click on the Microsoft Excel icon on top right corner. This data is available courtsey of Population Reference Bureau (PRB). 

3) Open the hcds-a2-bias.ipynb on this git repository and run steps 1 thru 5. Please ensure you have internet connectivity while you are running the notebook as the code calls ORES REST APIs. ORES is "Objective Revision Evaluation Service" by wikipedia and it provides quality score for a wikipedia article. ORES REST API information is available here: https://ores.wikimedia.org/v3/#!/scoring/get_v3_scores_context 
https://www.mediawiki.org/wiki/ORES

## My personal reflection and data analysis:


CC-BY-SA 
