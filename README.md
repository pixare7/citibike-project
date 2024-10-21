# Citibike Analysis

### Executive Summary:
This project analyzes data from New York City's Citibike program, utilizing a series of interactive Tableau dashboards to answer key questions posed by city officials. The data provides insights into how bike-sharing is utilized in the city, highlighting trends in usage and ride patterns throughout 2023. The analysis aims to help city officials understand bike-sharing behavior and identify opportunities to improve the service.  
The project focuses on key metrics such as ride type, user type, percentage changes in ride counts, and distance covered over time, visualized through interactive maps and charts. The ultimate goal is to uncover trends that guide business decisions, helping make the Citibike program more efficient and accessible.
You can explore the **Tableau dashboard** [here](https://public.tableau.com/views/citibike_data_17288848956340/Story?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link).

### Business Problems:

This analysis addresses the following question:
- **Angels Program**: Where should riders be incentivized to take bikes to make them more accessible in other locations?
- **Bike Accessibility**: How can the Citibike program improve bike accessibility in under-served areas to ensure that bikes are evenly distributed and available when needed?

### Key Findings:

1. **Dashboard Descriptions**:
   - **Dashboard 1**:
     - A bar chart shows that electric bike usage peaked in April and steadily declined throughout the year. In contrast, classic bike usage peaked in August, which coincides with ideal weather conditions.
     - A line chart reveals that member bike rides increased consistently by 18-20% in March, April, and May, while casual rides spiked by 35% in March, 61% in April, and 20% in May. This suggests that improving weather and biking events (such as tours and marathons) play a significant role in boosting ridership.
     - A pie chart shows a higher proportion of member rides compared to casual rides. The consistency in member rides, coupled with the large fluctuations in casual ride usage, suggests that member rides are more stable, while casual rides are more event-driven or weather-dependent.
     - A map shows the start stations and the attractions nearby such as parks, museums, train stations, restaurants, and more.  

   - **Dashboard 2**:
     - A bar chart and line graph show that the most popular starting location for rides is the Grove Street PATH station. Hovering over the map reveals that over 29,000 bike rides started here, with nearly 49,000 ending here, indicating a significant accumulation of bikes.
     - This is where the **Angels Program** comes into play, incentivizing riders to move bikes from areas with high bike density (e.g., Grove Street) to areas with higher demand but fewer bikes (e.g., Bergen Avenue, Union Street, or Grant Avenue).
     - The map also reveals while there are many **end stations** in New York City, there are **no start stations** displayed. This suggests that many users end their rides in NYC, but do not begin their trips there. This may be due to known issues with unlocking bikes in NYC, which could be impacting the availability of start stations. Addressing these issues could lead to higher bike utilization in the city.
     - Filtering by user type shows that Grove Street PATH is the most popular station for members, while Hoboken Terminal is the most popular for casual riders, likely due to its proximity to tourist destinations and scenic views along the Hudson River.
     - The map highlights the three main regions where rides begin: downtown Jersey City, Hoboken, and the west side of Jersey City. These regions are similarly popular for ending rides, with New York City also appearing as a common endpoint.

2. **Interactive Features**:
   - **Filters**: Users can filter the data by month or time range, as well as by user type (casual, member, or both) and rideable type (classic, docked, electric). These filters provide a customized view of the data for better insights.
   - **Drill-downs**: Users can hover over charts and maps to access additional details such as ride count, rideable type, average distance, station name, and the total number of rides. This allows for deeper analysis without overwhelming the initial visual.
   - **Interactive Map**: The map is fully interactive, allowing users to zoom in and explore specific stations. Hovering over each station reveals the station’s name, location (latitude and longitude), and the total number of bike rides, with zip code boundaries visible for geographic context.

### Results and Recommendations:

1. **Chosen City Map Analysis**:
   - When filtering for bike types, the map and accompanying bar chart show that Hoboken Terminal is the most popular station for all rideable types. For classic bikes, Grove Street PATH emerges as the top start location.
   - Filtering by user type reveals that members predominantly start rides at Grove Street PATH, while casual users prefer Hoboken Terminal and South Waterfront. This is likely due to the scenic views along the Hudson River, as well as Hoboken Terminal’s convenience for tourists and non-commuters traveling to New York City.
   - Interestingly, the map shows that many riders end their trips in New York City, but there are no start stations in NYC. This could be attributed to reported issues with unlocking bikes in the city, which may discourage users from beginning their rides there. Addressing these operational challenges could improve accessibility and increase bike usage for both starting and ending trips in NYC.

2. **Results Summary**:
   - The analysis highlights significant patterns in bike usage, with notable differences between casual and member riders. Member rides are more consistent throughout the year, while casual rides experience spikes tied to weather and events.
   - Popular starting points, such as Grove Street and Hoboken Terminal, indicate high commuter and tourist traffic, while less popular stations, especially in suburban areas, could benefit from the redistribution of bikes through the Angels Program.

3. **Recommendations**:
   - **Redistribution of Bikes**: Implement the Angels Program to encourage riders to move bikes from high-accumulation areas, such as Grove Street, to locations with higher demand but fewer bikes, like Bergen Avenue and Union Street.
   - **Targeted Marketing**: Promote bike-sharing in areas with lower ridership to increase awareness and usage, particularly in less popular regions.
   - **Address NYC Operational Challenges**: Investigate and address the unlocking issues that prevent users from starting rides in New York City. Ensuring smooth bike access in NYC could balance start and end station distribution and boost overall bike usage.
   - **Future Improvements**: Consider incorporating real-time data into the analysis to monitor bike usage dynamically, allowing for more responsive decision-making. Additional metrics, such as customer satisfaction or environmental impact, could also provide a more holistic view of the program’s success.
