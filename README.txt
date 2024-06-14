 AWS CloudFormation Project for Scalable Web Hosting Infrastructure 

I successfully designed and deployed an advanced AWS CloudFormation template to automate the creation of a comprehensive and scalable web hosting infrastructure. This project involved several key AWS services and features, providing a robust solution for hosting both static and dynamic websites.

Project Highlights:
VPC Configuration: Set up a Virtual Private Cloud (VPC) with four subnets (2 public and 2 private) to ensure high availability and fault tolerance.
Network Setup: Integrated an Internet Gateway for public subnet access and a VPC Endpoint Gateway for secure access to S3 from private subnets.
Security and Routing: Configured security groups and route tables to manage secure and efficient traffic flow within the network.
Route 53 & CloudFront: Implemented Route 53 for domain name management and CloudFront for content delivery, optimizing access to static content hosted on S3.
S3 Buckets for Static and Dynamic Websites:
Static Content: Hosted static website content accessible via CloudFront with Origin Access Control (OAC), ensuring secure and efficient delivery.
Dynamic Content: Managed dynamic website content through a Load Balancer and Auto Scaling Group, routing traffic to private EC2 instances running HTTPd servers.
Automation and Scalability: Leveraged AWS Auto Scaling to ensure the infrastructure can scale dynamically based on traffic demands, maintaining performance and availability.
Key AWS Services Utilized:
Amazon VPC: For network isolation and configuration.
Amazon EC2: For hosting dynamic web server instances.
Amazon S3: For storing and serving static and dynamic content.
Amazon CloudFront: For content delivery network (CDN) services.
Amazon Route 53: For DNS management and routing.
AWS Lambda: For serverless compute needs.
AWS Auto Scaling: For ensuring high availability and scaling.
Amazon SNS: For sending notifications.