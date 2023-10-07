# Designing-an-Elastic-Highly-Available-Architecture-in-AWS
Creating a scalable and resilient website that contains a dashboard for monitoring.

First, I gonna create security groups for a load balancer and an Auto Scaling group.
and then I will create a launch template that you will use to create EC2 instances. 
Next, I will create an Auto Scaling group. 
and then I will attach the Auto Scaling group to a new Application Load Balancer. 
Finally, I will connect to the website through the load balancer. 
and then I will create a CloudWatch dashboard to monitor the load balancer.
