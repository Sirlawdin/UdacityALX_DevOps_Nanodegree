# UdacityALX_DevOps_Nanodegree

## Udacity Cloud DevOps Udagram Project1

## Deploy Static Website on AWS
#### Salaudeen O. Abdulrasaq salaudeen.abdulrasaq2021@gmail.com

In this project, A static website was deployed to AWS using S3, CloudFront, and IAM.

The files included are: 

01-created S3 bucket.PNG  - Created an S3 bucket (udacity-project1-static-website-bucket) for the website and unchecked the block public access settings  
02-Uploaded Website files.PNG  -  Uploaded the website files to the created bucket
03-Enabled Static Website Hosting.PNG  -  Enabled Static Website Hosting in the bucket
04-Bucket Policy Updated.PNG  - Created a bucket Policy to make the content of the bucket public
05-Created CloudFront Distribution.PNG  - Created a CloudFront Distribution to distribute website.

Website endpoint: http://udacity-project1-static-website-bucket.s3-website-us-east-1.amazonaws.com/index.html

CloudFront Domain Name: https://dgfxocffcttr8.cloudfront.net/

Customized error Page: https://dgfxocffcttr8.cloudfront.net/error

A customized error page was created and on the page is a link back to the home URL.


<br>





</br>

## Udacity Cloud DevOps Udagram Project2

## Deploy a High-Availability Web App using CloudFormation

#### Salaudeen O. Abdulrasaq salaudeen.abdulrasaq2021@gmail.com

# STATEMENT PROBLEM

## Scenario
Your company is creating an Instagram clone called Udagram.

Developers want to deploy a new application to the AWS infrastructure.

You have been tasked with provisioning the required infrastructure and deploying a dummy application, along with the necessary supporting software.

This needs to be automated so that the infrastructure can be discarded as soon as the testing team finishes their tests and gathers their results.

Optional - To add more challenge to the project, once the project is completed, you can try deploying sample website files located in a public S3 Bucket to the Apache Web Server running on an EC2 instance.


## Server specs

Launch Configuration was created for application servers in order to deploy four servers, two located in each of your private subnets. The launch configuration was used by an auto-scaling group.
Two vCPUs was used with 4GB of RAM. The Operating System used is Ubuntu 18. An Instance size and Machine Image (AMI) that best fits this spec was chosen.


# MY SOLUTION:

## Architecture Diagram

### Script Usage
This Repository contains some scripts that will be used to create the CloudFormation stack. 

### Usage:

#### Create:

```
./create.sh (stackName) (script.yml) (parameters.json) (profile)
```

> Example:

```
./create.sh Udagram infrastructure/network.yaml parameters/network.json udacity_user
```


#### Update:

```
./update.sh (stackName) (script.yml) (parameters.json) (profile)
```

> Example:

```
./update.sh Udagram infrastructure/network.yaml parameters/network.json udacity_user
```

![Architecture Diagram!](https://github.com/Sirlawdin/UdacityALX_DevOps_Nanodegree/blob/main/Udagram/UdagramDiagram.png)

# Website Link :

[http://serve-WebSe-15QTPYAIXE924-1193114271.us-east-1.elb.amazonaws.com](http://serve-WebSe-15QTPYAIXE924-1193114271.us-east-1.elb.amazonaws.com)

