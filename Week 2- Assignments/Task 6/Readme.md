[6]Create a Internal and External Load Balancer

This task demonstrates how to create both Internet-facing (External) and Internal Load Balancers using AWS EC2 and VPC services.

Step 1: Create Load Balancer
Navigate to EC2 → Load Balancers → Create Load Balancer.

Choose Application Load Balancer.
Set the following:
Name: external-alb
Scheme:
Internet-facing for external

Internal for internal

IP address type: IPv4

Listener: Add HTTP listener on port 80

<br>
🔹 Select Availability Zones and Subnets
Select at least two Availability Zones and assign a subnet for each:

✅ eu-north-1a (eun1-az1)

✅ eu-north-1b (eun1-az2)


Each selected AZ must have a subnet associated with it.
        ![image](https://github.com/user-attachments/assets/f70cc086-d05a-4caa-8a60-1abd61198ba4)
        Zone
        ![image](https://github.com/user-attachments/assets/756bbc29-8e4d-4241-a5a4-2ae4f891c613)

Summary
![image](https://github.com/user-attachments/assets/3cd2b29f-1769-43c2-bffd-9223188042d8)

Step 2: Created Load Balancer
        ![image](https://github.com/user-attachments/assets/f820c24d-6085-4632-aa9e-06bb5f2ea3d2)
