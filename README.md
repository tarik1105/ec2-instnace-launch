# Launching ec2 instance with ubuntu

requirements:
vs code, Terraform, aws cli and aws account

steps:
1. define aws as provider.
2. create vpn and a subnet with CIDR block.
3. configure Internet Gateway and route table so we can access our instances over internet.
4. configure Security groups to expose ports 22,80,443.
5. Create a network interface with an ip in the subnet and assign an elastic IP to the network interface.
6. Create Ubuntu server and install/enable apache2.

outputs:
<p align="center">
  <img src="/images/server-1.terraform.png" width="600" alt="server1-output">
  <img src="/images/server2.terraform.png" width="600" alt="server2-output">
</p>