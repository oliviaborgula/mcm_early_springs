# mcm_early_springs
Data analysis was performed in May 2024. 

For this <a href="https://www.mymcmedia.org/early-spring-in-county-impacts-pollinators-plants/"> story</a>, I uploaded data from this National Phenology Network <a href= "https://www.usanpn.org/data/code/geoserver-request-builder"> site</a>, which shows the average leaf-out date (the scientific threshold for spring arrival date) each year in US cities dating back to 1981. I joined it with this <a href= "https://github.com/kelvins/US-Cities-Database">dataset</a> to get specific coordinates for Montgomery County. I then used R to calculate the difference between each year's spring start date and the 1981 baseline before finding the average number of days earlier or later relative to 1981. 
