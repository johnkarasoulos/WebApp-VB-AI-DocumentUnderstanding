# Visual Builder Application integrating OCI Document Understanding Services.
This is the source code to implement a sample VisualBuilder application that is integrated with an OCI Bucket and an OCI Document Understanding service at your Oracle Cloud Infrastructure tenancy and it is used to upload and send an image of a Passport to OCI Document Understanding service (throught the OCI bucket) and then receive and display the extracted information from the passport. 

## Extract Information from a Passport – VB Application Architecture.
![image](https://github.com/johnkarasoulos/WebApp-VB-AI-DocumentUnderstanding/assets/25766024/b6638559-bf6f-4fa1-a330-e84fd6671629)

## Cloud Coaching - Low Code embraces Oracle Cloud Infrastructure AI services 
You can watch from this link: https://youtu.be/0oHixpA9JDc?si=U2g-QIyJjUVWKOZK&t=1191  , how to implement this application using the provided source git repository into your own Visual Builder instance at your tenancy.

### From github repository to Oracle VisualBuilder application. 
1. Connect to your Oracle Visual Builder Studio Instance
2. Into an existing Project OR Create a new project --> create a new git repository by importing the existing public GitHub repository.
   ![Screenshot 2024-03-25 at 12 33 33](https://github.com/johnkarasoulos/aircraftBlockchain/assets/25766024/235cf9ae-c01f-449a-8764-96fdda1e543b)

4. Create a new Workspace using the button "Clone From Git" where you are selecting the Repository Name, the Branch , the Development Environment and you are providing the name of the Workspace Name.
   ![Screenshot 2024-03-25 at 12 37 06](https://github.com/johnkarasoulos/aircraftBlockchain/assets/25766024/5592e9b4-d1c1-44ba-ab37-364f87f06809)

6. You redirected to the new VisualBuilder instance assigned to this workspace and you can start working.  
 
## Configuration of the application  
Once you have create your own workspace using a clone of the github repository inside your git repository available into your Oracle Cloud Infrstructure Visual Builder Studio, then you will need to configure the followings : 
- For each service end point, your Cloud Infrastructure Signature :
  <img width="546" alt="Screenshot 2024-03-25 at 14 04 23" src="https://github.com/johnkarasoulos/WebApp-VB-AI-DocumentUnderstanding/assets/25766024/314df43a-6077-4476-a5a5-8e4dcbd82cfa">

- The variables needed to access your OCI Object Storage - Bucket : bucketName, compartmentId , namespaceName
