# HomeworkAWS

First of all, I visited the Cloud Academy website and studied about the 6 lab activities under the AWS Certified Solutions Architect - Associate.
After that did hands on practicals using Amazon Web Services by creating an account there. Brief description about the lab sessions and the issues faced are described below.

1. Create your first Amazon EC2 instance (Linux)

  Amazon EC2 is the most famous AWS service and allows you to launch different types of cloud instances and pay for them with a pay-per-use approach. EC2 provides you with complete control of your computing resources and lets you run on Amazon’s computing environment. Amazon EC2 reduces the time required to obtain and boot new server instances to minutes. This allows you to quickly scale capacity, both up and down, as your computing requirements change. Amazon EC2 allows you to build and configure your instances as you like, from your operating system to applications.
  
  https://www.youtube.com/watch?v=u0ilsoANTCk&feature=youtu.be
  
  As in the video when doing this lab session, I have used windows operating system and therefore used putty. At first I was unable to catch up the steps to be follow in the putty. Therefore, I had created more than one EC2 instances in lab 01.

2. Create your first Amazon EC2 instance (Windows)

  Amazon EC2 is the most famous AWS service and allows you to launch different types of cloud instances and pay for them with a pay-per-use approach. With Amazon EC2 you can create new servers in a few minutes and use different images (AMI) to personalize them. AWS provides several Microsoft Windows Server AMIs that enables you to run any compatible Windows-based solution. Can use Windows-based applications, websites, and web-services written in .NET, for data processing, media transcoding, and any other task requiring Windows software.
  
  https://www.youtube.com/watch?v=iXSPJQifby8&feature=youtu.be
  
  As in the video I was unable to do the final step in the lab session. Because I had changed my internet explorer security settings. Therefore, due to security issues I was unable to go to the required links as described in the lab session.

3. Managing instance volume Using EBS

  Amazon Elastic Block Store (Amazon EBS) provides persistent block level storage volumes for use with Amazon EC2 instances in the AWS Cloud.  Each Amazon EBS volume is automatically replicated within its Availability Zone to protect from component failure. This provides high availability and durability. Amazon EBS volumes offer consistent, low-latency performance needed to run the workloads.
  
  https://www.youtube.com/watch?v=IhSuhGkfLok&feature=youtu.be
  
  As in the video when doing this lab session, I was created the instance in zone us-west-2a. As in the Lab modules in cloud academy when attaching new volume, I selected the zone as us-west-2b. Therefore, at the first time I was unable to continue from that find since there were no instances I had create in the zone us-west-2b.
  
4. Create your first Amazon S3 bucket

  Amazon Simple Storage Service (Amazon S3), provides secure, durable, and highly-scalable object storage. Amazon S3 allows to store and retrieve any amount of data from anywhere on the web. Will pay only for the storage actually use with no minimum fee and no setup cost. It can be used alone, or together with other AWS services, such as Amazon Elastic Compute Cloud (Amazon EC2), Amazon Elastic Block Store (Amazon EBS), and Amazon Glacier. Can also use Amazon S3 with third-party storage repositories and gateways.

  https://www.youtube.com/watch?v=Fpxh6pyu0WE&feature=youtu.be

5. Create an EBS-Backed (Linux AMI)

  An Amazon Machine Image (AMI) provides the information required to launch an EC2 instance. Can customize an EC2 instance and then save the configuration as a custom AMI for private or public use. Every EC2 instance launched selecting the customized AMI will contain any software or file that have previously added.
  
  https://www.youtube.com/watch?v=xzkAI9hoenY&feature=youtu.be
  
6. Create your first Amazon RDS Database
  
  Amazon Relational Database Service (Amazon RDS) is a web service that makes it easy to set up, operate, and scale a relational database in the cloud. Can migrate existing applications and tools that utilize a relational database to the Amazon Web Services because Amazon RDS offers access to the capabilities of a MySQL, Oracle, SQL Server, and the PostgreSQL database engine. Amazon RDS provides cost-efficient and resizable capacity while managing time-consuming database administration tasks. This efficiency frees you to focus on applications and business.
  
  https://www.youtube.com/watch?v=wE5akgCcBkc&feature=youtu.be
  
  As in the video when doing this lab session, I accidently didn’t select the latest version of MySQL. When creating the MySQL database I was end up with an error after entered the password. After that, I again created a db instance by selecting latest MySQL version. Another error I was made is I didn’t give the source as in the user guide of the lab session in the Security Groups under the VPC. When I correct those mistakes I was able to complete the lab session.
