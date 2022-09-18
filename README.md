# bikesharing

## Overview

The purpose of this story is to convince investors that a bike-sharing program in Des Moines is a sound business venture. One of the key potential
investors has aked to see a bike trip analysis.

The anlysis began with a cleaning of the raw data. Pandas was used to change the "tripduration" data from an integer to a datetime datatype. Then, several visualizations were created using Tableau to tell "the story" of the NYC Bike Share experience.

## Results

The analysis begins with a look at the most popular starting locations for this particular bike share business in NYC. It is observed that Mahhattan
has a large amount of activity, most likely due to tourism.
![Top Starting Locations](https://user-images.githubusercontent.com/106849689/190923664-afa9cb7f-e260-483f-a15e-141e1279c216.png)

Next we look at what times of the day bikes are being checked out. According to the plot, it looks like many bikes are checked out closer to midnight than any other time of the day.
![Popular Checkout Times](https://user-images.githubusercontent.com/106849689/190923744-e80225d6-0a41-458b-8422-3994452e9bf3.png)

We can also dig deeper into the bike check out times by looking at what gender checks out these bikes at certain times of the day. It looks like more men
check out these bikes at the peak hour of midnight than women.
![Popular Checkout Times by Gender](https://user-images.githubusercontent.com/106849689/190923884-d2ec1d43-eff0-47dd-8e92-3295fe2e89cb.png)

This heatmap shows that more bike trips are taken Monday through Friday, in the morning, approximately 8am, and in the evening, between 5pm and 6 pm. 
![Trips by Day Time](https://user-images.githubusercontent.com/106849689/190923963-5e40b8c8-4e3f-41ba-acc5-05d9d391ccc5.png)

We can look closer at this heat map and notice that more men take trips Monday through Friday during the hours of 8am, 5pm and 6pm.
![Trips by Day Time by Gener](https://user-images.githubusercontent.com/106849689/190924073-9fa910b4-c9d2-4c3c-b946-dbc3fd9f0957.png)

Looking at this gender data in a slightly different way. We can see that more men use these bikes during the week than women, and that more men are 
subscribers this this service than women.
![Trips by Day by Gender by User Type](https://user-images.githubusercontent.com/106849689/190924119-597406d9-cc3a-4e6f-9977-491ec820cfec.png)

Thus bubble chart shows us which bikes get the most use. This can help in determining the number of bikes needed in a certain area.
![Bike Use](https://user-images.githubusercontent.com/106849689/190924182-cbaa9172-c11d-48f5-987b-52d98143e33b.png)

This treemap is a good way to track which bikes need repair.
![Bike Repairs](https://user-images.githubusercontent.com/106849689/190924214-ee7c12b9-6b49-4f20-b5eb-caa6aaacdd0a.png)

The link to the analysis can be found here:

[https://public.tableau.com/views/Citibike_16633777624290/NYCStory?:language=en-US&:display_count=n&:origin=viz_share_link]

## Summary:

The overall analysis shows that a bike share company is a viable concept in a city that has many users. Des Moine could be a successful location 
for such a business. A couple of pieces of data thay may be helpful in making the decision to invest in this company would be:
- The averave distance between the bike stations. If the distance is too far, then there may be a chance that the bikes will not be used.
- The trips by age could also be a way of determining if this is a viable business. If the bikes are used more by a specific age group, then ensuring
that age group has an adequate number in the Des Moine area could be a key to success.
