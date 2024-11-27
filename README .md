### Codetribe MongoDB 

This project involves creating a MongoDB database named Codetribe and adding three collections: Facilitators, Trainees, and Projects. Each collection will contain specific fields and documents as outlined below. 

### Prerequisites
Before starting, ensure the following:

MongoDB is installed on your system.
To start the MongoDB shell (Mongosh):

Open your terminal or command prompt.
Run the following commands
mongosh
shell
Test>

### MongoDB Shell Commands

Step 1: Create the Codetribe Database
To switch to the Codetribe database (and create it if it doesn’t exist):
use Codetribe

Step 2: Create Collections: 
Create the Facilitators Collection

db.Facilitators.insertOne({
  Name: "John Doe",
  Location: "Johannesburg",
  Course: "Full-Stack Development"
})
 Create the Trainees Collection:
 db.Trainees.insertOne({
  Name: "Jane Smith",
  Location: "Cape Town",
  Facilitator: "John Doe"
})
Create the Projects Collection: db.Projects.insertOne({
  Name: "Weather App",
  Course: "Web Development",
  Lesson: "APIs and Fetch"
})

### Verifying the Data
You can verify the collections and documents were created successfully by running the following commands:

List all collections in the database:

show collections
View documents in the Facilitators collection:

db.Facilitators.find().pretty()
View documents in the Trainees collection:

db.Trainees.find().pretty()
View documents in the Projects collection:

db.Projects.find().pretty()
### Screenshort
[screenshots1](./README%20(1).png)
[screenshots2](./README%20(2).png)
[screenshots3](./README%20(3).png)
[screenshots4](./README%20(4).png)
[screenshots5](./README%20(5).png)