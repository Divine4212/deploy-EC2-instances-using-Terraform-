# deploy-EC2-instances-using-Terraform-
In this Project which will be carried out on aws, we'll create a vpc, 3 public subents, route table, internet gateway and associate the route table to each subnets.
we will also create 3 EC2 instances inside the subnets, security groups for load balancer and the instances.
finally, we will create load balancer, target groups, listener port and route 53 to point to the load balancer, all on aws.

Use terraform init for initialization
terraform plan to have an overview of the rsesources to be deployed
terraform apply to deploy the infrastructure on aws.
terraform destroy to destroy the infrustructure.
