# EC2 (Elastic Compute Cloud)

## Overview

Amazon Elastic Compute Cloud (Amazon EC2) provides scalable computing capacity in the AWS Cloud. Using EC2 eliminates the need to invest in hardware up front, so you can develop and deploy applications faster. You can use EC2 to launch as many or as few virtual servers as you need, configure security and networking, and manage storage.

## Key Concepts

### 1. **Instances**
   - **Instance Types**: Various configurations of CPU, memory, storage, and networking capacity (e.g., t2.micro, m5.large).
   - **Instance Lifecycle**: States include pending, running, stopping, stopped, and terminated.
   - **Instance Purchasing Options**:
     - **On-Demand**: Pay for compute capacity by the hour or second with no long-term commitments.
     - **Reserved Instances**: Significant discount (up to 75%) compared to On-Demand pricing.
     - **Spot Instances**: Purchase unused capacity at reduced rates, but can be interrupted by AWS.

### 2. **AMI (Amazon Machine Images)**
   - Pre-configured templates for your instances that package the bits you need for your server (including the operating system, and additional software).

### 3. **Security Groups**
   - Virtual firewall that controls the traffic to and from your instance. Rules can be configured for inbound and outbound traffic.

### 4. **Elastic Block Store (EBS)**
   - Provides persistent block storage volumes for use with EC2 instances. EBS volumes are automatically replicated within their Availability Zone to protect from component failure.

### 5. **Elastic IP Addresses**
   - Static, public IPv4 addresses designed for dynamic cloud computing. An Elastic IP address is associated with your AWS account.

### 6. **Key Pairs**
   - Secure login information for your instances. AWS uses public-key cryptography to secure the login information for your instances.
