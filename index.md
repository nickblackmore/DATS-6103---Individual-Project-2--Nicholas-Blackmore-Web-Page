## Trends in Severe Weather Events in the United States

Lately there has been considerable attention amongst climate scientists given to the seemingly growing unpredicatbility of the climate. Many scientists assert that anthropogenic  climate change is responsible for an increase of "severe" weather events. In this project, I will explore directly whether this perceived increase in frequency corresponds with an increase in economic damage due these climate events. For the purposes of this project, property damage, crop damage, and number of deaths will be used to determine the 'economic severity' of weather events.

### Data Analysis Process

The weather data I used for this project came from the National Oceanic and Atmospheric Administration and the carbon dioxide level data came from the Scripps Institute. Both the data sets and my code can be found on my github page: [DATS-6103 - Individual Project 2 - Nicholas Blackmore](https://github.com/nickblackmore/DATS-6103---Individual-Project-2--Nicholas-Blackmore), and on Zenodo: . In terms of cleaning and pre-processing the data, my main tasks were adjusting monetary values for inflation; creating a singular metric for 'economic severity' using the Value of a Statistical Life (VSL), monetary value of property damages, and monetary value of crop damage; and combining weather events in instances where they were entered into the dataframe as different events. After I accomplished this, I was able to visualize the data. 

### Visualizations
Below are some samples of the visualizations I used to glean insights about the overall trends of weather events in the United States.

### 1. Economic Damages by Year
<img src="Economic Damages of All Events by Year.png" alt="image not found" class="inline"/>
<img src="Economic Damages of Drought, Heat, and Fires by Year.png" alt="image not found" class="inline"/>
<img src="Economic Damages of Tropical Storms and Hurricanes by Year.png" alt="image not found" class="inline"/>

### 2. Location and Econoomic Damages by Weather Event Category
<img src="Location and Economic Damages of Weather Events.png" alt="image not found" class="inline"/>
<img src="Location and Economic Damage of Tornados.png" alt="image not found" class="inline"/>
<img src="Location and Economic Damages of Floods.png" alt="image not found" class="inline"/>

### 3. Top 10 States Ordered by Ecnomic Damages for Each Weather Event
<img src="10 States with most total damages.png" alt="image not found" class="inline"/>
<img src="10 States with most econ damages from fires.png" alt="image not found" class="inline"/>
<img src="10 states with the most economic damages from hurricanes.png" alt="image not found" class="inline"/>

### 4. Correlation Between Yearly Economic Damages and Co2 Levels
<img src="C02 vs Economic Damages with trendline.png" alt="image not found" class="inline"/>

### 5. Weather Events With the Highest Correlation between Economic Damages and Co2 Levels
<img src="Correlations between economic damages and Co2 levels for each weather event.png" alt="image not found" class="inline"/>


### Conclusion and Takeaways

Floods, Droughts/Heat Waves/Fires, and Winter Weather events all show mild correlations between the economic damages they caused and rising CO2 levels. However, it does not completely resolve the question posed at the beginning of this project. To further this research, it may be useful to see if either increases in temperayure or increases in other greenhouse gases are more correlated with severe weather events. 

Additionally, a 25 year window is probably not a reasonable time frame to detect extremely severe weather events. For example, the term '100 year flood' is used to describe a flood of a certain severity that has an average rate of occurence of once every 100 years. So, if floods as severe as '100 year floods' were occuring twice as often as they used to be, there is only a 39.3% chance that one or more floods of that magnitude would even be observed in a 25 year sampling period. This makes the detection of an increase in this type of extreme weather event difficult. Unfortunately, the longitudinal data that this type of study would require, and with the same level of detail as the dataset used in this project, may be impossible to obtain. 

Finally, it was fairly obvious from the analysis that a large number of extreme weather events occured in areas that the United States relies on for agricultural production (Great Plains, the Mississippi River Watershed, and the Gulf of Mexico). To determine the risk this may cause to the economy, a more focused study of weather trends those regions may be necessary.  


This project is also published on Zenodo at: [Link](url)

