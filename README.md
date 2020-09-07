# MongoDB
# Hare krishna
# Radhe Radhe

# Drivers - https://docs.mongodb.com/drivers/

# Working with MongoDB

----------------------------------------------------------------------------------------------------------------------
                                   
                                   Application                                                       Data
  
                 frontend         Backend | Drivers          <------->       Mongodb  <-->   storage  <---> db
                   (UI)           (server)|  Node.js                         server          engine    r/w files(slow)
                                              Java             queries                                 r/w data (fast)
                                             Python                          communicate        file/data access
                                
 
                                  Mongodb Shell   (queries to mongodb server)
                                
                                    playground, Administration
                             

-----------------------------------------------------------------------------------------------------------------------


# Outline

------------------------------------------------------------------------------------------------------------------------------

           Introduction                   .------ >  CRUD Deep Dive - Read             ------>  Woking with Numeric Data          
                .                         .                  .                         .                   .
                .                         .                  .                         .                   .
    N->  Basics & Basic CRUD              .          CRUD Deep Drive - Update          .        Security & Authentication
                .                         .                  .                         .                   .
                .                         .                  .                         .                   .
        Data Schema & Relations           .          CRUD Deep Drive- delete           .        Performance, Fault Tolerance
                .                         .                  .                         .              & Deployment
                .                         .                  .                         .                   .
        Working with the Shell            .       A->    Using Indexes                 .              Transactions
                .                         .                  .                         .                   .
                .                         .                  .                         .                   .
          Using Compass                   .           Working with Geospatial          .         From Shell to Drivers
                .                         .                  data                      .                   .
                .                         .                  .                         .                   .
    B->  CRUD Deep Dive - Create < -------.           The Aggregation framework  -------             MongoDB Stitch
    
----------------------------------------------------------------------------------------------------------------------------    
