# ifconfig me plan

Simple plan to build a VPC, ec2 instance, install a few packages and then curl to the ec2 instance web servers to display your public IP address. 

```
terraform plan -out tfplan -var="key_name=hmoats" -var="private_key_file=/home/private/.ssh/id_rsa" -var="public_key_file=/home/private/.ssh/id_rsa.pub"
```
