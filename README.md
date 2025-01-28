# AWS_cloud_practicioner

The AWS Certified Cloud Practitioner certificate is an entry-level certification offered by Amazon Web Services (AWS) designed for individuals who want to build a foundational understanding of the AWS Cloud.

It’s a great first step for anyone considering a career in cloud computing or seeking to understand how AWS works in the broader context of IT and business.


# List of items

- [AWS Cloud Practiociner Exam tips](#0)
- [AWS Global Infrastructure](#1)
- [AWS Well-Architected](#2)
- [AWS EC2](#3)
- [AWS EBS - Elastic Block Store](#4)
- [AWS VPC - Virtual Private Cloud](#5)



<a id="0"></a>
# AWS Cloud Practiociner Exam tips

To pass the **AWS Certified Cloud Practitioner** exam, you need to focus on gaining a foundational understanding of AWS services, cloud concepts, security, and pricing. Here’s a step-by-step guide on what to read and study:

---

### 1. **AWS Cloud Practitioner Exam Guide**
   - **Start here**: Download the [AWS Certified Cloud Practitioner Exam Guide](https://aws.amazon.com/certification/certified-cloud-practitioner/) to understand the topics covered and their weight in the exam:
     - **Cloud Concepts** (26% of the exam)
     - **Security and Compliance** (25%)
     - **Technology** (33%)
     - **Billing and Pricing** (16%)

- [Exam guide pdf (23/01/2025)](https://d1.awsstatic.com/training-and-certification/docs-cloud-practitioner/AWS-Certified-Cloud-Practitioner_Exam-Guide.pdf)

---

### 2. **AWS Training Resources**
AWS offers free and paid resources to help you prepare:
   - **AWS Cloud Practitioner Essentials Course** (Free or Paid):
     - Available on AWS Training or Coursera.
     - Covers all key concepts in a structured manner.
   - **AWS Skill Builder** (Free):
     - Explore the free [Skill Builder platform](https://explore.skillbuilder.aws/) for self-paced training.
   - **AWS Whitepapers** (Free):
     - **Recommended Reading**:
       - [Overview of Amazon Web Services](https://aws.amazon.com/whitepapers/).
       - [AWS Well-Architected Framework](https://aws.amazon.com/architecture/well-architected/).
       - [Pricing Overview](https://aws.amazon.com/pricing/).

---

### 3. **Topics to Study**
Focus on these areas:
   - **Cloud Concepts**:
     - What is cloud computing? (e.g., scalability, elasticity, global reach)
     - Benefits of cloud computing (e.g., cost-efficiency, pay-as-you-go model).
     - Cloud deployment models (Public, Private, Hybrid).
   - **AWS Core Services**:
     - **Compute**: EC2, Lambda.
     - **Storage**: S3, EBS.
     - **Networking**: VPC, Route 53, CloudFront.
     - **Databases**: RDS, DynamoDB.
   - **Security and Compliance**:
     - Shared responsibility model.
     - IAM (Identity and Access Management) basics.
     - AWS Trusted Advisor and compliance programs.
   - **Billing and Pricing**:
     - AWS pricing models: Pay-as-you-go, Reserved Instances, Savings Plans.
     - AWS Cost Management tools: Cost Explorer, Billing Dashboard.
     - AWS Free Tier.
   - **Support Plans**:
     - AWS Basic, Developer, Business, and Enterprise Support Plans.

---

### 4. **Practice Exams**
   - Take **official AWS practice exams** or free mock tests to assess your readiness:
     - **AWS Certified Cloud Practitioner Practice Exam** (Available on the AWS website).
     - Platforms like Udemy, Whizlabs, and Tutorials Dojo offer high-quality practice exams.

---

### 5. **Study Timeframe**
   - If you’re consistent, you can prepare in **2–4 weeks**, dedicating 1–2 hours daily.
   - For beginners, spending 6–8 weeks ensures a solid understanding.

---

### 6. **Recommended Resources**
   - **Books**:
     - *AWS Certified Cloud Practitioner Study Guide* by Ben Piper.
   - **Video Courses**:
     - [Stephane Maarek’s AWS Cloud Practitioner Course](https://www.udemy.com/) (Highly recommended on Udemy).
   - **Flashcards**:
     - Quizlet or Tutorials Dojo flashcards for on-the-go revision.

---

![image](https://github.com/user-attachments/assets/e2f01f5e-cbae-4fdb-ade4-ca53a9fe6b55)

![image](https://github.com/user-attachments/assets/62fa8dc1-975e-40ae-81c8-8ccc366bc7db)

![image](https://github.com/user-attachments/assets/8b8a9762-7d73-4a71-a5d9-5d7fa17d840e)


<a id="1"></a>
# AWS Global Infrastructrure

Deliver a cloud infrastrucutre, companies can depend on no matter their size.

![image](https://github.com/user-attachments/assets/b1861a71-115b-464e-b0b8-4911b78e1ee7)

- 105 availability zones

- 33 geographic regions


  ![image](https://github.com/user-attachments/assets/b8f65318-b75d-487f-8477-d9b927ec8917)

- **AWS Region**s are geographically isolated areas containing multiple data centers, designed to provide services close to users and meet regulatory requirements. 

- **AWS Availability Zones (AZs)** are physically separate data centers within a Region, connected via low-latency networks, ensuring fault isolation and high availability.

![image](https://github.com/user-attachments/assets/2121b7e1-781b-47ba-a22a-0ffadffd8aa1)

<a id="2"></a>
# AWS Well-Architected

Helps cloud architects design infrastructure that is built arround 6 pillars:

1 - Operational excellence
  - Focuses on running and monitoring systems and continually improving processes and procedures.

2 - Security
  - Focuses on protecting information and systems

3 - Reliability
  - Focuses on ensuring workloads perform their assigned functions and recover qucickly from any faillure to meet demands.

4 - Performance efficiency
  - Focuses on selecting suitable resource types and sizes. Monitoring performance and maintining efficiency.

5 - Cost optimization
  - Focuses on understanding spending trends, contorlling fund allocation and scaling to meet the business needs without overspending.

6 - Sustainability
  - Minimizing environmental impact
  
![image](https://github.com/user-attachments/assets/058c0b8b-2444-4ab6-a34e-b29405fa37cf)

![image](https://github.com/user-attachments/assets/6757c11e-6dea-436c-9da5-bfa7423c69a5)

<a id="3"></a>
# AWS EC2

![image](https://github.com/user-attachments/assets/b1078f85-8fd9-4722-83a2-86f891ffe2f9)

**Amazon EC2 Basics Summary**  

Amazon Elastic Compute Cloud (EC2) is a core service of AWS that provides scalable, on-demand computing power in the cloud. It allows users to run virtual servers, known as instances, to host applications, process data, or handle workloads. Here are the key basics of EC2:  

1. **Instances**:  
   - EC2 instances are virtual servers that can be launched and configured as needed.  
   - Instances come in various types (e.g., General Purpose, Compute Optimized, Memory Optimized) to suit specific workloads.  

2. **AMI (Amazon Machine Image)**:  
   - An AMI is a pre-configured template that includes the operating system and any software or configuration needed to launch an instance.  

3. **Instance Sizes**:  
   - Instances have different sizes (CPU, memory, and storage capacities) to accommodate small to large-scale applications.  

4. **Elasticity and Scalability**:  
   - EC2 supports dynamic scaling, enabling you to add or remove instances based on workload demand.  

5. **Pricing Models**:  
   - **On-Demand**: Pay per hour or second, with no long-term commitment.  
   - **Reserved**: Commit to a fixed term (1 or 3 years) for significant cost savings.  
   - **Spot Instances**: Purchase unused capacity at a discount, suitable for flexible and fault-tolerant workloads.  

6. **Storage**:  
   - EC2 instances use Amazon Elastic Block Store (EBS) for persistent storage. Instance Store is an alternative for temporary, non-persistent storage.  

7. **Networking**:  
   - EC2 instances can be deployed within a Virtual Private Cloud (VPC) to provide secure, isolated networking. Public or private IPs can be assigned.  

8. **Security**:  
   - EC2 uses security groups (firewalls) to control inbound and outbound traffic. Key pairs (SSH keys) ensure secure access to instances.  

9. **Load Balancing and Auto Scaling**:  
   - Amazon EC2 works with Elastic Load Balancing (ELB) to distribute traffic and Auto Scaling to automatically adjust instance counts based on demand.  

10. **Monitoring**:  
    - Amazon CloudWatch provides monitoring of EC2 instances, offering metrics like CPU usage, disk I/O, and network traffic.  

EC2 is highly flexible, allowing users to scale resources up or down to match their application needs, ensuring cost-efficiency and adaptability in the cloud.

![image](https://github.com/user-attachments/assets/fcb54f6e-9720-4b05-ac05-b0fb66991a7d)

**EC2 Storage and Networking Summary**  

Amazon EC2 provides flexible storage and networking options to meet diverse application needs. Here’s a breakdown:  

### **Storage Options**  

1. **Elastic Block Store (EBS)**:  
   - Provides persistent block storage for EC2 instances.  
   - Data persists even after the instance is stopped or terminated.  
   - Storage types include:
     - **General Purpose SSD (gp3, gp2)**: Balanced performance for most workloads.  
     - **Provisioned IOPS SSD (io1, io2)**: High performance for I/O-intensive applications.  
     - **Throughput Optimized HDD (st1)**: Low-cost, high-throughput for big data and analytics.  
     - **Cold HDD (sc1)**: Low-cost storage for infrequently accessed data.  

2. **Instance Store**:  
   - Temporary, high-speed storage directly attached to the instance.  
   - Data is lost if the instance stops or terminates.  

3. **Amazon S3**:  
   - Object storage for scalable and durable storage of unstructured data.  
   - Suitable for backups, media storage, and data lakes.  

4. **Elastic File System (EFS)**:  
   - Managed file storage for EC2 instances.  
   - Automatically scales storage capacity as needed.  
   - Provides shared access across multiple instances.  

5. **AWS Storage Gateway**:  
   - Hybrid solution for on-premises and cloud storage integration.  

---

### **Networking in EC2**  

1. **Virtual Private Cloud (VPC)**:  
   - EC2 instances are deployed within a VPC for secure and isolated networking.  
   - Each instance gets private IPs within the VPC and optionally a public IP for internet access.  

2. **Elastic Network Interface (ENI)**:  
   - Virtual network interfaces that can be attached to EC2 instances.  
   - Used for high availability and fault-tolerant setups.  

3. **Elastic IP Addresses (EIPs)**:  
   - Static, public IP addresses that can be assigned to EC2 instances for consistent accessibility.  

4. **Security Groups**:  
   - Act as virtual firewalls, controlling inbound and outbound traffic at the instance level.  

5. **Network Access Control Lists (NACLs)**:  
   - Stateless firewalls that operate at the subnet level, providing additional layer security.  

6. **Elastic Load Balancing (ELB)**:  
   - Distributes incoming traffic across multiple EC2 instances to ensure high availability and fault tolerance.  

7. **Amazon PrivateLink**:  
   - Enables secure private connectivity to AWS services and applications without using the public internet.  

8. **AWS Direct Connect**:  
   - Provides a dedicated network connection between on-premises environments and AWS for high throughput and low latency.  

9. **Elastic Fabric Adapter (EFA)**:  
   - Enhances high-performance computing (HPC) applications by improving network performance.  

10. **AWS Global Accelerator**:  
    - Boosts application availability and performance by routing traffic through the AWS global network.  

### **Key Features**  
- EC2 instances can leverage **high-speed networking** with options like Enhanced Networking (SR-IOV) and AWS Nitro System.  
- Networking and storage services are designed to scale dynamically, supporting high throughput and low-latency demands.  

These storage and networking options make EC2 a powerful and adaptable service for both simple and complex workloads.

<a id="4"></a>
# AWS EBS - Elastic Block Store

### **AWS Elastic Block Store (EBS) Summary**

Amazon Elastic Block Store (EBS) is a scalable and high-performance block storage service designed for use with Amazon EC2 instances. It provides persistent storage that retains data independently of the EC2 instance lifecycle. Here are the key features and details:

---

### **Key Features**  
1. **Persistent and Reliable Storage**:  
   - EBS volumes store data redundantly across multiple physical devices in an Availability Zone to ensure durability.  
   - Data persists even after the associated EC2 instance is stopped or terminated.  

2. **Types of EBS Volumes**:  
   - EBS offers multiple volume types optimized for different use cases:
     - **General Purpose SSD (gp3, gp2)**: Cost-effective storage for general workloads (databases, boot volumes).  
     - **Provisioned IOPS SSD (io1, io2)**: High-performance storage for I/O-intensive applications like transactional databases.  
     - **Throughput Optimized HDD (st1)**: Low-cost, high-throughput storage for big data and analytics.  
     - **Cold HDD (sc1)**: Low-cost storage for infrequently accessed data.  

3. **Snapshot Capability**:  
   - EBS volumes can be backed up as snapshots stored in Amazon S3.  
   - Snapshots can be used to restore volumes, migrate data, or create new volumes.  

4. **Scalability and Elasticity**:  
   - Volumes can be resized dynamically without downtime, allowing easy scaling of storage.  

5. **Encryption**:  
   - EBS supports encryption at rest and in transit using AWS-managed or customer-managed keys (via AWS KMS).  
   - Encryption includes volume data, snapshots, and all data in transit.  

6. **Performance Optimization**:  
   - Volumes can be optimized for throughput or IOPS, depending on workload needs.  
   - gp3 volumes allow customization of IOPS and throughput independently of storage size.  

7. **Attach and Detach Flexibility**:  
   - EBS volumes can be attached to or detached from EC2 instances, even across different instances within the same Availability Zone.  

---

### **Use Cases**  
1. **Boot Volumes**:  
   - EBS is commonly used as the primary storage for booting EC2 instances.  

2. **Databases**:  
   - High-performance volumes like io2/io1 are ideal for database workloads requiring low latency and high throughput.  

3. **Data Warehousing**:  
   - st1 volumes offer affordable storage for large-scale data processing and analytics.  

4. **Backup and Disaster Recovery**:  
   - EBS snapshots enable efficient backups and recovery solutions.  

---

### **Pricing**  
- EBS pricing is based on volume type, size, and provisioned performance (IOPS/throughput).  
- Snapshots are billed separately based on the storage used in S3.  

---

### **Advantages**  
- **High Availability**: Redundant storage within a single Availability Zone.  
- **Flexibility**: Customizable volumes to fit workload demands.  
- **Integration**: Seamlessly integrates with EC2 and other AWS services.  
- **Data Durability**: Snapshots enable easy backup and restoration.  

EBS provides a versatile and dependable block storage solution for a wide variety of workloads, making it an essential component for managing EC2 instances efficiently.


![image](https://github.com/user-attachments/assets/e7340704-e47c-4bf6-80a9-66c9b8fcbf58)

<a id="5"></a>
# AWS Virtual Private Cloud

![image](https://github.com/user-attachments/assets/a7b9dd23-b2d2-4cfd-9394-1060b41a2d69)

A **Virtual Private Cloud (VPC)** is a logically isolated network environment in the cloud. It allows you to define and manage a virtual network that closely resembles a traditional on-premises data center network, but with the scalability, flexibility, and resources of the cloud. 

Here's an overview of key aspects of a VPC:

### 1. **Isolation**
   - A VPC is isolated from other networks in the cloud provider's infrastructure, ensuring security and control.
   - You can control inbound and outbound traffic for resources within the VPC using network access control lists (ACLs) and security groups.

### 2. **Subnetting**
   - A VPC can be divided into smaller subnets, which are segments of the network that can be either **public** (accessible from the internet) or **private** (accessible only within the VPC or via a VPN/Direct Connect).

### 3. **Customizable IP Address Range**
   - When creating a VPC, you define its IP address range using **CIDR (Classless Inter-Domain Routing)** notation, such as `10.0.0.0/16`.
   - This range determines how many IP addresses are available within the VPC.

### 4. **Networking Features**
   - You can connect your VPC to the internet via an **Internet Gateway** for public resources.
   - For private connectivity, you can use a **VPN** or **Direct Connect** to link the VPC to your on-premises network.
   - A **NAT Gateway** allows private resources to access the internet without exposing them to inbound traffic.
   - You can also use **VPC Peering** to connect multiple VPCs or services within the same or different regions.

### 5. **Security**
   - **Security Groups** act as virtual firewalls for your instances, controlling inbound and outbound traffic.
   - **Network Access Control Lists (NACLs)** provide an additional layer of security at the subnet level.

### 6. **Use Cases**
   - Hosting web applications or APIs with tightly controlled access.
   - Isolating sensitive workloads and databases in private subnets.
   - Creating hybrid cloud environments by extending on-premises networks to the cloud.
   - Setting up multi-tier architectures with public and private subnets.

### 7. **Cloud Provider Support**
   - Major cloud providers like AWS, Google Cloud, and Microsoft Azure all offer VPCs as part of their infrastructure services:
     - **AWS VPC**: Amazon's implementation allows full customization of networking.
     - **Azure Virtual Network (VNet)**: Similar concept with features for Azure's ecosystem.
     - **Google Cloud VPC**: A global VPC architecture with per-region subnets.

In essence, a VPC gives you the tools to build and manage a secure, scalable network environment in the cloud, making it fundamental for most cloud-based architectures.

### more on route tables...

A **route table** is a critical component of a cloud or network infrastructure that defines how network traffic is directed within a network or between networks. In the context of a **Virtual Private Cloud (VPC)**, a route table acts as a set of rules that determine where data packets should go based on their destination IP address.

### Key Concepts of Route Tables:

#### 1. **Routes**
   - Each entry in a route table is called a **route**.
   - A route defines a **destination** (IP range) and a **target** (where the traffic should be sent).
   - For example:
     - **Destination**: `0.0.0.0/0` (default route for all traffic)
     - **Target**: Internet Gateway, NAT Gateway, or another network device.

#### 2. **Types of Route Tables**
   - **Main Route Table**: The default route table for a VPC, automatically created when the VPC is set up. All subnets in the VPC are initially associated with this route table unless explicitly changed.
   - **Custom Route Table**: A user-defined route table that you can associate with specific subnets to customize routing for certain parts of your network.

#### 3. **Subnet Association**
   - Subnets in a VPC must be associated with a route table. 
   - A single route table can be associated with multiple subnets, but a subnet can only be associated with one route table at a time.

#### 4. **Targets**
   Route tables use targets to determine where traffic should be sent. Common targets include:
   - **Internet Gateway**: For traffic destined for the internet.
   - **NAT Gateway**: For private subnets to access the internet without exposing resources to inbound traffic.
   - **VPC Peering Connection**: For traffic between VPCs.
   - **Virtual Private Gateway**: For traffic routed through a VPN connection to an on-premises network.
   - **Local**: For traffic within the VPC itself.

#### 5. **Default Routes**
   - The most common route is the **default route** (`0.0.0.0/0`), which directs traffic to the internet or other external networks.
   - You can also define specific routes, such as `10.0.1.0/24`, for traffic within specific subnets.

---

### Example in AWS VPC

- **Scenario**: You have a VPC with two subnets: a public subnet and a private subnet.
  - Public subnet: Needs access to the internet.
  - Private subnet: Needs access to the internet through a NAT Gateway.

- **Route Table Setup**:
  - **Public Subnet's Route Table**:
    - `Destination: 0.0.0.0/0` → `Target: Internet Gateway`
  - **Private Subnet's Route Table**:
    - `Destination: 0.0.0.0/0` → `Target: NAT Gateway`
    - `Destination: 10.0.0.0/16` → `Target: Local` (for internal communication within the VPC)

---

### How Route Tables Work
1. **Packet Matching**: When traffic is sent from an instance, the route table looks for a matching destination in its rules. If no match is found, the packet is dropped.
2. **Priority**: The most specific route (longest prefix match) is selected first. For example:
   - Traffic to `10.0.1.1` will use a route with `10.0.1.0/24` before a broader `10.0.0.0/16` route.

---

### Common Use Cases
- Controlling internet access for different subnets (e.g., public vs. private).
- Routing traffic between VPCs in a peered network.
- Directing traffic to on-premises networks via a VPN.
- Segmenting traffic for multi-region or hybrid architectures.

By customizing route tables, you can fine-tune how your network traffic flows, ensuring security, performance, and proper routing for different workloads.
