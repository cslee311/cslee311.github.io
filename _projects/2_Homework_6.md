---
name: Homework 6 Submission
tools: [Python, HTML, vega-lite]
image: assets/pngs/UFO.png
description: This is my submission for homework 6.
custom_js:
  - vega.min
  - vega-lite.min
  - vega-embed.min
  - justcharts
---


# Visualizations for Homework 6

<vegachart schema-url="{{ site.baseurl }}/assets/json/chart_1.json" style="width: 100%"></vegachart>

"In this first visualization, I am using the UFO dataset to plot where all of the sightings have occurred and show other related details about the sightings. I am specifically highlighting the location of all these events on a map projection and featuring a tooltip that appears when hovering over a point, revealing details such as time, shape, and date of the UFO sightings. I chose to plot all points and the background countries across the equalEarth projection in Altair because I felt as if it would aid viewers in visualizing location compared to using points alone. I also chose to have the fill color set as dark slate grey, borders as white, and points as red to differentiate better the points shown from the background of the map. If I had more time, I would try to make the visualization more aesthetically pleasing overall by doing things such as having a more detailed and colored map, adding more to the tooltip, aligning everything concerning the page, and maybe grouping the points with colors based on attributes given." For this projection, I changed the tooltip, projection, and colors. I added latitude, longitude, and a description fron the dataframe to the tool tip. I changed the color of points to lime, the map to black, and the proejction to equirectangular.

<div class="left">
{% include elements/button.html link="https://github.com/UIUC-iSchool-DataViz/is445_data/raw/main/ufo-scrubbed-geocoded-time-standardized-00.csv" text="UFO Data" %}
</div>

<vegachart schema-url="{{ site.baseurl }}/assets/json/chart_2.json" style="width: 100%"></vegachart>

"For this second visualization, I chose to use a line graph to visualize how many buildings were constructed each year. I filtered the dataset of the main building inventory to only account for buildings that had a recorded year of construction. To visualize this, I chose to make the graph green because I felt as if it went well with both dark and light themes of Hugging Face. I did not do much else to change the visualization other than make the same dimensions as the first because I was satisfied with what I saw. If I had more time, I would make this more aesthetically pleasing by centering the graph concerning the page, adjusting the intervals of the graph, and maybe changing the present background." For this visualization, I changed the markings on the graph and the color it used. I changed the lines to circles and I used red to denote these circles. 

<div class="left">
{% include elements/button.html link="https://raw.githubusercontent.com/UIUC-iSchool-DataViz/is445_data/main/building_inventory.csv" text="Bldg Data" %}

<!-- these are written in a combo of html and liquid --> 

</div>
<div class="right">
{% include elements/button.html link="https://github.com/cslee311/cslee311.github.io/blob/main/python_notebooks/Workbook.ipynb" text="The Analysis" %}
</div>

