# weaponShop
Online Web Application - Full-Stack Prototype of AWS Services

Both front-end and back-end has been implemented via AWS services. We decided that a serverless approach via Amazon Web Services would be an optimal and enriching learning experience. 

For our back-end data pipeline, we utilized Amazon API Gateway, Lambda, and DynamoDB.

For our front-end interface, we constructed a website using HTML, based the user authorization around Cognito, and placed all the files in an S3 Bucket. We then uploaded the website through Cloudfront.

There were many advantages, as well as challenges, to relying on AWS to build and implement our website.

Firstly, there was a very steep learning curve to utilizing the tools available on AWS. Each tool had its particular function, and we had to figure out which one to implement, how to maximize its effectiveness, and then make sure it interacted properly with the other tools. 

Also, the Amazon developer documentation was very outdated, and majority of the information on the internet was also outdated or difficult to use. We ran into a massive roadblock with creating our API due to this, and our functions didn't work for most of the weekend. Lastly, when we used Cloudfront to upload our site, we were unable to connect our back-end to it and ensure 100% functionality throughout the stack. 

Despite the many challenges with implementing AWS, it was worth it. 

We were able to build a website and host it, whilst also constructing the back-end, all for free. Going serverless would also mean that we wouldn't have to worry about hardware, architecture, latency issues, security, etc. AWS has enough tools that one who has a decent enough grasp of it can construct and perform anything. 

PR/SK/TW/BC

HackGSU2018


