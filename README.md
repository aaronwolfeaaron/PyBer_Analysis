# PyBer_Analysis

# Overview
This analysis was conducted to observe the differences in fare amongst rural, suburban, and urban cities served by PyBer. In particular, PyBer sought to find disparities in access to rideshares based on affordability by location. 

# Results

After analysis, the data showed that users in rural areas paid significantly more per ride than their suburban and urban counterparts, with urban riders paying the least per ride.

Average Fares from the time period studied are listed below:
* Rural       $55.49
* Suburban    $39.50
* Urban       $16.57

There are multiple factors noted of why this may be the case. 

For one, there are far less drivers in rural areas than urban areas, so this comes down to an issue of supply-and-demand. A random sampling shown below shows evident disparities in number of drivers.

![](https://github.com/aaronwolfeaaron/PyBer_Analysis/blob/main/Urban_Driver_Count.png)
![](https://github.com/aaronwolfeaaron/PyBer_Analysis/blob/main/Rural_Driver_Count.png)

Second, the average fare per driver is much higher in rural areas, while in urban areas, the average fare per driver is significantly less than the average fare per ride, as evidenced by the information below. This shows that rural drivers are doing fewer, but longer, trips while urban drivers are doing more, but shorter, trips. 

![](https://github.com/aaronwolfeaaron/PyBer_Analysis/blob/main/Fare_Per_Driver.png)

# Summary 
Based on the results, I would like to provide three business recommendations to the CEO for addressing any disparities among the city types. 

1. In order to increase the number of drivers in rural areas, offer pay incentives to drivers from rural areas. This will increase supply.
2. In order to increase ridership in rural areas, provide vouchers to offset the cost of longer, less frequent trips. This will increase demand. 
3. In order to account for differences in types of ride (short, frequent urban rides and long, infrequent rural rides), use different algorithms for different city types. Lean more heavily into time of drive for cities and mileage of drive for rural areas. This will promote equity.
