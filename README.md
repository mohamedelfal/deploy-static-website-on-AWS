# Udacity DevOps
## 1- Website Files
### The S3 bucket is created.

![1-S3 bucket is created](./image/1-S3BucketIsCreated.jpg)

### 2-all the website Files uploaded to the newly created S3 bucket.
![2-Website Files Uploaded](./image/2-WebsiteFilesUploaded.jpg)

### 3- The S3 bucket is conFigured to support static website hosting.

![3-support static website hosting](./image/3-SupportStaticWebsiteHosting.jpg)

### 4- The S3 bucket has an IAM bucket policy that makes the bucket contents publicly accessible.

![4-Bucket Policy](./image/4-BucketPolicy.jpg)


## 2- Website Distribution

### CloudFront has been conFigured to retrieve and distribute website Files.

![5-CloudFront Distribution](./image/5-CloudFrontDistribution.jpg)

## 3- Access Website in Web Browser

### 1- Open a web browser like Google Chrome, and paste the copied CloudFront domain name (such as, d25g3zasxgsb3t.cloudfront.net) without appending /index.html at the end. The CloudFront domain 

name should show you the content of the default home-page, as shown below:
>> https://d25g3zasxgsb3t.cloudfront.net/

![https](./image/https.jpg)

The figure above shows the page displayed at >> https://d25g3zasxgsb3t.cloudfront.net/

### 2- Access the website via website-endpoint, such as http://first-udacity-website.s3-website.eu-west-3.amazonaws.com/

>>http://first-udacity-website.s3-website.eu-west-3.amazonaws.com/

![https](./image/http.jpg)

The figure above shows the page displayed at >> http://first-udacity-website.s3-website.eu-west-3.amazonaws.com/

### 3- Access the bucket object via its S3 object URL, such as, https://first-udacity-website.s3.amazonaws.com/index.html

![index](./image/index.jpg)

The figure above shows the page displayed at >> https://first-udacity-website.s3.amazonaws.com/index.html

