# Radiation-and-Heat
Comparing clear sky radiation and net solar radiation for 24 hours in KNUST, Kumasi-Ghana using Python.

##Procedure
-I downloaded the data sets for both variables separately from the Climate Data Store by inputting the geo-coordinates for Ghana.

-I then used CDO and the outputtab operator to extract the variable data for Spintex alone and piped the output to a csv file.

-I read the files in my python script by using methods from the Pandas python library and manipulated the data into a DataFrame for easy analysis.

-I plotted the graph of the correlation in python by using the Matplotlib libray and saved the output to a png file.

##Conclusion
-From the analysis of the data and visualization, it can be concluded that radiation values for both clear sky and surface net solar radiaton are very low or equal to zero during the early and late hours of the day. This is because, at those hours of the day, the sun has not risen at the position i specified. However, radiation values are seen to increase drastically during the day because the sun rises and stays up during those hours.

-Both clear sky and surface net solar radiation are observed to be very similar and this is because solar radiation at the location i specified is not strongly affected by cloud cover due to the scarcity of absorptive-radiation clouds in that region. 

