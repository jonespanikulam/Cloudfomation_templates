
Building a CI/CD Pipeline with AWS CodePipeline to Deploy a Static Website S3 on cloudfront using OAI
--------------------------------------------------------------------------------------------------------

Step1: Create an s3 bucket and block all public access

Step2: Create a ditribution in cloudfront with domain name as s3 bucket and create an OAI to access the website only through cloufront url.
Rest all option can be kept with default one. The bucket policy for OAI will be created by aws automatically after creating the distribution

![image](https://user-images.githubusercontent.com/59678465/169069472-ced4466d-7f01-474d-bfa2-aea896090b05.png)

Step 3: After creating the distribution you can access the site using cloudfront URL
![image](https://user-images.githubusercontent.com/59678465/169070206-d80e839e-ca1a-4368-a962-436adc476224.png)

Step 4:  Create a codepipe line and provide the repository name in code commit. So all the events pushed in the repo will be automatically updated

Step 5: Create a

Codepipeline
![image](https://user-images.githubusercontent.com/59678465/169018237-9e3a6e9a-bef3-4335-a8c1-f9d7c076804a.png)

Not accessible using s3
![image](https://user-images.githubusercontent.com/59678465/169017429-ca1277c8-9fa6-481e-864b-cef235de12c0.png)

Accessible using cloudfront.
![image](https://user-images.githubusercontent.com/59678465/169017369-d4aaf2c6-5b1a-42b2-8189-8e3fe0258ab5.png)

postbuild in buildspec file to do invalidation in cloudfront.
![image](https://user-images.githubusercontent.com/59678465/169017707-6a645763-090f-4217-9b53-41793f7e0569.png)

Invalidation in cloudfront
![image](https://user-images.githubusercontent.com/59678465/169018379-36328cf5-ce4d-4396-8d79-ca9b97cc4b66.png)
