# itran-lab3

1. Create an AWS infrastructure via terraform

- EC2 instance
- SecurityGroup
- VPC

# run these commands
-> terraform plan
-> terraform apply -auto-approve

After provisioning all the staff we’ll see the OUTPUT (5min approx)

Or you can type the command:

-> terraform output

OUTPUT:

instance = "3.84.174.145"

2. ssh -i yuriy_ec2.pem ubuntu@3.84.174.145

3. Test services is running

-> service Nginx status

-> service MySQL status

![wordpress installed successfully](https://github.com/ivnovyuriy/itran-lab3/blob/6ff4be705897a5e4b900d3ca1237dd91c59dacc6/img/1.png)