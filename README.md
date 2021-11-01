# Visualization of Dr. JohnSnow's Cholera outbreak map using D3.js

Subject: INFO H517 – Project 1

YouTube video link: [Video](https://youtu.be/uZxJ3R_28Ls)

Introduction:

As part of this project, Dr. John Snow’s map of London’s 1854 Cholera epidemic was recreated using latest visualization tools i.e, D3.js. Various visualizations like bar chart, pie chart, paths, legends were used in the development of this interactive visualization. 

Methods:

Entire visualization can be divided into 3 main plots:

a)	Map: A map of the London was created using the coordinates given in the streets.json file which consists of various streets. Within the map, the location of the deaths was plotted with pink color. The location of the pumps was plotted along with the location of the deaths to see the relationship between pumps and deaths. Interestingly, we can see in the map that more deaths were reported in the middle of the map where there were fewer pumps compared to deaths in other areas. So, its logical to conclude that fewer pumps contributed for higher deaths due to Cholera during the pandemic. On the right side of the map there’s an option for breakdown of deaths by gender and age for better understanding. 

b)	Bar chart: A bar chart was plotted to depict the information of the number of deaths partly in August and September. As we can see in the chart, deaths started to rise from the end of August to mid-September after which there was significant slowdown. Hovering over the map will highlight the bar and their corresponding deaths in the map. 

c)	Pie chart: On the bottom-right corner of the visualization, there are two pie charts that shows the distribution of deaths by gender and age. We can see that both males and females were equally effected by the epidemic. However, significantly more number of deaths were reported in population below the age of 10 or above the age of 80 compared to remaining age groups. 

It’s quite interesting to see the entire visualization come together. 

Conclusion: 

Important findings from the visualization are: 

•	Pumps were one of the main reasons for more number of deaths during the epidemic. More number of pumps could have prevented higher deaths. 

•	Also, there was steep increase in deaths during early September followed by a significant drop. 

•	Younger and older people were more effected than any other age groups. 
