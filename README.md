# embeddedChart
html template to embed the chart of an Observable notebooks without the auxiliary cell

The OnlyChart template is used with eg. https://observablehq.com/@d3/choropleth<br/>
  - If you need to change the shown chart you have to modify "chart" (line 15 of chart.html) with the identifier of the desired cell 
  
The Selector+Chart template is used with eg. https://observablehq.com/@d3/bivariate-choropleth<br/> 
  - If you need to change the shown selector you have to modify "viewof colors" (line 19 of chart.html) with the identifier of the desired cell<br/> 
  - If you need to change the shown chart you have to modify "chart" (line 22 of chart.html) with the identifier of the desired cell
  
 The identifier of the desired cell have to be retrieved from the notebook.js
  
