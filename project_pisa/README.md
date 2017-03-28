# Summary
The visualization explores PISA 2012 results of students in 65 countries. It shows that students from OECD countries do not necessarily perform better than their peers from non-OECD countries, whether it is in maths, reading, or science. This is despite the fact that countries in the Organisation for Economic Co-operation and Development (OECD) are generally more developed than non-OECD countries. 

# Design
* I decided to use simple horizontal bar chart to compare the performance of different countries in different subjects. 
* I also differentiated the bar fill color for OECD countries from non-OECD countries. This is to make it easier for readers to identify which group of countries performs better in PISA.
* Additionally, I added tooltip on mouseover to display test scores of each country to make it easier for readers to see more details.
* Finally, I added a simple animation that re-sorts the bar chart when readers change subjects. The movement of the bars, or lack thereof, will help highlight countries that consistently put up a good performance in different PISA subjects.

# Feedback
### Feedback #1:
Could you explain OECD somewhere in your paragraph? I could hardly guess what it means from the abbreviation.
### Comment:
I added OECD explanation in the introductory paragraph.

### Feedback #2:
How about adding a legend that explains what the light blue and dark blue stand for? It took me a while until I figured out their difference by resting my mouse on the boxes.
### Comment:
I decided to add a legend just below the chart description so that it's easier for readers to differentiate OECD and non-OECD countries without mouseover.

### Feedback #3: 
For countries you want to emphasize, it would be nice if you could make their names bold. It would make me easier to verify your conclusions.
### Comment:
I decided not to incorporate this feedback in the final index.html file to minimize clutter in the visualisation.

# Sources
1. PISA 2012 Technical Report: https://www.oecd.org/pisa/pisaproducts/PISA%202012%20Technical%20Report_Chapter%2016.pdf
2. PISA 2012 Annex A: https://www.oecd.org/pisa/keyfindings/PISA2012-Vol3-AnnexA.pdf
3. Using d3 to add tooltip to bar chart: http://bl.ocks.org/Caged/6476579
4. Formatting numbers using d3: http://bl.ocks.org/mstanaland/6106487
