# MongoDB
# Hare krishna
# Radhe Radhe

# Drivers - https://docs.mongodb.com/drivers/

# Working with MongoDB

   Application                                                       Data
  
   frontend         Backend | Drivers          <------->       Mongodb  <-->   storage  <---> db
     (UI)           (server)|  Node.js                         server          engine    r/w files(slow)
                                Java             queries                                 r/w data (fast)
                                Python                          communicate        file/data access
                                
                                                  
                               Mongodb Shell   (queries to mongodb server)
                                
                                playground, Administration
