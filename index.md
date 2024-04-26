## Amenities Accessible From MetLife Stadium, NJ
# Pavithran Balan
# Command-Line GIS 34:970:595 (Spring 2024)

The aim of this project is to understand if the amenities around MetLife Stadium are accessible in a walking distance. 

The datasets used in this project are all MLS stadium locations in USA, Hotels and restaurants around MetLife Stadium, NJ Transit stop location, ACS (2015-2019) Data to extract the number of people using transit as a means of transportation to work. 

All the locations data were directly obtained from Wikipedia and google. The csv file was used and with the arcgis geocoder, all the locations were geocoded and used for analysis. To find the 15 mins walking buffer from the stadium location, Network analysis was done usin OSMnx

Before, jumping in to MetLife stadium, let's look at where the Fifa world cup is happening across USA in 2026

<iframe src="ok.jpg"height="500" width="500"></iframe>

As seen in the image, there are many other states with soccer stadiums. To understand what factor would have gone into account to choose where world cup is hosted, I added the capacity factor to check.

<iframe src="final_stadiums.html" height="500" width="500"></iframe>

As we could see all the stadiums selected for the world cup has higher capacity (>60,000) compared to the non-selected stadiums which had less than 50,000. 

Demographics of Bergen County

Focusing back on the MetLife stadium, it is located in East Rutherford, Bergen County, NJ.

To understand how the transit usage is in the county, I used acs data to visualize the number of people using transit as a means of transportation to work

<iframe src="ok2.jpg "height="500" width="500""></iframe>

As seen above, the transit usage in East Rutherford is very less and in general Bergen county is poor in transit usage showing it's a very car dependent neighborhood. 

Finally, to check what is accessible from the MetLife stadium a walking buffer of 15mins was created 

<iframe src="final_metlife.html" height="500" width="500"></iframe>

The map helps us understand that
  1. MetLife stadium is transit accessible in a walking distance
  2. It is not accessible to hotels even though it's right across from the stadium
  3. It is just almost accessible one Mall/Restaurant
