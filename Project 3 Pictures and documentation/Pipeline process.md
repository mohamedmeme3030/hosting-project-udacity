## Pipeline Process

## First of all everyone has his own way to achieve and this is my own idea:

#### 1- Creating the Database in AWS RDS and store the parameter in .env file.

#### 2- Link the local application to Github Through pushing it.

#### 3- Link the CircleCLI Directly to Github throught signing in and link Github.

#### 4- After That Pass all the enviromet variable to the enviorment variable CircleCi and create the circlecli in the main directory of the full project.

#### 5- If the repo has been changed then Circlecli starts the CI then deployment to AWS.

#### 6- Through First Installing all the dependencies that's need to deploy the application in both front and back end seperately.

#### 6- After that in our application the deployment related to the manager to approve it.

#### 7- When the manager approve it Starting the deployment of front end in the S3 Bucket.

#### -8 IF the previous is successful then deployment of the backend will take place.

#### 7- IF there is any error in Pipeline in CircleCi the process stoped and also the deployment will not happen.


### Pictures are attached fow more details.....
### Mohamed Hassan Project 3 Udacity Application Deployment