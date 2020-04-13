# jumphost plan

Simple plan to build a VPC, ec2 instance and update packages for a jumphost. Once ready, ssh via output public IP address and account `ubuntu`.

```
terraform plan -out tfplan -var="key_name=hmoats" -var="private_key_file=/home/private/.ssh/id_rsa" -var="public_key_file=/home/private/.ssh/id_rsa.pub"
```
