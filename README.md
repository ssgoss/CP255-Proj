Accessible Parking Data in San Francisco
----------------------------------------

### Research Question:

Due to upcoming federal legislation from the U.S. Access Board as outlined in the Public Right-of-Way Accessibility Guidleines, the San Francisco Municipal Transportation Agency will be required to increase the amount of accessible parking (i.e. parking for people with disabilities) in San Francisco to be equivalent to 4% of metered parking. I was curious to use various methods and existing data at the SFMTA and the city to plot these ratios in various geographical boundaries to see where the SFMTA will need to add more accessible parking to meet this target.

### Background:

The Accessible Services team at the San Francisco Municipal Transportation Agency (SFMTA) ensures compliance with Americans with Disabilities Act (ADA) and other relevant regulations on fixed-route transit and capital projects, administers the Agency's robust paratransit programs, and provides technical assistance to other SFMTA divisions on all transportation-related ADA compliance issues. The team also oversees ADA compliance and works to improve accessibility on all bicycle, pedestrian, emerging mobility, and parking projects. 

As part of this last category, Accessible Services works closely with the Agency's Curb Management team to track and site street parking for people with disabilities throughout the city. In San Francisco, accessible parking spaces on public streets are denoted by a painted blue curb and standard ADA-approved R99C signage. As compared to normal street parking, these blue zones have several attributes that make it easier for people with mobility impairments to park and get to their destination in a safe, comfortable, and convenient manner. 

Blue zones are currently only enacted in one of two ways, either as part of larger projects in the Transportation Engineering & Livable Streets division, or via approved public requests to the Curb Management team. As a matter of policy, blue zones requests are never granted in purely residential areas and are typically placed on block faces with metered street parking. 

Blue zones are an essential part of the SFMTA's role in serving the public: there are roughly 187,000 adults aged 60 or older and 38,000 people living with disabilities in San Francisco, , many of whom qualify for the use of a disabled parking placard. Together, these two groups represent approximately 25 percent of the city's population.

Accessible parking is just one of nine distinct designated curbside uses that the SFMTA's Curb Management team oversees. These include white passenger loading zones, yellow commercial loading zones, 5-minute general loading zones, red "no parking" zones, green 15-minute parking zones, free street parking (no paint but sign-posted and often time restricted), and metered street parking. Other teams at the MTA also manage the placement of bikeshare stations, parklets, transit boarding islands, and protected bike lanes, as well as the city's residential parking permit zones, all of which use curb space on public streets. In recent years Transportation Network Companies (TNCs, i.e. Uber and Lyft), employee shuttle programs and food delivery services have also necessitated use of the city's curbs. 

Considering that many of these curb uses didn't exist as little as 10 years ago, this remarkable increase in the demand for curbside space is requiring planners at the SFMTA to rapidly improve the tracking of curbside uses and their associated data. 

The SFMTA currently maintains records of the location of many curb uses, including Accessible Parking in GIS feature classes which it makes available through its website via an online ArcGIS map. I used this data, as well as other data made available through the cities data portal at <https://datasf.org/opendata/>.

### Analysis:

The 2014 Accessible Parking Policy Advisory Committee Report stated that there were 700 unmetered on-street blue zones in the city. Relative to metered parking spaces in the city, the percentage of blue zones has decreased since the 2014 report from 2.5 percent to 2.13 percent. The average Euclidian distance (i.e. as the crow flies) between blue zones throughout the city is 338 ft. (Figure 5)

