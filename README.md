# "Migrations in Motion" Web Map Essay
<img src="img/Cover of Web Map.JPG"/>

Caption: screenshot of the cover of the web map. Here is the [link to Web Map!](http://maps.tnc.org/migrations-in-motion/#4/45.58/-117.86)
<br><br/>

<h3> Introduction </h3>

The goal of the map was to help scientists and the public see the changing habitat locations of thousands of vertebrates due to climate change. The predicted corridors for animal travel can then be used a reference for scientists and public figures to enact change and change construction methods to ensure these corridors are not completing blocked for the animals. The more the human landscape inhibits the travel of animals the more animals that will die from climate change because they are not able to travel to the new region with their needed climate for survival. As determined by examining the web map we are able to determine there are large migrations of animals from the South East of the United States to towards the North East. There are also multiple large migrations leaving the Brazil region. From the northern part of Brazil, a large migration is moving West out of the country. Another migration of a large number of animals from Southern Brazil is focused on moving South East closer to the coast of South America. A function of the map was to determine corridors with a large influx of animal migration. These three areas that from visually analyzing map seem to have the largest migrations that are predicted to occur. These areas need to be a focus for reform and transition from a human made environment that is almost impossible for animals to migrate through because of the fragmentation of the land from human construction. Humans need to begin preserving areas and routes that animals would be able to use in their effort to find a new habitat because climate change forced them to migrate. The target audience for this type of research is for scientists specifically those doing climate and animal research. Scientists are able to use these findings to support their research in the effects of climate change on animal migrations. Furthering the research and evidence that these events will occur scientists can help persuade change in the government to support city designs that conserve habitats that will be needed for animals that will be migrating to their areas to find a new suitable habitat. Also, convincing government and city designers to create human made features that decrease the fragmentation of the environment, which we are building upon. Fragmentation of habitat from human-made features could be the end for many vertebrates that will be migrating from increased temperatures in their current unhospitable habitats. Climate change will alter the ecosystems around the world and to be able to adapt and survive animals need to migrate. Humans can either help or hinder this inevitable event by maintaining connectivity between the environment's human made features fragment.

<h3>Authors</h3>

This web map was created by a combined effort between University of Washington and The Nature Conservancy. specifically, the map was created by Dan Majka who is a part of The Nature Conservancy's North America Region science team. The visualization of this web map was made possible using information from three previously produced works.
1. wind map produced by HINT.FM

  [Link to Map](http://hint.fm/wind/)

2. earth wind map by cambecc's

  [Link to Map](https://earth.nullschool.net/)

3. Chris Helm's adaptation of cambecc's code

  [Link to GitHub](https://github.com/FreshyLabs/windy)

<h3> Systematic Architecture </h3>

| Roles | Descripition |
| ----- | ------------ |
| Web Client | This web map is available on the open web for anyone to access. So, this web map resides in the cloud. (The external internet) |
| Web Server | The type of database holding all of the GIS data for this web map is an XML database type. There is .css and .js code stored in this server. |
| Web Services | This web map was created using two web services leaflet and mapbox.  |
| Web Data | The data was produced by the University of Washington and The Nature Conservancy researchers. There were three other data products that contributed to producing this map which are listed above below Authors section. |

<h3> Inspection of the Code </h3>
<br></br>
<img src="img/js script.JPG"/>

There are multiple Javascrpit data sets being flowed from the server to the client. There is data created using google analytics that is being added to the web map. Mapbox and leaflet were used to create the interactions on the web map and stored in .js file. leaflet helps make this web map usable on mobile devices.  Data from The Nature Conservancy website is being added to the web map. The web map is provided as an open source website for anyone to access and is protected by cloudflare.

<img src="img/css script.JPG"/>

The unslider is the interactive part of the map with the title and a few pages of information on the project. The .css code references data to produce this function on the web map. The font used in the web comes from google. The layout of the map was created with the help of mapbox.

<h5> Major Libraries in Use </h5>

1. JavaScrpit Library: which is used to create the interactions between the webpage and the user. The multiple elements on the webpage users are able to use.

2. CSS Library: which is primarily used for design of the web page, so the layout of the webpage is easy and comfortable to interact with for the user.

<h5> Does this Project Support Responsive Design?</h5>

The project does support responsive design. As a user you are able to access the web page and have the same interactions with it on your mobile phone as your computer. There are a few things that could be improved so the web page is able to respond better to changing platforms. When opening this web page on your mobile device the interactive pop-up in the bottom left with the addition information about the project does not resize on the mobile. It takes up a large amount of the screen and when holding the mobile device sideways you are not able to read everything available in the pop-up. Additionally, if you move the map too fast on the mobile the thematic layer takes a second for it to reconfigure itself over the new coordinates.

<h3> Data Sources </h3>

1. The Thematic Layer is a raster layer; it is known as the "flow-canvas leaflet-zoom-animated" layer.

2. Leaflet Basemap layers (rasters) which are produced by OpenStreetMap

  - Black
  - Satellite
  - Streets


3. Mapbox Tiles (raster) there are multiple mapbox tiles that make up the base of the map.

<h5> Critique of UI/UX </h5>

My opinion of the user experience (UX) with the web page is overall user friendly. Simplistic design easy to understand functions available to interact with. The pop-up is a simple design with a using a slider to move between information slides. There are three different basemaps avaliable to use depending on user preference. User is able to transition between 7 zoom levels. In my opinion there are only about 3 or 4 zoom levels that are useful for analyzing the data on the map. When you zoom to close it is hard to understand the importance of the animation. Also, when you zoom too far out less data is shown on the image and does not give the user a good idea of the extent of the data to analyze it correctly. Users are able to move through the web page with relative ease by clicking and dragging the map to the location the user wishes to analyze. This web page in my opinion is easier to navigate with the use of a mouse because you can move the map easier. Things that could be done to improve the user experience is let it be able to zoom in and out using a mouse scroller and be able to minimize the pop-up in the bottom left in order to only focus on the map.

My opinion of the user interface design (UI) of the webpage is that is visually satisfying. The three different colors chosen for the different types of vertebrates makes it easy to distinguish the different migration paths. The Black basemap is the easiest to be able to analyze the thematic data overlaying it. The Satellite and Streets basemaps make it harder to see the thematic data over them. When opening up the website as a user I thought this map was only showing data for North America not until I moved the map did I realize that South America data was also included, which I found confusing. The web page should tell the user in the beginning either in the title or by the set zoom level the extent of where the data covers. The pop-up is easy to read and interpret how to work. The legend is easy to read. As the user you are able to recognize that you can use zoom buttons in the top right to change zoom level of map. Once the user hovers over the basemap button they are able to understand they can change the basemap from black to either of the other two.

<h3> Descriptions of the Layers and Features of Web Map </h3>

<h5>Basemap</h5>



<h5>Thematic Layer</h5>

<h5>Interactive Features</h5>

<h5>Web Map Elements</h5>

1. legend which is a list of the three different vertebrates shown in the map

<img src="img/legend.JPG" width="100" height="100" class="center"/>
<br></br>
<img src="img/codelegend.JPG" width="500" height="300" class="center"/>
