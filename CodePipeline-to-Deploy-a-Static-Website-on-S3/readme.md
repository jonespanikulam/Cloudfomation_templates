
Building a CI/CD Pipeline with AWS CodePipeline to Deploy a Static Website S3 on cloudfront using OAI
--------------------------------------------------------------------------------------------------------

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
