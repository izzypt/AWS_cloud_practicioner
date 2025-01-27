# AWS_cloud_practicioner

The AWS Certified Cloud Practitioner certificate is an entry-level certification offered by Amazon Web Services (AWS) designed for individuals who want to build a foundational understanding of the AWS Cloud.

It’s a great first step for anyone considering a career in cloud computing or seeking to understand how AWS works in the broader context of IT and business.

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



# List of items

- [AWS Global Infrastructure](#1)
- [AWS Well-Architected](#2)
- [AWS EC2](#3)

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
