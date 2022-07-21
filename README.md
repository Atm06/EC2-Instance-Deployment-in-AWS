# EC2-Instance-Deployment-in-AWS


We will look into the process of launching instances that is through AWS CLI(Command Line Interface). 

AWS CLI is a unified tool for running and managing your various AWS services. Just download and install the tool and you will be able to control multiple AWS services from the command line. For Developers, it is a great tool for managing AWS services.
Begin with AWS CLI by launching an EC2 Instance using it. Creating an instance with AWS CLI is the same as launching one with AWS console. Open your command prompt as administrator by right-clicking on it.

# Creating a VPC
The first thing to do is to create a VPC(virtual private cloud) under which an EC2 instance will be launched. 

# Creating Subnets
Next, create two subnets and make one as public to make it accessible from the internet.

# Creating Internet Gateway
Internet gateway is used by the private subnet to access the internet for its updates and other packages installations. 

# Creating Route Table
The next step is to create a route table and assigning it to the already created VPC. After creating the route table assign the route to this route table.

# Associating Route Table and modifying subnet 
The next step is to associate the route table with the subnet and making the same subnet as public by mapping the public IP address to it. Enter the SubnetId and RouteTableId that you noted earlier.

# Creating Key Pair and Security Group
The most important step is to create a key pair. This key pair must be kept safe and secure with the user so that the person can access the EC2 instance created using this key pair.

# Running the EC2 Instance
Finally, after all the setup completed successfully now the time is to run the instance. 

Viewing the Instance 
Now after the instance status is “running” type the command to view the complete details of the EC2 instance that you just created:

# Verifying the EC2 Instance 
To verify whether the EC2 instance created using the AWS CLI is created as per need, log in to your AWS Console and open the EC2 service and check for the instance.

