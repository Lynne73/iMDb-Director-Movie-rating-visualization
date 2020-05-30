# iMDb-Director-Movie-rating-visualization
The entrance webpage is “index.html”.

**User Guide**
### Entrance page
Open the html document called “index.html” with a standard web browser (chrome or firefox), you will see a web page containing four two main sections.

### First part
![(PLOT1: First secontion is shown as a gallery)](/report_plots/plot1.png)
The first section is made up of four pictures, each picture will redirect you to the topic that you are interested in.
For example, if you want to know more about directors’ information, you can choose to see the link contained by the second picture, which also tells you it would be a scatterplot.
This function allows users to have a primitive prediction of what they will see and can choose the topics they are interested in, instead of showing all charts peremptorily.

### Second part
![(PLOT2: second part is shown by three plots)](/report_plots/plot2.png)
The second section is a combination of three plots, which are donut chart, bar chart and line chart. But the difference between this section and the first one is user will see a dashboard, on which these three plots are linked to each other. And this part is about movies’ language information.

### Subpages
In subpages that are about choropleth-map, scatterplot, stacked-area-plot or heatmap, there will be a headline of a general conclusion this chart conveys. For example, in stacked-area-plot, you can see the headline be like this:
![(PLOT3: stacked-area-plot’s headline)](/report_plots/plot3.png)
There will also be an info box about how to properly use this plot.
![(PLOT4: stacked-area-plot’s operating guide)](/report_plots/plot4.png)
Besides, there will be a basic explanation about what you can find from each plot. If you want to explore more, use the charts as much as you like!

### Choropleth Map
If you are interested in every country’s movie number or rating, click on the first picture in the first section, and you will be redirect to a new web page.
As you can see from this page, choropleth map lies in the middle part, and there are two buttons on top of it. If you want to see the distribution of total movie numbers, you can click the corresponding button (or by default), if you want to know more about average movie rating situation around the world, click the second button. 
This map is colored according to the number/rating level. Higher the number is, darker and redder the map will be painted. So you can have a very intuitive impression on the performance of countries. 
![(PLOT5: choropleth map overview)](/report_plots/plot5.png)
For some countries, their area may not be big enough to be see clearly at this size level. So you can also zoom in to see more clearly.
![(PLOT6: choropleth map after zooming in with italy’s detail information)](/report_plots/plot6.png)
If you want to know detailed information, you can hover on this country the country you selected will be highlighted and there will be a info-box telling you the movie number/ average rating.

### Scatterplot
If you want to know the performance of directors, you can choose the second picture from the first section.
![(PLOT7: scatterplot overview)](/report_plots/plot7.png)
Each point in this plot represents a director. The X-axis is average rating, Y-axis is the average vote for each movie, and the radius and color of points both represent the total rating-vote numbers.
As we can see from the plot, most directors does not have many rating votes, only part of them have high popularity. Besides, we can see there are several directors that have very outstanding performance. For example, there is a director who has been rated more than 10,000,000 times and has a 8+ average rating. If someone want to see a movie, he/she is very possible be attracted by this director.
To help users to know which director each dot represents, I added the hover-on function to this scatterplot. So when users put their mouse on one dot, he/she will see the director’s name.
![(PLOT8: scatterplot with hoving on a dot)](/report_plots/plot8.png)

### Stacked Area Plot
If you are interested in the movie genres’ popularity’s change over years, click on the third picture in the first section. 
![(PLOT9: stacked-area-plot overview)](/report_plots/plot9.png)
Here is a stacked-area-plot, each color is a movie type. Because the number of each type varies from each other, I upgraded the traditional stacked-area-plot and made it stack mirror-symetry  so that each genre’s area can be bigger to be seen clearly.
As we can see from the plot, there are two massive drop downs around late 80s and early 90s. It was because of the Big Economy Recession happened in western world. In US, Canada, Australia, UK, Finland as well as many other developed countries that produces large number of movies, their economy was in the doldrums until early 90s. It well explained the sharp decrease in the chart.
The user can also hover on each genre to get it highlighted, so that he can specify the change of this genre more carefully. At the same time, the genre’s name will also pop up at the top of this chart.
![(PLOT10: stacked-area-plot with highlight and detail genre)](/report_plots/plot10.png)

### Heatmap
If you want to know more about a specific movie category, click on the forth picture in the first section. 
![(PLOT11: heatmap overview)](/report_plots/plot11.png)
This heatmap use a color range from green to red to show the rating level from low to high. The X-axis represents main genre, and Y-axis is sub-genre. For example, there is a group that shows the most green color: History + Sci-Fi, means if you want to see a historical movie and you should definitely avoid those whose sub-genre is Sci-Fi. It will be a disaster. But for the combination of Animation + History, it can be very successful. So the audience can rest assured to choose to see it.
What’s more, if the user want to know the specific rating level of a combination, he/she can hover on the combination rectangular to see the detail.
![(PLOT12: heatmap with detailed information of animation + history)](/report_plots/plot12.png)

### Dashboard
If you want to see movies in some specific languages, you can narrow down the choosing range by selecting the second section on the entrance page. And you will be redirected to this web page.
![(PLOT13: dashboard with default overview)](/report_plots/plot13.png)
This dashboard is a linked group consists of three plots, a donut chart, a line chart and a vertical bar chart. The donut chart shows the distribution of languages in movies in the recent 50 years, the line chart show the number of movies made of this language in the last 5 years, and the bar chart shows the number of movies made in these countries/regions of a specific language in recent 50 years.
If you don’t choose any language, the line chart and bar chart will by default be the number of all these languages, if you choose a specific language, these other two plots will be changed to the data that is related to this language.
For example, if you choose English:
![(PLOT14: donut plot in dashboard with choosing english)](/report_plots/plot14.png)
The proportion of English will become bigger so as to highlight and the percentage English takes will shows up.
![(PLOT15: line chart in dashboard with choosing english)](/report_plots/plot15.png)
At the same time, the line chart will show the changing tendency of English , the highest year will be filled with blue and the lowest year will be filled with red. The big number that shows up is the total movie number in the year of 2019.
![(PLOT16: bar chart in dashboard with choosing english)](/report_plots/plot16.png)
As for the bar chart, it will also be changed to English movies only. The height of bars represents the number of movies made of English in the latest 50 years. 
So for audience who want to see English movies, if they want to have more choices, they’d better search in US. If they search in Spain or Belgium, their choices is very limited.
