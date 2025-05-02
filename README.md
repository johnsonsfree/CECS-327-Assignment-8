# CECS-327-Assignment-8
# Sonia Masih and Youssab Girgis
# Group 8
#Client File
The client file has changes such as three valid loT queries, showing the results from server file and showing an error for queries that are not valid. It works by sending a query to the server file and then a valid response is returned. We tied our assignment 7 to help us complete this assignment since we have to integrate assignment 7's sensors. We also had to convert to imperial measurements such as kWh, gallons, °F, %RH. Our time zones also had to be in PST time zone. 

#Valid Queries: 
1. What is the average moisture inside my kitchen fridge in the past three hours?
2. What is the average water consumption per cycle in my smart dishwasher?
3. Which device consumed more electricity among my three IoT devices (two refrigerators and a dishwasher)?
   
#Instructions to run: 
-Both client and server file have to running and make sure to use the same IP address and port number. 
-Establish a connection between client and server file. 
-Enter one of the valid queries, and once the query is sent there will be a response back. 
-Once you get the response, you can type "exit" to exit. 

#Server File
The server file is the most important file because here is where we have our connection established with our client file and also our metadata. It should be able to understand and reply back to a valid query, and if it is not valid, then a error response must show. We also implemented an "exit" system. Conversions will be shown here for the unit of measurements for our device sensors. 
