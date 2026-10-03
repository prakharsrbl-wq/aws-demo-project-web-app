##Introduction (About the Project)


This is a beginner AWS Cloud project built to develop my practical understanding of AWS services, cloud networking, security, application deployment, and high availability. 

In this project, I created and configured a web application infrastructure using services such as Amazon VPC, EC2, Application Load Balancer, Auto Scaling, Amazon RDS, Route 53, IAM, CloudWatch, and Security Groups.

The main purpose of this project was not to build a complex application, but to understand how different AWS services work together to deploy and manage a web application.

I configured public and private subnets, route tables, Internet Gateway, NAT Gateway, Security Groups, load balancing, and Auto Scaling to understand the infrastructure side of cloud computing.

I also learned and practiced Route 53 and can configure DNS records and routing. 

However, because this was a beginner project with a limited budget, I focused on the AWS services and practical work that I could perform within the available/free-tier resources instead of adding unnecessary paid services.

For the application part, I had limited prior knowledge of Flask and backend development. I still attempted to build a simple Flask application and connect it with the RDS MySQL database. 

I used some guidance from AI during this part to understand errors, configuration, and implementation, while doing the actual setup, testing, troubleshooting, and AWS integration myself. 

This helped me understand how an application connects to cloud infrastructure even though application development was not my primary focus.

Overall, this project was created as a hands-on learning project to strengthen my understanding of AWS Cloud infrastructure and to gain practical experience by building, testing, troubleshooting, and documenting the services I learned.


## AWS Services Used

- **Amazon VPC** — Created the isolated network for the project.
- **Subnets** — Used separate public and private subnets.
- **Internet Gateway** — Provided internet connectivity for public resources.
- **NAT Gateway** — Allowed resources in private subnets to access the internet outbound.
- **Route Tables** — Controlled traffic routing between subnets and gateways.
- **Security Groups** — Controlled network access between the ALB, EC2, and RDS.
- **Amazon EC2** — Used to run the web application.
- **Application Load Balancer** — Distributed incoming traffic to EC2 instances.
- **Auto Scaling Group** — Maintained EC2 instances and replaced unhealthy instances.
- **Amazon RDS (MySQL)** — Used as the application's database.
- **IAM** — Used to control access to AWS resources.
- **CloudWatch** — Used for monitoring and alarms.
- **SNS** — Used for notifications from CloudWatch.
