
# Analyzing biases in Wikipedia data
## Overview:
This project analyzes bias on wikipedia by computing and analyzing two metric: 
a) # of articles by country's population 
b) Ratio of high quality articles to article count

Analysis involves observing the top and bottom 10 countries for the above two metric. 
Countries that are low on "# of articles by country's population" metric, are under-represented on wikipedia and vice versa. 
Countries with low "ratio of high quality articles to article count" metric have low representation of good quality articles on wikipedia and vice versa

## Quick Start Guide:
1) Download page data from: https://ndownloader.figshare.com/files/9614893 on your computer. This data is provided by Oliver Kyes, Human Centered Design (HCD), University of Washington

2) Download population data from: http://www.prb.org/DataFinder/Topic/Rankings.aspx?ind=14 on your computer. Click on the Microsoft Excel icon on top right corner. This data is available courtesy of Population Reference Bureau (PRB). 

3) Open the hcds-a2-bias.ipynb on this git repository and run steps 1 thru 5. Please ensure you have internet connectivity while you are running the notebook as the code calls ORES REST APIs. ORES is "Objective Revision Evaluation Service" by wikipedia and it provides quality score for a wikipedia article. ORES REST API information is available here: https://ores.wikimedia.org/v3/#!/scoring/get_v3_scores_context 
https://www.mediawiki.org/wiki/ORES

## My personal reflection on the project and data analysis:
1) Countries with very small population such as Nauru are over represented in wikipedia as compared to populous countries such as India and China

2) Surprised to find North Korea to have the most high quality articles as compared to total articles. This could be due to a very image conscious regime influencing the quality of articles by using paid editors

3) Also surprised to find no high quality articles from Switzerland which is a very developed country. This could be opposite the effect of North Korea. Switzerland being a mature democracy, no politician is paying to improve the quality of articles


Data is released under CC-BY-SA 4.0 license

Code is released under MIT license
