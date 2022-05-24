# Overview of UFO Sightings project:
Create a table in JavaScript that allows a more in-depth analysis of UFO sightings. Allowing users to filter for multiple criteria at the same time on Dana's already working webpage and dynamic table. In addition to the date, I added table filters for the city, state, country, and shape.

## Resources
- Data Source: data.js (UFO data)
- Date Tools: JavaScript "standard", JavaScript version ES6+
- Software: HTML/CSS, JavaScript, Visual Studio Code, BootStrap

## Results / How to use the new webpage:

### Visit the created webpage: https://azykan.github.io/UFOs/
![Index page](https://user-images.githubusercontent.com/97486216/169737750-81869d6c-a0f4-418b-8ec4-923724fb34f4.png)

### Visit Filter Search Table
- Enter desired search criteria in the table.
![Filter table](https://user-images.githubusercontent.com/97486216/169742135-c31b338e-a65a-4851-92bc-29daf771fe61.png)
##### Search criteria
- For example by city (el cajon). The Date,State,Country, and Shape can be left blank ( just shows the example (greyed out) request.
![el cajon search](https://user-images.githubusercontent.com/97486216/169740734-8463c5e3-00dd-4e34-bdbb-debc9b23ab21.png)
##### Filter
- Select Filter button. Or hit enter

![Filter button](https://user-images.githubusercontent.com/97486216/169742511-6deed82b-5785-4959-b58e-eb76943017c9.png)
##### Clear
- Clear table to start a new search:
![Clear table](https://user-images.githubusercontent.com/97486216/169742999-de067b35-4d2a-4c38-a197-ddc5bc8f186a.png)
# Summary
- One drawback of this design is the difficulty for the user to know what parameter to use for the filtering. 
-- For example, to pick a city, the user would have to go through the table and find the city desired for the analysis and key the exact spelling.
-- The user would also have to know that they must use backslashes (/) in the Date filter for it to return any data.
# Recommendations for further development 
- (1) To reduce the confusion of what is being searched, remove the dithered out (greyed out) pre-populated search example request.
- (2) Allow any combination of date format to be entered.
- (3) Ultimately a drop-down list including all available filter values should be implemented.
