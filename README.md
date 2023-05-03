Download Link: https://assignmentchef.com/product/solved-cpsc583-project-3
<br>
In programming assignment 3, you work with and modify an existing visualization created with D3. The goal of the assignment is to learn about designing interacti0n and implementing interaction using D3.

<h1>MODIFYING THE CODE</h1>

It is quite common to provide brushing and linking in visualizations. In this assignment, you are tasked with adding interaction to an existing D3 visualization. Run-time performance is not important. The task consists of the following steps.

<ol>

 <li>Take the provided code and make sure that it works. Easiest thing (which also helps in the next steps) is to create a new WebStorm project and add all three files to the project root.</li>

 <li>Using WebStorm (or your preferred programming environment), explore the code in index.html.</li>

 <li>Try to understand how countries are identified in the data files and in the produced SVG output.</li>

 <li>Implement a “hover tool-tip” to show country name as well as both male and female life expectancy on the scatterplot and map. Follow the style a<a href="http://bl.ocks.org/d3noob/a22c42db65eb00d4e369">t </a><a href="http://bl.ocks.org/d3noob/a22c42db65eb00d4e369">http://bl.ocks.org/d3noob/a22c42db65eb00d4e369</a><a href="http://bl.ocks.org/d3noob/a22c42db65eb00d4e369">.</a>  Ensure you cite the example’s code where/if you make use of it.</li>

 <li>Design a simple interaction for selecting elements in the scatterplot and how the map will change based on the selection. This interaction should also include a means of deselecting elements.

  <ol>

   <li>An example of a possible interaction would be that when a scatterplot datapoint is clicked the country’s colour on the map is changed and a thin line is drawn from the scatterplot point to the country (to assist in visibility for tiny countries). The colour returns to normal and the line disappears when the scatterplot point is clicked again for deselection.</li>

  </ol></li>

 <li>Implement this interaction.

  <ol>

   <li>Use console.log() to see the results of your selection/deselection.</li>

   <li>Update the map based on the selection/deselection.</li>

  </ol></li>

</ol>

<h1>NOW FOR YOUR REPORT</h1>

<ol start="7">

 <li>Describe your implemented design and how the interaction works. Take screenshots from the visualization and illustrate the steps of the interaction by annotating them. Then describe how you altered the code to achieve this.</li>

 <li>This design description is important; do not neglect it as it will be weighted almost equally to the implementation. It will be marked based on the clarity of description and the suitability of the interaction and visual elements.</li>

 <li>Describe a more advanced interaction design for this map and scatterplot. Use images from a mock-up (sketches or from visualization tools such as Tableau, Data Illustrator, etc.) to illustrate the steps of the interaction by annotating them.  Then describe why this is an improvement over the interaction described previously in Step 7.</li>

</ol>