# Midterm_Exam_Q8
Using your choice of a geospatial API, create a web map that visualizes at least two datasets of your choice and includes an analysis component
-
-
# Google Heat Map -- Grocery Stores in the United States
Trader Joe's Locations and Aldi Locations---Amanda's Favorite Grocery Stores----*Data compiled from POI Factory

<https://anorton3.github.io/Midterm_Exam_Q8/stores/>
-
-
1. Choose at least two datasets with relevant data points on topics of interest , describe each dataset in a short paragraph, explaining their significance and how they relate to each other. 

2. Create JSON objects based on your chosen datasets. 

3. Place markers on the map using the data from your JSON objects. Each marker should correspond to a data point from your datasets. For each marker, create a popup that displays the location name and other data fields from the JSON object.

4. Perform analyses or visualizations using both datasets, choose the analysis methods that best suite your datasets and clearly explain your approach and findings in a short paragraph.

5. Add layer controls that allows users to toggle between several layers, and switch between different tile layers (e.g., satellite view, street view)
-
Answers to the above questions:
1. The two data sets that I chose for this map came from POI factory and describes the locations of two popular grocery stores, Aldi and Trader Joe's. Each dataset contains the coordinates (latitiude and longitude) for the stores location, as well as the name (Aldi or Trader Joe's), the city, the state, and the zip code. Specifically for Trader Joe's, the data set also contains the phone number for the store. Aldi is commmonly used by consumers looking for discounts on food items. Trader Joe's is a unique grocery store that sells only their brand, has high qulaity products, and is also budget-friendly. These stores have become quite popular recently due to their budget-friendly prices and availability when applicable. 
2. JSON examples used to create the map:
   For the markers: {position:{lat:33.249024,lng:-86.808446},title:"ALDI-Alabaster,AL---113 Simmsville Rd, Alabaster,AL 35007-4100"},
   For the heatmap: {name:"Trader Joes - 205 Summit Blvd, Birmingham",lat:33.447226,lon:-86.731256},
3. Each marker displayed on the map contains the name of the store, the location/address, and for Trader Joe's the phone number to each store.
4. A heat map was created to display where each store is located and the density for each store. To my surprise, Aldi is commonly located on the Eastern side of the United States and is infilitrating the Mid-west more. The only area were Aldi is located in the West are large populated areas in California and Arizona. The dataset contain 2,364 store lcoations in the United States, none of which are located in Wyoming. As for Trader Joe's, they are more widespread but sparse in number of stores, a mere 559 store locations. From the map it appears that the Trader Joe's store locations are in major cities, such as Denver, Seattle, Las Vegas. This store doesn't have a large presence due to the number of locations. From the map, the states that have neither store are as follows: Wyoming, Montana, Alaska, and Hawaii.
5. Toggle features present on the map contain buttons to switch between Trader Joe's and Aldi location for the heatmap layer. The tile layers contain satellite with labels and generic map with terrain and roads present. 
