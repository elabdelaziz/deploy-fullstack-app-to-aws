## Circle-Ci Pipeline

* build which install and build both the front-end and back-end applications.
* deploy which deploy the front-end to AWS S3 using aws cli and deploy the back-end to Elastic Beanstalk using eb cli.
* AWS Credentials as Circle ci environment variables which are used by aws cli for deployment.
* This workflow gets triggered on the master branch.