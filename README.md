# Travel Memory

`.env` file to work with the backend after creating a database in mongodb: 

```
MONGO_URI='ENTER_YOUR_URL'
PORT=3001
```

Data format to be added: 

```json
{
    "tripName": "Incredible India",
    "startDateOfJourney": "19-03-2022",
    "endDateOfJourney": "27-03-2022",
    "nameOfHotels":"Hotel Namaste, Backpackers Club",
    "placesVisited":"Delhi, Kolkata, Chennai, Mumbai",
    "totalCost": 800000,
    "tripType": "leisure",
    "experience": "Lorem Ipsum, Lorem Ipsum,Lorem Ipsum,Lorem Ipsum,Lorem Ipsum,Lorem Ipsum,Lorem Ipsum,Lorem Ipsum,Lorem Ipsum,Lorem Ipsum,Lorem Ipsum,Lorem Ipsum,Lorem Ipsum,Lorem Ipsum,Lorem Ipsum,Lorem Ipsum,Lorem Ipsum,Lorem Ipsum,Lorem Ipsum,Lorem Ipsum,Lorem Ipsum,Lorem Ipsum,Lorem Ipsum,Lorem Ipsum,Lorem Ipsum,Lorem Ipsum,Lorem Ipsum, ",
    "image": "https://t3.ftcdn.net/jpg/03/04/85/26/360_F_304852693_nSOn9KvUgafgvZ6wM0CNaULYUa7xXBkA.jpg",
    "shortDescription":"India is a wonderful country with rich culture and good people.",
    "featured": true
}
```

## Configuring MongoDB:

Step 1. **Sign in with your MongoDB account and create cluster:**
  - Visit the official MongoDB website https://www.mongodb.com/
 - Sign in with your MongoDB account
 - On the overview tab click on create Cluster
   

Step 2. **Setup your Cluster:**
 - Select the M0 structure as it is a free structure
 - Name your cluster (SaimCluster)
 - Select aws as provider and region as Mumbai
 - Click on create Deployment
 - Enter your username and keep the default password (*save username and password in safe file for future use*)
 - Click on create Database User
 - Click on Choose a connection method


Step 3. **Change the security group:**
 -  Under the security tab click on Network Access
 -  On you default IP Address click on Edit
 -  Mention 0.0.0.0/0 for Access List Entry and click on confirm
   

Step 4. **Connect Database through Compass**
 -  Under the Deployment Tab go to Database
 -  Click on connect after your cluster name
 -  Select the Compass option
 -  To install MongoDB compass select the option "I don't have MongoDB Compass installed
 -  Select your os (Windows 64-bit (10+) (MSI)) and download MongoDB Compass 
 -  Once the file is downloaded save it in a safe folder
 -  Install the MongoDB compass through your OS installer
 -  Follow all the prompts and keep the default settings
 -  Copy the connection string (*save the connection string in safe file*)
 -  Open MongoDB Compass
 -  Click on New Connection >> paste the connection string >> in the connection string replace 'password' with default saved password
 -  Click on Connect
 -  Database is now connected with MongoDB Compass








