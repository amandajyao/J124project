# J124 Final Project: California Fire Incidents
For my final project, I worked with the California Wildfires dataset. This dataset contains information on all wildfires that occurred in California between 2013 to 2020.  

## Data Analysis
1. My first question upon looking at the dataset was finding out which year saw the most fires statewide. Generally, I wanted to know how the total number of recorded wildfires varied across the period 2013-2019 from year to year. To determine this, I created a pivot table displaying the counts of individual fires, specifically using the "UniqueId" variable in the dataset, across all "ArchiveYear" values. 2017 saw the most wildfires statewide, totaling 438 fires, while 2014 had the fewest fires over the period examined, counting 117 fires. 

!['firesByYear', 'Number of fires by year'](/firesByYear.png)

2. My next question for analysis was determining which county suffered the most fires over the period. To do this, I created a pivot table counting the number of fires, or the "UniqueId" variable in the dataset, for each county. The results indicate that Riverside county suffered the most wildfires of all California counties over the years 2013-2019. Specifically, Riverside county counted 146 wildfires during the period. 

!['firesByCounty', 'Number of fires by county'](/firesByCounty.png)
!['firesByCounty2', 'Number of fires by county'](/firesByCounty2.png)

3. Next, I wanted to examine the distribution of incidents of major fires across the counties. To accomplish this, I filtered the original data to only include observations where "MajorIncident" is TRUE, and created a pivot table counting the number of fires, the "UniqueId" variable in the dataset, for each county. I found that although Riverside county had the most wildfires overall during the period, it did not have the most major incident fires. Butte county experienced the most major incident fires, counting 28 total over the years 2013-2019. 

!['majorsByCounty', 'Number of major fires by county'](/majorsByCounty.png)
!['majorsByCounty2', 'Number of major fires by county'](/majorsByCounty2.png)

4. After looking into the incidents of major fires across counties, I was curious about the distribution of fatalities across the counties. I suspected that, given Butte county experienced the most major fires, it would also have the most fatalities. My results after creating a pivot table displaying fatalities by county confirmed this; almost half of the total fatalities across the entire dataset occurred in Butte county. Specifically, of the 181 total fatalities recorded in the dataset, 85 corresponded to Butte county.

!['fatalitiesByCounty', 'Number of fatalities by county'](/fatalitiesByCounty.png)
!['fatalitiesByCounty2', 'Number of fatalities by county'](/fatalitiesByCounty2.png)

5. Finally, I wanted to examine the distribution of the total number of acres burned by county over the period. To do this, I first created a pivot table calculating the sum of the "AcresBurned" variable by each individual county. Then, for heightened ease of analysis, I sorted the obtained pivot table in descending order by the column containing the sums of "AcresBurned." Lake county had the most acres burned, at 582784 acres, while Alpine county had the least, at zero acres.

!['sumAcresBurned', 'Sum of acres burned by county'](/sumAcresBurned.png)
!['sumAcresBurned2', 'Sum of acres burned by county'](/sumAcresBurned2.png) 

## Story Summary and Sourcing
### Pitch
Based on these findings, a potential story idea could compare the specific conditions behind why Riverside county experiences such frequent, but less severe, fires with the reasons fueling the extremely high incidence of major fires in Butte county. These two counties are both unique for different reasons: they are unequivocally the leaders in two different categories, Riverside county for the frequency of fires, and Butte county for the magnitude of fires. A story angle could closely examine and compare the characteristics of each of the two counties. Are there similarities between the two counties? On the other hand, what sets them apart from one another that could potentially fuel their contrasting, though similarly serious, experiences with fires? 

### Sources
#### People
1. Rick Bartee — Director of Area 2 North, California Fire Chiefs Association: (916) 774-5825, rick.bartee@calchiefs.org

Under the categorization of counties into divisions and areas by the California Fire Chiefs Association, Butte county falls under Area 2 of the North Division, which is headed by Rick Bartee. Bartee would likely have valuable and specific information regarding conditions in Butte county that make it susceptible to extremely severe fires. 

2. Don Butz - Director of Area 4 South, Caifornia Fire Chiefs Association: (619) 402-0846, don.butz@calchiefs.org  

According to the categorization of counties into divisions and areas by the California Fire Chiefs Association, Riverside county falls under Area 4 of the South Division, which is directed by Don Butz. Butz would almost certainly have highly pertinent information on specific characteristics of Riverside county that make it prone to frequent fires. 

3. Dan Stefano - President of the California Fire Chiefs Association: (714)754-5144, dan.stefano@calchiefs.org

As president of the California Fire Chiefs Association, Stefano would be able to provide more general and broad information regarding wildfires within the state at large. He represents a key authoritative source for the story. 
#### Additional Sources
1. [Another source](https://www.ncdc.noaa.gov/cag/county/mapping/4/pcp/201902/1/value) I would want to employ is detailed data regarding the climate of Butte and Riverside counties at various times of the year, and examining what the climate indicators are like in the two counties during peak fire season. This data comes from the National Oceanic and Atmospheric Association. 
2. In addition, I would also like to use the [fire hazard severity zone maps](https://osfm.fire.ca.gov/divisions/wildfire-planning-engineering/wildland-hazards-building-codes/fire-hazard-severity-zones-maps/) hosted by the Office of the State Fire Marshal. This data would allow me to be more specific and exact when discussing areas in the two counties that are particularly high-risk for fires. 

## Data Visualization
[!['map', 'Map of fires by county'](/map.png)](https://datawrapper.dwcdn.net/EMVtJ/1/)