![](https://lh7-us.googleusercontent.com/Y8uTIA87sBtF5Ylha-yC4w4D_w1C8Nb3M3EG6hN1ny1_q6ZtvyMuBWWMMQa9_LZrosS7bIHX0XbGYkIZ1EdsFc24ZXv1H_4t_hoVk4-mVOrJFWfurTtceonov0nkVjucN3N6I6gZ6RtFWBHkJ0MyDnw)

A heat map of the blue zone reveals concentrations of blue zones in downtown San Francisco, especially around Civic Center and the Tenderloin; north of Market Street between Van Ness Avenue and Hyde Street; along the Embarcadero; in SOMA between I-80 and 6th Street;  north of Geary Avenue in Japantown; in the Mission around 22nd Street between Valencia Street and South Van Ness Avenue; in the Inner Sunset along Irving Street; and in the Inner Richmond along Geary Boulevard between Arguello and 21st Avenue.

These concentrations can be explained by the SFMTA's blue zone siting policy: blue zones are currently only sited in non-residential areas and typically on metered block faces, with rare exceptions to increase access to some specific public destinations.

![](https://lh7-us.googleusercontent.com/S2HzREJSqRtB4t93mD7vJJ6JwvrvlTWjkd0-E0u7aeUYO7klGY9YG3MIdDj8kzcl4FrDUO_ZclQOoo54qhAhp4FKMtoT60Iae1olvWuE16oJl5qEPqjfzU2SEnNNg83rhMRlmHyKaanwLHtEXrJAyQk)

This map current blue zones relative to metered block faces and non-residential zoned areas. 747 or 93.85 percent of blue zones are in non-residential zoning districts; 495 or 62.1 percent of blue zones are on metered block faces.

![](https://lh7-us.googleusercontent.com/GAY7y7zgOne9gKhlRDucg68ByQcJFWRBWUqU1o8l4_p7Yjvg2Az0nyGbmPeAm2x2Krmn6Zo8AeQGwXT5jocEswDJCBup-ydnNtpHDTnHSj1FSB5KZY__iUa3Q4MpC8X2_CZlhZ9uVb_vyt3TyqSktJM)

![](https://lh7-us.googleusercontent.com/yKBqJD9DFrLrHr6alVKuXWx9sRd_LEU9XPYNvsmLhFia9MMezQXREGFnSYbYHeT7m8J-Maq7Dru978hxUhXT7VI7JyIMW9nJikIvklurNZfuMbj1Wqi6XosXyXY4rxXayau_vUtIWAytAUFlG-h8bdU)

To better understand the distribution of blue zones across the city and to see which areas are currently best served by the accessible parking program, I summarize blue zones and parking meters by political and geographic boundaries. We see that just two neighborhoods, Golden Gate Park and Lakeshore, meet the intended ratio of 4 percent blue zones to metered parking spaces, due to the fact that these areas have a relatively low proportion of parking meters for their size. Note that this calculation of blue zones in Golden Gate Park does not include the Recreation & Parks blue zones located within the park, only SFMTA blue zones located on streets along the periphery. The next highest proportions are in Glen Park (3.08 percent), The Outer Mission (2.75 percent) and Crocker Amazon (2.70 percent). The lowest proportions are in neighborhoods that are either entirely or partially residential. Most of the neighborhoods in the city have blue zone proportions between 1 and 2 percent, meaning that the number of blue zones will need to double or quadruple in these areas to meet the goal of 4 percent relative to metered parking. The average proportion of blue zones to meters by neighborhood is 1.67 percent. 

We can also see blue zones relative to meters in supervisor districts across the city. At this scale we see that no supervisor district in the city meets the 4 percent PROWAG requirement, with District 11 on the Southern edge of the city having the highest ratio of 2.33 percent blue zones to meters, and District 10, in the Southeastern corner of the city, having the lowest ratio of just 0.42 percent blue zones to meters. The average proportion of blue zones to meters by supervisory district is 1.5 percent.

![](https://lh7-us.googleusercontent.com/WDJZkCjSNot1mb1iwcbPi4SWau8-vhnCh7dxrAWyvGBiy_MvSeIZckQwH5plKEawbDsb6ahvSqcm8-N2x6VJmAQDKEB0d_vjgxbbkTe_0gcZHWORRITID99x9HHqIBwULJ591KwbVr1Uu-aBPoXRbFQ)

Binning blue zones and meters into a smaller grid of equal areas allows us to compare and assess blue zone percentages on a more granular level. For this analysis, blue zones and meters were summarized into Level 8 H3 hexagons. H3 is a standardized hierarchical geospatial index devised by Uber that allows analysts to divide maps of the Earth into a grid of equal-sized hexagons at various nested spatial resolutions. Level 8 hexagons each capture an average area of 0.74 square kilometers or 0.28 square miles. At this resolution, San Francisco can be approximately divided into 186 hexagons, each spanning an area roughly equivalent to 45 downtown city blocks. In a city of micro-neighborhoods, I chose this resolution as a kind of Goldilocks option: Level 7 hexagons cover too great an area to provide any useful insight, but Level 9 hexagons are too small to be practical. 

This map shows that there are 25 hexagonal areas that meet or exceed the 4 percent goal. These include areas of Maritime Park, Cow Hollow, Pacific Heights, Anza Vista, Lone Mountain, NOPA, the Panhandle, the Central and Outer Richmond, Golden Gate Park, Buena Vista, Eureka Valley, the Outer Sunset, West of Twin Peaks, Fairmount, St. Mary's Park, Mission Terrace, Bernal Heights, Silver Terrace, Parkmerced, Stonestown and Visitacion Valley. Note that most of these places meet the 4 percent target because they have a relatively low number of metered parking spaces, not because of an abundance of blue zones. The average proportion of blue zones to meters in these H3 hexagons is 2.8 percent. This H3 analysis also shows us that the blue zone proportion can vary dramatically among relatively similar areas of the city. Consider the distinction between the hexagon near Lafayette Park in Pacific Heights (5.16 percent) and the hexagon directly next to it that encompasses parts of Polk Gulch, Nob Hill and Russian Hill (1.62 percent).

#### Blue Zones Near Healthcare Centers

![](https://lh7-us.googleusercontent.com/EQIaex5WyhOaCfE8o9rRb0hzYIXFEB40hYgcxyIX7esspRlLYShT2m9j-ypRS7q6TnYjvU5ar-e0JLxia75NH-yYMnD4jlhon6HseUUpg_zFXlsWV2ekGGZQTeqnYVSrbKRop279PVyTB4gNH5tqit8)

#### Blue Zones Near Schools

![](https://lh7-us.googleusercontent.com/S1FY5nQMxkOl0oazEDb5A0KXBT4gEbZYP1WhtDEvUWEB9Lml83d20Ueu-WxzGqJW_4Po0FEQrW_Zr9ZWi570vUPe26Q6WwYYkKI_6ZfcTkFYDh6wZlNoCCnaOpCckhR2lkW7FuU6TQgvSauJ9DI0O0w)

#### Blue Zones Near Libraries

![](https://lh7-us.googleusercontent.com/u70IHrsDhMloAADynRPZbaL7W3WOwlhd9LrnKy7japEhSaAd2mG8Ecrh350wlE0mMXgTTWisucfQ7xwq31SbOlFCLrJKewmiNXorTgCEg7vlg8mhDZwy0jndvOIaS9l8HIkqi5j927qQGrxa6HY24Lk)

Beyond assuring an adequate distribution of blue zones across the city, the Accessible Services team is also concerned with providing enough parking near specific destinations that serve people with disabilities on a daily basis. These maps illustrate blue zones that are located within one-tenth of a mile (528 feet) of healthcare centers, libraries, and schools in San Francisco.  Since the point data for these locations do not represent the exact centerpoints or accessible entrances of these destinations, a circle with a radius of one-tenth of a mile was chosen as a nominal distance big enough to capture any proximal blue zones beyond the limits of building footprints. Ideally a more precise method would be used to locate blue zones directly in front of the most accessible entrances to these destinations. 

Note that neither the ADA Parking Guidelines nor PROWAG specify exact distances from an accessible parking space to the entrance of a business or destination. Section 208.3 of the ADA Accessibility Guidelines only states that accessible parking "must be located on the shortest accessible route to an accessible entrance, relative to other spaces in the same parking facility" and PROWAG only stipulates a precise distance between loading zones, stating in section 212.1 that "where permanently designated passenger loading zones are provided...  at least one accessible passenger loading zone...shall be provided every continuous 100 ft."

Only 20 or 26.64 percent of healthcare centers have only one blue zone nearby and 10 or 12.82 percent have no blue zones nearby. We see that 25.81 percent of libraries have just one blue zone, and almost 10 percent have no blue zones nearby. IWe see that 53.48 percent of schools have no blue zones nearby, and another 17.08 percent have just one blue zone nearby. Together that means that 70 percent of schools in San Francisco have one or no blue zones nearby.

### Conclusion:

Taken together these findings indicate that despite the high concentration of blue zones in downtown San Francisco, there aren't enough blue zones relative to the number of metered parking spaces in this area. These analyses also show that most planning neighborhoods and supervisor districts are well-below the 4 percent target, and there are many critical destinations in the city (i.e. healthcare centers, libraries, schools) that have no blue zones nearby. In many viable areas of the city, blue zone counts need to double to meet statutory targets. These analyses revealed that although analyzing blue zone counts in terms of supervisor district and neighborhood can be useful to understand the social and political impact of the blue zone program, assessing counts on a more granular level may be more practical in directing the work of adding more blue zones to specific street corridors or commercial districts.
