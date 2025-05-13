<header>
  
# Welcome to my portfolio!
For my portfolio, I will displaying three different assignments from the semester and demonstrate how I've improved them.

__Note:__
_Please read this on the home page as the web app links will not work otherwise!_

</header>

## Production Assignment #1: My First Web App

For our first production assignment, I decided to use the example data that was provided to us to produce a web app. This web app shows the locations of several wineries across Vermont and New Hampshire. While this ended up being a fairly decent map, it had virtually no interactivity.

<img src=https://github.com/colt6418/webgis-portfolio/blob/screenshots/map1_old.png alt="Original web app">

_The original web app_

<br>
Check out a live version of the original web app <a href="https://umass-amherst.maps.arcgis.com/apps/instant/sidebar/index.html?appid=47d34172b1534044830d4b527b67c8ef">here</a>.

Since this was the very first project I figured this would be the perfect opportunity to go back and improve it now that I have a full semester of webGIS under my belt.

To improve them map, I added the websites to each winery that has one, and categorized the points by whether or not the winery is open. To make the two states stand out on the map, I added a used a shapefile from Esri of the state boundaries and filtered out the other states. To add some functionality, I used the Nearby Web App so that you can use the app to track which locations are nearest to you, or an entered location.

<img src=https://github.com/colt6418/webgis-portfolio/blob/screenshots/map1_new.png alt="New map"> 

_The improved web app with new functionality!_

<br>
Check out a live version of the new web app <a href="https://umass-amherst.maps.arcgis.com/apps/instant/nearby/index.html?appid=c6c753d6edb54458a4985d6f3ec4b6ee">here</a>.

Overall, I believe this version of the map feels more fleshed out, and has a proper purpose.

<br>
## Production Assignment #7: Mapbox

One of my favorite assignments we've done this semester was the Production Assignment #7, especially since I was able to use my own data. For this assignment, I decided to make a map of different pianos I've located on campus. I made this map because I figured it would be cool to have an organized map of all of the pianos on campus, as well as their availability. I gathered all of the data myself; asking around to discover new pianos, tracking down the exact location of each piano, and testing them myself. The map I made for this assignment has the pianos I've located so far, which give a popup displaying information about each piano:

- Name of the location
- Availability of the piano
- Type of piano
- Additional notes on the piano

<img src=https://github.com/colt6418/webgis-portfolio/blob/screenshots/map7_old.png alt="Original Draft">

_The original submitted draft of the piano map_

<br>
Visit the original map <a href=https://colt6418.github.io/Assignment-7-old>here</a>.

In order to improve the map, I used some css formatting to make a title, as well as a quick tip on how to interact with the map to make it more welcoming.

<img src=https://github.com/colt6418/webgis-portfolio/blob/screenshots/map7_new.png>

_The new map, now with a title and instructions_


Visit the new version of the map <a href=https://colt6418.github.io/Assignment-7-new>here</a>.

While I was very eager to make a map of my piano findings, I've always wanted to find a way to let people collaboratively track the locations of different pianos on campus. This brings us to... 

<br>
## Production Assignment #8: Making a Survey

For the third assignment I would like to look at something a little different, being a method I learned to gather spatial data from a collective group of people. In Production Assignment #8, we learned how to make surveys to collect data - including spatial data - from the public. This allows me to expand upon the previous assignment so that I can easily let people add information on different pianos across campus. For the sake of giving an example of what this collected data would look like, I filled out the survey with the data I had previously collected and used in Production Assignment #8.

The original survey allowed the participant to input the location of the piano through either their current location, or the more likely option of submitting a point on the map of the piano's location. Other required questions on the survey include:

- Type of piano
- Public availability of the piano

Additional optional Questions include:

- Specification on piano type if the user selected either 'Upright' or 'Grand'
- Specification on permission required if the user specified the accessibility as 'Special Access Required'
- Any extra notes they want to include about the piano

I made most of the questions optional because I wanted to include options to include more details about the pianos, while trying not to deter people from submitting enough information that would allow me to track the piano myself to gather any additional data I need.

While I believe that this survey sufficiently serves its purpose, I've found ways that I can improve it. For one, I added a link to a map of the submitted data so people can easily check which spots have been submitted already to avoid double submissions, or even if they're just curious. I've also added an 'other' option that allows the user to type in case they find something else such as an organ.

<img src=https://github.com/colt6418/webgis-portfolio/blob/screenshots/survey_picture.png alt="survey">

Check out the survey <a href=https://survey123.arcgis.com/share/632117025b4a4b5da844ff46a177ad06>here</a>!
