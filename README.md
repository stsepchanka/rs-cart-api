
## Task 8

### What is done:
- 1 - Dockerfile is prepared, image is building. Image size is minimised to be less than 500 MB.
- 2 - Dockerfile is optimized. Files that change more often and commands that depend on them should be included later, files and commands that change less should be at the top.
- 3 - Folders are added to .dockerignore, with explanations. At least 2 big directories should be excluded from build context. Elastic Beanstalk application is initialized.
- 4 - Environment is created and the app is deployed to the AWS cloud. You must provide a link to your GitHub repo with Cart API service or PR with created Dockerfile and related configurations.
- 5 - FE application is updated with Cart API endpoint. You must provide a PR with updates in your FE repository and OPTIONALLY link to deployed front-end app which makes proper API calls to your Cart service.

Cart API [http://stsepchanka-cart-api-dev.eu-west-1.elasticbeanstalk.com/](http://stsepchanka-cart-api-dev.eu-west-1.elasticbeanstalk.com/)

FE Repository PR [https://github.com/stsepchanka/nodejs-aws-fe/pull/5](https://github.com/stsepchanka/nodejs-aws-fe/pull/5)

FE [https://d310rchd4cv01e.cloudfront.net](https://d310rchd4cv01e.cloudfront.net)
