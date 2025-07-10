<a href="https://www.juncture-digital.org"><img src="https://juncture-digital.github.io/juncture/static/images/ve-button.png"></a>

<param ve-config 
title="St. John's Wort"    
source-image="https://upload.wikimedia.org/wikipedia/commons/d/d0/St._John%27s_wort_%2850050399481%29.jpg"   
banner="https://upload.wikimedia.org/wikipedia/commons/d/d0/St._John%27s_wort_%2850050399481%29.jpg" 
height=100
author="Kate Kaufman"
layout="vertical">

### This is a basic map

Have a comma but no space between your longitude and latitude.
<param ve-map
	   center="38.91588,-77.06338"
	   zoom="16"
	   caption="This is the location of Dumbarton Oaks in Washington, D.C.">

You can put a QID from Wikidata instead of coordinates.
<param ve-map
	   center="Q9679"
	   zoom="10"
	   caption="This is the Isle of Wight.">
	   
Additionally, you can use the url from openstreetmap.org which gives you the coordinates.
<param ve-map
	   center="42.37364,-71.11643"
	   zoom="15"
	   caption="Here's Harvard University.">
	   
	   
Using geojson.io, you can also add arrows and highlighted sections, along with map markers: images pulled from wikimedia commons. Use the draw polygon button, click on the polygon to change color and line width, then click save. Copy the generated code from the right-hand side and paste it into github
<param ve-map prefer-geojson
	   center="19.62,-42.73"
	   zoom="1.85"
	   caption="This is a map of SJW's transition from Europe to the U.S.">