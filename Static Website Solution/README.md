# Deploy Static Website on AWS

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
