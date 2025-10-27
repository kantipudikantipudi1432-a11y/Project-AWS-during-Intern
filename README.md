# Project-AWS-during-Intern
Secure VPC Architecture With NAT Gate way & WebHosting


Step 1:Virtual Private Cloud create .
step 2: To create VPC specific IP range (By Choose ) assign.
Step 3:Create to Subnet's.
step 4: Public Subnet for web servers or internet-facing services.
step 5:Private Subnet - internal systems to Internet Gateway attach cheyyadam and for configure Route tables Properly.
Step 6:Next in Private subnet need to have Internet access for instances for NAT gateway.
Step 7:Connect NAT gateway to private subnet.
Step 8:For Private subnet Create a route table in internet-bound traffic, to add NAT Gateway.
Step 9:To Host a web we can use  EC2 instance or S3, Better to use ec2.
Step 10: Perfer EC2 instance in public subnet to launch.
Step 11: Perfer Web server (Apache/Nginx) install.
Step 12:perfer HTML/CSS/JS Template files and  upload.
Step 13:Add Security Group in HTTP/HTTPS access allow.
Step 14:IAM Roles & Policies: only required permissions.
Step 15: Test the application.
Step 16:Access the Website in public IP or domain.
If applicable
Step 17:
For Extra alerts add (like load balancer load,
usage) If to send exceed "Look's Unique for Step 17"
