# bikesharing
## Overview of the Analysis

   The main objective behind analysis in to find out how NYC bike sharing business work? for this we used 201908-citibike-tripdata and perfoming analysis based on tableau chart to give answer to differnt questions regarding NYC bike sharing.


## Results

Using differnt parameters(field) in NYC city bike sharing data like starttime,endtime,gender etc. find out following results:-

### 1. checkout times for users:-

   Following image shows Checkout times for users for every hours in day means it shows tripduration for particular minute and  particular hour. For example 104824 rides checkout by Male 34151 rides checkout by Female and 6172 rides checkout by Unknown for Hour of tripduration: 0 and Minute of tripduration:6 .


![image](https://github.com/sanjal7137/bikesharing/blob/f422cd5484764b2f51791b40c68a8bd4c8951d72/Images/1.png)

### 2. checkout times by gender :-

   Following image shows Checkout times for users by gender for every hours in day means it shows tripduration for particular minute and  particular hour gender wise. For example 375 rides for Hour of tripduration: 1 and Minute of tripduration:19 .


![image](https://github.com/sanjal7137/bikesharing/blob/30e19fbb221e77b55120205d01abb6d767caf894/Images/2new.png)

### 3. Trips by weekday for each hour :-

   Following image shows Number of bike trips by weekday for each hour of the day means it shows tripduration for particular minute and  particular hour gender wise. For example 375 rides for Hour of tripduration: 1 and Minute of tripduration:19 .


![image](https://github.com/sanjal7137/bikesharing/blob/30e19fbb221e77b55120205d01abb6d767caf894/Images/2new.png)


### UFO Sightings filtering:

1- User manually give input as a filter parameter and as per user input table display UFO data in below image enter city name is "ca" in filter and table display all UFO data with city name "ca":

![image](https://github.com/sanjal7137/UFOs/blob/a6a08c2b0e5936222375ee66c6a36c18e5814ff7/Resources/ufofilterdata.png)

2- To clear filters and refresh the webpage to view all UFO data:d

  * filters can be manually cleared
  * the webpage can be refreshed by clicking on the "UFO Sightings"shown in below image
  
  ![image](https://github.com/sanjal7137/UFOs/blob/959f1b95ba0ea537c1935e84e5640c5b02493b5c/Resources/ufoclear.png)
 

## Summary 

One main drawback of the webpage is that data for UFO sightings is static resides in data.js file so web page is dynamic but due to static database user gets results based on data stored in data.js file. 

Following improvements can be made to the existing web page:
* Have drop-down list for filter criteria to select or give more than one value as a filter.
* Allow users to select a date range, rather than one specific date only
* Add a clear filter button to clear all filter criteria 
