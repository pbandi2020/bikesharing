# NYC Citi Bike Ride Analysis Dashboard
## Project Overview

Citi Bike NYC's official bike share program, was designed to give residents and visitors a fun, affordable and convenient alternative to walking, taxis, buses and subways.
The current analysis is built to convience the Des Moines investors with a solid business proposal by providing inteactive vizualition dashboard built using the bike sharing program data. For the analysis we picked the most popular month "August 2020 data" for biking.

## Results
The dashboard is built using certain key performance indicators that would provider the investors look at the proposal based on return of investment.

1.  Key dimension used are Gender, Usertype, Tripduration, Trip Start & End times, Location attributes
2.  The dimension are measured againt the total ride count and Average trip duration
3.  The Dashboard is build with filters to help the investors slice and dice the information. The filters avaibale are Gender and Hours per day
4.  Use the following link to access the dashboard - [Bike Sharing Program Analysis Report for NYC](https://public.tableau.com/profile/prathima.bandi#!/vizhome/NYCCitiBikeAnalysisReport/NYCCitiBikeAnalysisDashboard?publish=yes)

## Summary of vizualization layers included in the dashboard
1. Peak Hours in which the bikes are used for the month of August - This chart provides the investors a view of busy times to plan on staffing
2. Average Trips by Gender
3. Total Rides and utililation based on Trip Duration - This is very important to help maintain the equipment and understand the usage
4. Total Trips recorded by Usertype and Gender - This chart proivdes the investors a view on annual subcrption and usage by gender category
5. Most popular checkout location and checkout location - This will also help plan staffing and ensure enough bikes are avaiable to support the traffic
6. Trip count by Weekdays per Hour - This view helps with understanding the most busy day in a week and the which times in the day is most busy
7. Heat map based on Start and Stop times - Another view of busy times sliced by weendays and hours per day

 ## Tableau WorkSheet
 <table>
 <tr>   
  <td align="center"> <b> Bike Checkout For All Riders </b> </td>
  <td align="center"> <b> Bike Checkout By Gender </b> </td>
  </tr> 
  <tr>   
    <td valign="top"> <img src="/Images/AllRiderCheckouttime.png" width="500" /> </td>
    <td valign="top"> <img src="/Images/CheckouttimebyGender.png" width="500" /> </td>
  </tr>     
</Table>
<table>
  <tr>   
     <td align="center"> <b> Bike Checkout By UserType and Gender Sliced by Weekdays </b></td>
  </tr> 
  <tr>   
    <td valign="top"> <img src="/Images/WeekdayridesummaryByGenderandUsertype.png" width="500" /> </td>
  </tr>     
</Table> 
<table>
 <tr>   
    <td align="center"> 2017 VBA_Challege output </td>
    <td align="center"> 2018 VBA_Challege output</td>
  </tr> 
  <tr>   
    <td valign="top"> <img src="/Resources/2017%20AllstocksAnalysisRefactor.png" width="500" /> </td>
    <td valign="top"> <img src="/Resources/2018%20AllstocksAnalysisRefactor.png" width="500" /> </td>
  </tr>     
</Table> 
<table>
 <tr>   
    <td align="center"> 2017 VBA_Challege output </td>
    <td align="center"> 2018 VBA_Challege output</td>
  </tr> 
  <tr>   
    <td valign="top"> <img src="/Resources/2017%20AllstocksAnalysisRefactor.png" width="500" /> </td>
    <td valign="top"> <img src="/Resources/2018%20AllstocksAnalysisRefactor.png" width="500" /> </td>
  </tr>     
</Table> 
## Technology & Tools
The dashboard was built using Tableau Public account and for data transformation used Pandas.

## Summary 
In this dashboard our focus is on a single month and the most busiest month. On order for an investor to get a good understanding of the business model I suggest the following,
1.  Ride count by month for the whole year - This helps the investors understand the high and low points and help plan staffing and other logistics that will help with cost savings
2.  A financial report by month that would show  Total cost of all rides, Total ride count, Breakdown on expenses to help analyze the profits


4.  

