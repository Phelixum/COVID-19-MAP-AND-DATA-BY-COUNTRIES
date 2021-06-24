# COVID-19-MAP-AND-DATA-BY-COUNTRIES

COVID-19 MAP AND DATA BY COUNTRIES

This is a modest COVID-19 worldwide data tracker based on p5.js. It displays up-to-date information about current cases and is using web scraped data to achieve this. It is based on 2 p5.js sketches, one displaying the map and the other displaying the data. I was trying but couldn’t connect them into one full sketch.

“COVID-19 Data” sketch has a country search bar implemented, allowing to search any country’s up-to-date information. In order to refresh the page, just restart the sketch.



“COVID-19 Map” sketch shows the current total cases as a percentage chart that displays data in a form of bubbles that have a different diameter, therefore displaying how big are the country’s cases compared to the total world cases. The diameter starts at 0.6 and goes up to 29. This can easily be changed in line 37 in sketch.js.


The data collected is based on Heroku API:
https://coronavirus-19-api.herokuapp.com/all
https://coronavirus-19-api.herokuapp.com/countries

Sketches:
COVID-19 Data: https://editor.p5js.org/Phelixum/sketches/9_JzejRcn
COVID-19 Map: https://editor.p5js.org/Phelixum/sketches/jy8-6_DTF


