Overview:


* This repository focuses on data pertaining to parties and noise complaints throughout the 5 boroughs of NYC and my analysis towards it.
* Findings:
   * Found that parties last longer before complaints shut down during summer months.
   * Average hours for each month is mostly high for street/sidewalk parties during summer months and higher for residential building/house parties during cooler months.
   * Average hours for each month is mostly affected for parties in the Bronx while other boroughs aren’t as affected by it.
   * For all boroughs, most parties happened in a residential building/house setting while the least happened in a house of worship setting.
   * The hottest bar scenes throughout the 5 boroughs happen in Manhattan and outer boroughs near Manhattan. In terms of where in Manhattan specifically, it’s mostly in Downtown and Midtown Manhattan while there are some bar scenes in 2nd Avenue on the Upper East Side and at the top of Manhattan near the George Washington Bridge.


Files:


* NYCDSA_Python_Project.ipynb: A Jupyter Notebook file that utilizes Python code in code cells as well as text descriptions in markdown cells.
* bar_locations.csv: A CSV file which contains data based on different parties throughout different bar locations in the 5  boroughs.
* Party_in_nyc.csv: A CSV file which contains data on different parties based on different location types in the 5 boroughs.
* nyc_heatmap.html: An HTML file that has an interactive heatmap so that the user can freely analyze the heatmap as he/she pleases.
* NYCDSA_Python_Project_Presentation.pptx: A PowerPoint presentation that explains the approaches I took as well as shows the visualizations in a nicer way so that the user can have an easier time analyzing.


Data Dictionary:
* party_in_nyc.csv:
   * Created Date: type obj, the date and time that the party started.
   * Closed Date: type obj, the date and time that the party was shut down.
   * Location Type: type obj, the type of location that the party took place in.
   * Incident Zip: type float64, the zip code that the party was held in.
   * City: type object, the city where the party happened.
   * Borough: type object, the NYC borough where the party happened.
   * Latitude: type float64, the latitude coordinate of the party.
   * Longitude: type float64, the longitude coordinate of the party.
* bar_locations.csv:
   * Location Type: type obj, the type of location that the party took place in.
   * Incident Zip: type float64, the zip code that the party was held in.
   * City: type object, the city where the party happened.
   * Borough: type object, the NYC borough where the party happened.
   * Latitude: type float64, the latitude coordinate of the party.
   * Longitude: type float64, the longitude coordinate of the party.
   * num_calls: type int64, the number of noise complaints for each party.


Required Python Libraries:
* numpy
* scipy
* pandas
* matplotlib
* seaborn
* datetime
* folium
* json
* branca
* collections
* webbrowser


Note: To install Python libraries, use this command after opening Anaconda Prompt:
* pip install libraryName


Substitute libraryName with the name of the library you want to install.