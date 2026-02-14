Assignment 1 – Launching Virtual Machine on AWS

Aim
To launch and configure a virtual machine on AWS using EC2 service.

Description
In this experiment, an EC2 instance was created using Amazon Linux 2023 AMI and t3.micro instance type. The instance was configured with a key pair, security group, and storage. The instance was successfully launched and verified in running state.

Configuration Details
AMI: Amazon Linux 2023
Instance Type: t3.micro
Storage: 8 GB
Security: SSH (Port 22) enabled
Credit Mode: Standard

Result
The EC2 instance was successfully launched and terminated safely to avoid charges.

Learning - 
1️⃣ AWS Management Console
What it is:
A web-based interface provided by AWS to manage cloud services.

Why we use it:
It allows users to create, configure, and monitor cloud resources easily without coding.

2️⃣ EC2 (Elastic Compute Cloud)
What it is:
EC2 is a service that provides virtual servers (virtual machines) in the cloud.

Why we use it:
It allows users to run applications without buying physical hardware.

Example:
Hosting a website on a virtual machine instead of using a local server.

3️⃣ Launch Instance
What it is:
Launching an instance means creating a new virtual machine.

Why we use it:
This step allocates computing resources like CPU, RAM, storage, and operating system.

4️⃣ AMI (Amazon Machine Image)
What it is:
An AMI is a template that contains the operating system and pre-installed software required to launch an instance.

Why we use it:
It helps quickly install and configure the operating system.

Example:
Amazon Linux 2023 provides a ready-to-use Linux environment.

5️⃣ Instance Type
What it is:
Instance type defines the hardware configuration of the virtual machine such as CPU and memory.

Why we use it:
Different applications require different computing power.

Example:
t3.micro provides 1 vCPU and 1 GB RAM suitable for small tasks.

6️⃣ Key Pair
What it is:
A key pair consists of a public key (stored in AWS) and a private key (.pem file stored locally).

Why we use it:
It provides secure authentication to access the EC2 instance via SSH.

7️⃣ Security Group
What it is:
A security group acts as a virtual firewall controlling inbound and outbound traffic.

Why we use it:
To allow or block specific network traffic for security purposes.

Example:
Allowing SSH (Port 22) to access the Linux server.

8️⃣ VPC (Virtual Private Cloud)
What it is:
A logically isolated network within AWS where instances are launched.

Why we use it:
It provides network-level security and isolation.

9️⃣ Auto-Assign Public IP
What it is:
Automatically assigns a public IP address to the instance.

Why we use it:
To connect to the instance from the internet.

🔟 Storage (EBS – Elastic Block Store)
What it is:
EBS provides persistent storage attached to the EC2 instance.

Why we use it:
To store operating system files, applications, and data.

1️⃣1️⃣ Advanced Settings (Important Controls)
🔹 Credit Specification

Controls CPU credit usage in burstable instances.

We selected Standard to avoid extra charges.

🔹 Detailed Monitoring

Provides enhanced monitoring through CloudWatch.

Disabled to reduce cost.

🔹 Tenancy

Defines whether instance runs on shared or dedicated hardware.

Selected Shared to minimize cost.

1️⃣2️⃣ Launch & Running State

What it is:
After launching, AWS allocates resources and starts the virtual machine.

Running state means:
The instance is active and ready to use.

1️⃣3️⃣ Termination

What it is:
Permanently deletes the instance and attached resources.

Why we use it:
To stop billing and free resources after demo.

🏁 Final Conclusion

The EC2 instance was successfully launched by configuring AMI, instance type, security settings, storage, and advanced options. The virtual machine was verified in running state and terminated safely.
