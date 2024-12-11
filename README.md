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
  ![SG image](/secutity_groups.png)

  ### EC2 Instance Configured 
  I configured the EC2 with linux 2 AMI,
  selecting the VPC, ensuring the subnet has a public IP address 
  selected the Key pair i created earlier on.
  attached the above Security group and launched the instance.
  ![EC2 Instance successfully initialized img](/EC2_instance.png)


  ### Installing Apache through Git
  From AWS console, launcehed EC2 SSH cilent 
  a readily command promt was provided.
  Paste the command into git.
 ![installing Apcahe on Git img](/installig_aphache.png)
  
  
### Apache installed: test page
 Copy the Public IP address of my EC2 and paste into a new tab.
 Public IP address: 18.202.81.81
The final look...✨
![Testpage img](/testpage.png)
