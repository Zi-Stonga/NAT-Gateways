# AWS NAT Gateways


### Setting up NAT Gateways in Amazon Web Services

#### NAT Gateways allow internet access for instances in a private subnet. They also enable private subnets to connect to other Amazon Web Services. NAT Gateways prevent the internet from connecting with instances in a private subnet. 

## Process 

1. Sign into the AWS Management Console
2. Create a VPC

![alt text](https://github.com/Zi-Stonga/NAT-Gateways/blob/main/Images/VPC.PNG)
4. Create Public and Private Subnets
![alt text](https://github.com/Zi-Stonga/NAT-Gateways/blob/main/Images/Subnet.PNG)
5. Create an Internet Gateway
![alt text](https://github.com/Zi-Stonga/NAT-Gateways/blob/main/Images/Internet-Gateway2.PNG)
6. Create Public Route Table and Configure 
![alt text](https://github.com/Zi-Stonga/NAT-Gateways/blob/main/Images/Route-Table2.PNG)
7. Launch an EC2 Instance in the Public and Private Subnets
![alt text](https://github.com/Zi-Stonga/NAT-Gateways/blob/main/Images/Instance-Launched.PNG)
