# AWS Web Application Deployment (EC2 + ALB + RDS)

## Architecture
- Custom VPC with public and private subnets
- EC2 (Apache Web Server) in public subnet
- RDS MySQL in private subnet
- Security Groups with least privilege access

## Services Used
- Amazon EC2
- Amazon VPC
- Security Groups
- Application Load Balancer
- Amazon RDS (MySQL)

## Flow
Internet → ALB → EC2 → RDS

## Verification
- Web server accessible via browser
- Database accessible only from EC2

## Author
Ayush Pallav

## Links
GitHub: https://github.com/<your-username>/aws-ec2-alb-rds-project  
Live URL: http://<web-ec2-129094402.ap-south-1.elb.amazonaws.com>


