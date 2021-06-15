# elastic-beanstalk-docker-with-ssl-sample
AWS Elastic Beanstalk Docker App Sample with SSL Enabled

Configuration to terminate SSL connections at instance using Elastic Beanstalk is hard.
AWS documentation does not cover it very well.


Based on https://docs.aws.amazon.com/elasticbeanstalk/latest/dg/samples/docker.zip
and https://docs.aws.amazon.com/elasticbeanstalk/latest/dg/https-singleinstance.html

**Deploy:**

Create a .zip file of the contents, including `.ebextensions` and `.platform` hidden folders
and upload it to your beanstalk docker environment.

Tested with: Elastic Beanstalk Environment Platform Docker running on 64bit Amazon Linux 2/3.4.1
