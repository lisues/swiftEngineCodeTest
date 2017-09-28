## swiftEngineCodeTest

========================================================================

#### DESCRIPTION:
This project was asigned by swiftEngine.io for a job interview. Create a simple REST-based message board, which 
stores data in a mongoDB database. A successful iteration of the Message Board web-application includes REST 
interfaces that invoked via GET and POST.

A simple REST-based Messaging Board web application stores data in a MongoDB database with using APIs provided by SwiftEngine.

[URL:](https://lisuejshe.site.swiftengine.net/)
A form for user to post a message and will send JSON data to server for storing the message. 

[URL:](https://lisuejshe.site.swiftengine.net/getMessages.ssp/)
The URL displays all messages. 
 
[URL:](https://lisuejshe.site.swiftengine.net/getMessages.ssp/{topic})
The URL displays the messages with given topic. 

### Supported Formats

=========================================================================

#### PACKAGING LIST:

##### index.ssp
  implemented a form to user to add a message.  Implemented sending a POST request with JSON data to server. 
  Display a notification message when message is stored successfully. 
 
##### messages.ssp 
  implemented a method to process the POST request and store the message to in the MongoDB database. Email 
  to the person who posted the message and admin. 
  
##### getMessages.ssp 
  Get all the messages from database and display them.



=========================================================================

Copyright © 2017 All rights reserved
