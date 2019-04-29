Step 1: Install a local instance of Mongodb:
Follow links https://docs.mongodb.com/v3.2/administration/install-community/ and/or https://docs.mongodb.com/manual/installation/

Step 2: Install MongoDB Compass to view data easily (or use MongoShell): Follow https://docs.mongodb.com/compass/master/install/

Step 3: Install eclipse and maven: 
https://www.eclipse.org/downloads/packages/ | 
https://www.eclipse.org/m2e/

Step 4: Clone the repository and open the project as a Maven project 
(maven will install all required packages and dependencies for you)

Step 5: Download log files from https://drive.google.com/open?id=1NVgZ1E25G5g6cIFcAHCMO4KLjSNaVmkQ and save the location

Step 6: Open "MongoDriver.java" and update the location of the folder (using the given format on line 37)

Step 7: Run "MongoDriver.java" to load the data from log files and the database and collections will be created automatically.

Step 8: Use "MongoClientTest.java" file to retrieve details from the DATA API 
(Uncomment the print section under each call to see the data in eclipse console. Data is returned in List<Document> or List<String> format.)
