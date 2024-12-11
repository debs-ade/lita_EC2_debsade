# lita_EC2_debsade
This is a documention of the process of configuring EC2 and deploying Apache web server

The goal of this project is to crate a more capaable infrastructure for Smartshop that will handle it expansion to an online store.
 
### To achieve that new infastrcture has to be:
Scalable
Reliable
Security
Cost effective
### The technology used via Amazon Web Serive;
   Elastic Compute Cloud EC2
   Virtual Private Cloud VPC
   Security Groups 
   key pair 

   ### Security Group Creation 
  Using the already provided VPC, set inbound and outbounds rule.
  Allow all SSH at 22 and HTTP at 80 traffic
  ![SG image](/security_groups.png)

  ### EC2 Instance Configed 
  I configured the EC2 with linux 2 AMI,
  selecting the VPC, ensuring the subnet has a public IP address 
  selected the Key pair i created earlier on.
  attached the above Security group and launched the instance.
  ![EC2 Instance successfully initialized img](/EC2_instance.png)
  
  
