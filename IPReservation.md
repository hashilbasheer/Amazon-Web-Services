## Step 1: Create Network Interface and assign IP to it


![image](https://user-images.githubusercontent.com/54981984/99785766-9b1b6880-2b43-11eb-8460-07c4efdcd5e7.png)


## Step 2:Attach this ENI to the EC2 instance which we want to reserve IP (we can add the ENI while the launching ec2 )


![image](https://user-images.githubusercontent.com/54981984/99787383-acfe0b00-2b45-11eb-9293-40804738a106.png)


### We can see that ENI is attached to the EC2 instances (as private IP) and note that we have to select the EC2 subnet in same availability zone as the ENI AZ
