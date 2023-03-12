# Route Anywhere
Route Anywhere is a basic navigation application which is prepared to demonstrate the route direction between two locations.

# Story
The aim was to Develop a demonstration that allows a user to search for a given Point Of Interest near his position and get walking and/or driving directions to it.

# Approach
- The demonstration was started by analysing the requirement and the resources available. 
- The objective was set to develop a simple application and not to build a complex model in this case.
- The resources available were the api's of nextbillion.ai with the required api key.
- The following steps were adapted for building the demo application.
  - The html code of nextbillion's direction api was obtained from code sandbox (https://codesandbox.io/s/fjgq7?file=/v2/directions.html).
  - The html code was tweaked a bit to include origin and destination place holders for user's inputs.
  - The "getCurrentPosition" function was used to get the user's current position using the geolocation api provided by the browser, which will be the input for the origin.
  - The "map.on" function was used in the code, by which the user can select his/her desired destination POI on the map by a single click.
  - The code was checked and run.
  
# Supports Used
- Brackets 2.1.3 - for coding.
- ChatGPT Feb 13 Version. Free Research Preview - for error handling and code understanding.

# How to use the application
- Opening the Application
    - Open the Route_Anywhere.HTML from the Github Repository.
    - Click on Raw.
    - Right click and save as in your desired file path.
    - Now double click and open the saved file.
    - The application opens in your default browser.
- Supported Browsers
    - Google Chrome.
    - Firefox.
- Use Case
    - Click on 'Current Location' button to get your current location as origin.
    - Click on any desired destination POI on the map.
    - Click on 'Request Direction' Button. 
    - The application will generate the direction between the origin and destination.
    - Click on 'Remove Direction' and repeat the above Use Case steps to find the direction to a different POI.
    
# Challenges Faced
- Unable to pull in the Directions, Geocode and Search api into the demo, even though the json call was successful.

# Further Improvisations
- Make a better UI for the application by a professional UI developer.
- Improvise the code to zoom to the user's location once the origin is given.
- Suggest nearby POIs like Restaurants, Hospitals etc. to the user using the search api.
- Add more functionalities like scale bar, lat long display, compass, etc.
- Use distance api to choose the mode of transport and generate the distance accordingly.

# Closure
Overall I enjoyed a lot working on this exercise!
