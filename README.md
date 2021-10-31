# UFOs

## Overview
In this analysis, I am using JavaScript, HTML and css to create a web page designed for UFO sightings. I am given a javaScript file filled with sightings information to start the analysis. I built the functionality for filtering, and table information in JavaScript, the styling in css, and the webpage interface in HTML (e.g., table, jumbotron, header, text boxes, etc.). This was my first time using JavaScript, HTML, and css. The project really came along and looks neat. 

## Results
To use this webpage, one can scroll through the table. To find filtered data, one can use the filter search on the left-hand side of the page. Typing in a filtered criteria and moving the curser our side of the box will issue a change event in the JavaScript code auto filtering the table.

#### Unfiltered text box. 
Light grey words are placeholders in the text box and don't filter the image.

![Code_Example](/static/images/Unfiltered_filter_box.PNG)

#### Filtered on State "CA" and Shape "Triangle"
Notice how "CA" and "Triangle are slightly darker text than the placeholders in the other filter text boxes. The table to the right shows the table filtered on the parameters in the filter box.

![Code_Example](/static/images/Filtered_on_CA_and_Triangle.PNG)

## Summary

Two draw backs of this new design include:
- The user is guessing what parameters to search on. There is a high possibility of typing in a city that doesn't exist.
- The user can't filter on multiple dates, states, etc. 

Future enhancements could include:
- A drop down or auto completion for filtering parameters.
- Adding filtering capabilities on duration.  
