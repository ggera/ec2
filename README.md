# ec2
Automate the EC2 instance creation under load balancer with Ansible.
- Create a role with s3 access.
- Launch an ec2 instance with a role inside the private subnet of VPC, and install apache
through bootstrapping.
- Create a load balancer in public subnet.
- Add the ec2 instance, under the load balancer
- Create an auto scaling group with minimum size of 1 and maximum size of 3 with load balancer
- Add the created instances under the auto scaling group.
- Write a life cycle policy based on CPU utilization
