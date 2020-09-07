# MongoDB
# Hare krishna
# Radhe Radhe

# Tutorial - https://docs.mongodb.com/manual/tutorial/
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
# Database vs Collection - https://docs.mongodb.com/manual/core/databases-and-collections/

# Create Database - https://www.tutorialspoint.com/mongodb/mongodb_create_database.htm

# JSON vs BSON - https://www.mongodb.com/json-and-bson

# CRUD Operations  - https://docs.mongodb.com/manual/crud/

    Create                                                 Update
    
    insertOne(data,options)                     updateOne(filter, data, options)
    insertmany(data,options)                    updateMany(filter, data, options)

    Read                                                   Delete
    
    find(filter, options)                       deleteOne(filter, options)
    findOne(filter, options)                    deleteMany(filter, options)
    
    

