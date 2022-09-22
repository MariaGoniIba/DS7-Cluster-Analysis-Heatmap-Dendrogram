# Data Science (DS) project 7: Cluster Analysis using a heatmap and dendrograms
Simple cluster analysis to explore the usability of heatmap and dendrograms, clustering different countries according to latitude and longitude.

# Credit
The dataset and proposal of the exercise is from the Udemy course [The Data Science Course 2022: Complete Data Science Bootcamp](https://www.udemy.com/course/the-data-science-course-complete-data-science-bootcamp/). I highly recommend this course for those learning Python and machine learning.

# Exploring the result
<p align="center">
  <img src="https://github.com/MariaGoniIba/DS7-Cluster-Analysis-Heatmap-Dendrogram/blob/main/Heatmap.png" | width=600>
</p>

Let's extract conclusions. The are 2 features (latitude and longitude) and 6 observations (USA, Canada, France, UK, Germany and Australia). 

The dendrogram on the left side clusters the countries. There is another dendrogram at the top, uniting the 2 features.

The different colours defined the heatmap. Regarding latitude, most colours seems alike, except for Australia. This is because the latitude of the other 5 countries is very close as they are all in the northern hemisphere. Australia is the only one in the southern so the colour is completely different. 
As per the longitude, Germany, France and the UK are very similar. Australia is completely bright while USA and Canada are purple. 
Given the legend we can tell that Canada and the USA are close to each other but different from Europe, and completely nothing like Australia in terms of longitude. 
We can even cluster these observations based on the colours. Germany, France and the UK are very similar regarding both features, so they will be one cluster. 
USA and Canada are almost the same in terms of longitude and slight different in terms of latitude. Australia is completely different on both aspects. 
In the case that we wanted a 2 cluster solution, then Australia would be clearly the outlier.
