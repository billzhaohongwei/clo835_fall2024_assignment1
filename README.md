# Deploy one Amazon Ec2 instance in the public subnet of default VPC, with its security group and Amazon ECR repositories for webapp and MySQL images
terraform init
ssh-keygen -t rsa -f assignment1

terraform validate
terraform plan
terraform apply --auto-approve
