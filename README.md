# airSEM-Report
SQL Code to create airSEM Performance Dashboards using Performance Data from various Search Engines and Campaign Parsing Table.

**Requirements**

Performance Data from Search Engines:
conversions (Bookings) and conversionvalue (Revenue) in the previous 30 days won't match excatly to the numbers on interface due to the cookies effect. Other KPIs should match exactly to the numbers on interface; conversions and conversionvalue earlier than the previous 30 days should match as well. 

Dimensions from the Parsing Table:
Ensure all dimensions have valid values. Exception: For Brand Campaigns, “N/A” is valid for Origin and Destination. 
