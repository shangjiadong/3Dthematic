# 3D Thematic Map of Travel time to Portland International Airport

> The 3D map GitHub Page can be found [here](https://shangjiadong.github.io/3Dthematic/index.html)

## Introduction 

This map is created based on the simulation results generated from VISSUM. The base framework is Provided by Portland Metro. And the project is supported by Cascadia Lifeline Program (CLiP).

**2D or 3D**

Most map we see is 2D map. It is easier for us to locate the place. It only can render x and y coordinates while another dimension of information is displayed by color, or shape to distinguish from other objects. If we want to display elevation information, we need to use color, or contour to mask the object. However, if we use 3D map, we can directly render the elevation with polygon height.

The other reason to use 3D instead of 2D is when the data dimension is too high. For example, we need to display the frequency that multiple events that happened over the past few years. Then use color and shape is not enough to accurately communicate the message, or it will be too messy to be aesthetically pleasant. 3D would be a good option that the height can be a good feature to display one dimension of information.  

According to [Human Factors Blog](http://humanfactorsblog.org/2010/01/22/3d-is-better-than-2d-right/), "3-dimensional displays (like a perspective view) are perceived to be more natural and possibly require less mental integration than 2-dimensional displays (see this very well-researched. Some of the logic goes like this:  when I view a 2d map, I usually turn it into a 3d representation in my head.  Showing a 3d representation removes this step (in addition to showing more information)". 

A great example of 2D map is [Google Map](https://www.google.com/maps), the application can quickly help people locate the destination. This is helpful when people only need the geographic location of the place. However, Google map also has street view, this helps people to go into the environment to explore around. And also help to identify the place based on his/her recognition of the geographic feature.
Also, when you need to view a large region, like world-wide, 2D map seems to be a more feasible option. The map contained in [this](https://www.boredpanda.com/interesting-maps/) page all looked at the information world or country wide. Using 3D map will make the map very messy. 
[This](http://www.arcgis.com/apps/Styler/index.html?webscene=91b46c2b162c48dba264b2190e1dbcff&menuslides=true&activepanel=slides&title=Interesting%20Places%20in%203D&subtitle=Take%20a%20tour%20around%20the%20world&bgcolor=rgb(150,80,10)&opacity=.5&theme=custom&layout=bottom)3D map is very cool, it takes you to different cool places in the world. When these information are displayed in 3D, you can relate to the content, as like you were actually there or you are watching it very close. This creates a good virtual experience. 