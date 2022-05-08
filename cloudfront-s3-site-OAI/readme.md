Hosting Site in s3 using Cloudfront OAI
-----------------------------------------
CLoudformation policies used:
AWS::CloudFront::Distribution
CloudFrontOriginAccessIdentity:
AWS::S3::BucketPolicy


![c1](https://user-images.githubusercontent.com/59678465/167283747-95d7aed0-9bac-4f8e-bd6d-e5cb43cdffb6.jpg)

Distribution
![c2](https://user-images.githubusercontent.com/59678465/167283754-a7a7d972-4fe4-4ea9-90b4-05dc777c6388.jpg)


Cannot be accessed using s3 object url
![c3](https://user-images.githubusercontent.com/59678465/167283764-0a0c7fc5-f117-4c60-b6fe-22c718551465.jpg)


Accessed using cloudfront using OAI:
![c4](https://user-images.githubusercontent.com/59678465/167283769-3c7e37f1-39b6-4580-ac2c-8fa33252ac98.jpg)

