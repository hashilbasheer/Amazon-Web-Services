## Automated Way to Upgrade EC2 instance drivers (Windows/Linux) using AWSSupport-UpgradeWindowsAWSDrivers 

### Step 1: Create an IAM role with SSMCore permission and attach it to an EC2 instance (which we created now), Then it will be visible in SSM page (coz SSM agent is installed on these servers by attaching required IAM role)

![image](https://user-images.githubusercontent.com/54981984/99684925-01eb4400-2aa8-11eb-8ceb-70ec950b5eca.png)

### Step 2: Automation--> Execute

![image](https://user-images.githubusercontent.com/54981984/99686396-91452700-2aa9-11eb-9547-48d1809613df.png)

### Step 3: ![image](https://user-images.githubusercontent.com/54981984/99686553-b2a61300-2aa9-11eb-8841-d192ebfa3ffc.png)

![image](https://user-images.githubusercontent.com/54981984/99686720-e08b5780-2aa9-11eb-9f4d-413a8a337059.png)

![image](https://user-images.githubusercontent.com/54981984/99686846-00228000-2aaa-11eb-9c49-8c3498c0ab0b.png)

### AWSSupport-UpgradeWindowsAWSDrivers will automate the following tasks 

Part 1: Installing and upgrading AWS PV drivers
Part 2: Installing and upgrading ENA
Part 3: Upgrading AWS NVMe drivers

### Step 4: Part 4: Updating EC2Config and EC2Launch

### Step 5: Part 5: Installing the serial port driver for bare metal instances

UseCase
![image](https://user-images.githubusercontent.com/54981984/99688157-7a9fcf80-2aab-11eb-8693-c3de55e9603d.png)


![image](https://user-images.githubusercontent.com/54981984/99689244-c56e1700-2aac-11eb-8e4c-4e23f0356e70.png)
