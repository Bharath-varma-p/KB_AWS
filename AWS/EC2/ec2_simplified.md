# EC2 Simplified Version

## Defination

Amazon EC2 (Elastic Compute Cloud) is like renting a computer that you can use through the internet. Instead of buying a physical computer, you can use EC2 to run applications, store data, and handle tasks on Amazon's powerful servers. This way, you only pay for the time you use it, and you can choose how powerful you want it to be, just like choosing different types of computers depending on what you need them for.

- It's Fully Managed Container Orchestration Service that helps you to more easily deploy Scale and then in containers 


**Key Features**

      - The following are the key features
            - SLA Commitment of 99.99% Availability 
            - AWS Nitro System is Build in for the Security 
            - We have Savings Plan which optimize the Performance to save cost 
            - It Has Migration tools which makes it easy to Switch between the Clouds with Amazon Lightsail or AWS Managed Services 
            - 


<h5 align="center" > 
    <img src="./ec2.png"><br>
    This is the Image of EC2 Logo
</h5>

### EC2 Configuration Options

Amazon EC2 provides several configuration options that allow you to tailor your virtual machine to your specific needs. Here are some of the key configuration options:

1. **Instance Types**: Choose from a variety of instance types based on the CPU, memory, and storage that best fit your application. For example, a `t2.micro` instance is great for low-traffic websites, while a `c5.9xlarge` is better suited for compute-intensive applications.

2. **Storage Options**: EC2 offers different types of storage including:

   - **EBS (Elastic Block Store)**: Persistent storage volumes for your data, which can be attached to any EC2 instance. For example, use an `EBS General Purpose SSD (gp2)` for a balance of price and performance.
   - **Instance Store**: Temporary storage that is physically attached to the host computer. Instance store is ideal for temporary data that changes frequently, like buffer, cache, or scratch data.

3. **Network Settings**: Configure the VPC (Virtual Private Cloud) and security groups to control inbound and outbound traffic to your instances. For example, you might allow only HTTP and SSH traffic to reach your web server.

4. **AMI (Amazon Machine Image)**: Select from pre-configured AMIs or create your own with the operating system and software stack required for your application.

5. **Key Pairs**: Use key pairs for secure SSH access to your instances. Generate a key pair in the EC2 console, and use the private key to log in securely.

### Simple Example

Think of Amazon EC2 like a hotel for computers. When you travel, instead of buying a house, you rent a hotel room with features you need: maybe just a bed and bathroom, or perhaps a suite with multiple rooms and luxury amenities. Similarly, with EC2, you rent computing power with the specific features you need for as long as you need it. You can choose the size of the "room" (instance type), the type of "bed" (storage), and even the "view" (network settings) to ensure your stay (computing task) is exactly as you want it.

#### BootStrap Scripts

- Bootstrap scripts in EC2, also known as user data, are used to automatically configure an instance upon startup. You can use these scripts to install software, update settings, or run administrative tasks. This feature is particularly useful for automating the setup process of instances, ensuring that they are fully configured and ready to use as soon as they launch.

    <h5 align="center">
        <img src="./Bootstrap_Scripts.png">
        <br />
        EC2: 1 Please refer to this Image - [Bootstrap Script]
    </h5>
