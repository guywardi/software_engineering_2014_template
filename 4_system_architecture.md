#2.0 SYSTEM ARCHITECTURE

######2.1 System Overview

Park Smart solution will have a two definite approach for positioning a definite vehicle or a person.
    <b>Approach 1:</b> Locating a mobile device used by the driver who is looking for their parked car.
    <b>Approach 2:</b> Navigating a car to the desired park spot.

 Here, Approach 1 is the priority since the car owner will be looking for the car in the covered park area where all the WIFI AP is installed. But on the other hand the Approach 2 is the 2nd only he is connected to the predefined network i.e. if that is school network.

Architecture of this model is pretty much challenging. 

#####2.2 Required Aspects

There are certain aspects that needed to be taken care of before we start the project in detail are as follows.
<ul>
  <li><b>A) Hardware Resources</b></li> 

 <li><b>B) Software Resources</b></li>

 <li><b>C) Service Provider</b></li>
</ul>
In order to acquire maximum quality and good response from the system we will be using following specification in this particular module.
<ol>
 <li>15 WIFI APs IEEE 802.11 Standard Family (Number depends upon area)</li>

 <li> Ethernet Switches</li>

 <li> Linux Server (Database, Response, Position Query Handling) </li>

<li> Parking Management, Oracle Database</li>

<li>Internet/Intranet Service Provider</li>
</ol>
#####2.3 Scenario

The most important point in the system is the Internet through which this multiple and separate services and devices are aligned together to provide one simple solution for parking.
Internet will be acting like a bridge to the user and the parking host provider.
With the help of Wi-Fi devices parking host can record, amend or reserve the parking spot allocation in the real time scenario. Accordingly the database will be working side by side so that there is always updated information provided for the consumer. Database management will be consisting of messages, warnings, alert, parking spot geo-location information, and also the fingerprint of the client devices and the vehicles, which will be helpful for further future, use. 
On the other hand the client application will be using as a broadcaster to the parking area looking for the spot, and will be displayed the proper location nearest to the office or classroom of their interest.

#####2.4 Service Architecture
