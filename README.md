# UdacityDevOps-HighAvailabilityApp

UdacityDevOps-HighAvailabilityApp is an application project for the Udacity Cloud DevOps Engineer course. This project consists of an architecture diagram and scripts for deploying an environment via CloudFormation to AWS.

## Installation

### Install AWS CLI
#### Add the following text to the config file
File: C:\Users\%userprofile%\\.aws\config
``` 
[default]
region = us-east-1
[profile udacity]
 region = us-west-2
```

### Setup AWS Credentials 
#### Add your AWS Access Key, Secret Key, and Session Token in place of the values in quotes below to the file
File: C:\Users\%userprofile%\\.aws\credentials 
```
[default]
aws_access_key_id = "AccessKey"
aws_secret_access_key = "SecretKey"
aws_session_token = "SessionToken"
```
## Usage
Run the Create Stack (create.bat) CloudFormation Template to initially create the template in the AWS environment specified above. Run the Update Stack (update.bat) CloudFormation template to update the AWS CloudFormation stack if it's already created.


## License
[MIT](https://choosealicense.com/licenses/mit/)