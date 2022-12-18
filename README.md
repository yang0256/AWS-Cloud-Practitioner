Domain 1: Cloud Concepts 26%

1.1 Define the AWS Cloud and its value proposition

•	Define the benefits of the AWS cloud including:
•	Security (AWS Documentation: Advantages of Cloud Security)
•	Reliability (AWS Documentation: Reliability)
•	High Availability
•	Elasticity (AWS Documentation: Elasticity)
•	Agility
•	Pay-as-you go pricing (AWS Documentation: AWS Pricing)
•	Scalability
•	Global Reach
•	Economy of scale
•	Explain how the AWS cloud allows users to focus on business value
•	Shifting technical resources to revenue-generating activities as opposed to managing infrastructure (AWS Documentation: Business Value on AWS)

1.2 Identify aspects of AWS Cloud economics

•	Define items that would be part of a Total Cost of Ownership proposal
•	Understand the role of operational expenses (OpEx)
•	Understand the role of capital expenses (CapEx)
•	Understand labor costs associated with on-premises operations (AWS Documentation: AWS Pricing/TCO Tools)
•	Understand the impact of software licensing costs when moving to the cloud (AWS Documentation: Cost and licensing)
•	Identify which operations will reduce costs by moving to the cloud
•	Right-sized infrastructure (AWS Documentation: Right Sizing)
•	Benefits of automation (AWS Documentation: Automation, Investing in Cloud Automation)
•	Reduce compliance scope (for example, reporting) (AWS Documentation: Minimizing the PCI Compliance Burden Using Containerization, Microservices, and AWS)
•	Managed services (for example, RDS, ECS, EKS, DynamoDB) (AWS Documentation: AWS Managed Services)

1.3 Explain the different cloud architecture design principles

•	Explain the design principles
•	Design for failure (AWS Documentation: Design for Failure)
•	Decouple components versus monolithic architecture (AWS Documentation: Decomposing monoliths into microservices)
•	Implement elasticity in the cloud versus on-premises (AWS Documentation: Elasticity)
•	Think parallel

Domain 2: Security and Compliance 25%

2.1 Define the AWS shared responsibility model

•	Recognize the elements of the Shared Responsibility Model (AWS Documentation: Shared Responsibility Model)
•	Describe the customer’s responsibility on AWS
•	Describe how the customer’s responsibilities may shift depending on the service used (for example with RDS, Lambda, or EC2) (AWS Documentation: Shared Responsibility, Shared Responsibility Model)
•	Describe AWS responsibilities Shared Responsibility Model)

2.2 Define AWS Cloud security and compliance concepts

•	Identify where to find AWS compliance information (AWS Documentation: AWS Compliance Programs, Compliance Resources)
•	Locations of lists of recognized available compliance controls (for example, HIPPA, SOCs) (AWS Documentation: HIPAA, SOC)
•	Recognize that compliance requirements vary among AWS services (AWS Documentation: Security and compliance)
•	At a high level, describe how customers achieve compliance on AWS (AWS Documentation: AWS Compliance)
•	Identify different encryption options on AWS (for example, In transit, At rest) (AWS Documentation: Encryption of Data in Transit, Encryption of Data at Rest)
•	Describe who enables encryption on AWS for a given service (AWS Documentation: importance of encryption and how AWS can help)
•	Recognize there are services that will aid in auditing and reporting (AWS Documentation: AWS Audit Manager)
•	Recognize that logs exist for auditing and monitoring (do not have to understand the logs) (AWS Documentation: Viewing HSM audit logs in CloudWatch Logs)
•	Define Amazon CloudWatch, AWS Config, and AWS CloudTrail (AWS Documentation: Amazon CloudWatch, AWS Config, AWS CloudTrail)
•	Explain the concept of least privileged access (AWS Documentation: Security best practices in IAM)

2.3 Identify AWS access management capabilities

•	Understand the purpose of User and Identity Management
•	Access keys and password policies (rotation, complexity) (AWS Documentation: Managing access keys for IAM users, Setting an account password policy for IAM users)
•	Multi-Factor Authentication (MFA) (AWS Documentation: Using multi-factor authentication (MFA) in AWS)
•	AWS Identity and Access Management (IAM) (AWS Documentation: AWS Identity and Access Management (IAM))
•	Groups/users (AWS Documentation: IAM Identities (users, user groups, and roles))
•	Roles (AWS Documentation: IAM roles)
•	Policies, managed policies compared to custom policies (AWS Documentation: Policies and permissions in IAM, AWS managed policies)
•	Tasks that require use of root accounts (AWS Documentation: AWS account root user credentials and IAM user credentials)
•	Protection of root accounts (AWS Documentation: best practices for securing my AWS account)

2.4 Identify resources for security support

•	Recognize there are different network security capabilities
•	Native AWS services (for example, security groups, Network ACLs, AWS WAF) (AWS Documentation: Control traffic to subnets using Network ACLs, Control traffic to resources using security groups, AWS WAF)
•	3rd party security products from the AWS Marketplace
•	Recognize there is documentation and where to find it (for example, best practices, whitepapers, official documents)
•	AWS Knowledge Center, Security Center, security forum, and security blogs (AWS Documentation: AWS Knowledge Center)
•	Partner Systems Integrators (AWS Documentation: Next-Gen MSP Meets Global Systems Integrator on AWS)
•	Know that security checks are a component of AWS Trusted Advisor (AWS Documentation: AWS Trusted Advisor check reference)


Domain 3: Technology 33%

3.1 Define methods of deploying and operating in the AWS Cloud

•	Identify at a high level different ways of provisioning and operating in the AWS cloud
•	Programmatic access, APIs, SDKs, AWS Management Console, CLI, Infrastructure as Code (AWS Documentation: AWS APIs, AWS SDK for JavaScript, AWS Management Console, AWS Command Line Interface, Infrastructure as Code)
•	Identify different types of cloud deployment models
•	All in with cloud/cloud native (AWS Documentation: Cloud-Native)
•	Hybrid (AWS Documentation: Hybrid Cloud with AWS)
•	On-premises (AWS Documentation: Deployments on an EC2/On-Premises Compute Platform)
•	Identify connectivity options
•	VPN (AWS Documentation: AWS VPN)
•	AWS Direct Connect (AWS Documentation: AWS Direct Connect)
•	Public internet (AWS Documentation: Connect to the internet using an internet gateway)

3.2 Define the AWS global infrastructure

•	Describe the relationships among Regions, Availability Zones, and Edge Locations (AWS Documentation: Regions and Zones, Regions and Availability Zones)
•	Describe how to achieve high availability through the use of multiple Availability Zones
•	Recall that high availability is achieved by using multiple Availability Zones (AWS Documentation: Multi-AZ deployments for high availability, Amazon RDS Multi-AZ)
•	Recognize that Availability Zones do not share single points of failure
•	Describe when to consider the use of multiple AWS Regions (AWS Documentation: Multi-Region Application Architecture)
•	Disaster recovery/business continuity (AWS Documentation: Disaster recovery options in the cloud, Business Continuity Plan (BCP))
•	Low latency for end-users (AWS Documentation: Low-latency computing with AWS Local Zones)
•	Data sovereignty (AWS Documentation: Embrace Data Sovereignty)
•	Describe at a high level the benefits of Edge Locations (AWS Documentation: AWS for the Edge)
•	Amazon CloudFront (AWS Documentation: Amazon CloudFront)
•	AWS Global Accelerator (AWS Documentation: AWS Global Accelerator)

3.3 Identify the core AWS services

•	Describe the categories of services on AWS (compute, storage, network, database) (AWS Documentation: AWS Cloud Products)
•	Identify AWS compute services
•	Recognize there are different compute families (AWS Documentation: Amazon EC2 Instance Types)
•	Recognize the different services that provide compute (for example, AWS Lambda compared to Amazon Elastic Container Service (Amazon ECS), or Amazon EC2, etc.) (AWS Documentation: Compute Services)
•	Recognize that elasticity is achieved through Auto Scaling
•	Identify the purpose of load balancers (AWS Documentation: Application Load Balancer)
•	Identify different AWS storage services
•	Describe Amazon S3 (AWS Documentation: Amazon S3)
•	Describe Amazon Elastic Block Store (Amazon EBS) (AWS Documentation: Amazon Elastic Block Store (Amazon EBS))
•	Describe Amazon S3 Glacier (AWS Documentation: Amazon S3 Glacier)
•	Describe AWS Snowball (AWS Documentation: AWS Snowball)
•	Describe Amazon Elastic File System (Amazon EFS) (AWS Documentation: Use Amazon EFS with Amazon EC2)
•	Describe AWS Storage Gateway (AWS Documentation: Amazon S3 File Gateway)
•	Identify AWS networking services
•	Identify VPC (AWS Documentation: Finding information to connect to a VPC)
•	Identify security groups (AWS Documentation: Finding information to connect to a VPC)
•	Identify the purpose of Amazon Route 53 (AWS Documentation: Amazon Route 53)
•	Identify VPN, AWS Direct Connect (AWS Documentation: Identifying a Site-to-Site VPN connection, AWS Direct Connect)
•	Identify different AWS database services
•	Install databases on Amazon EC2 compared to AWS managed databases (AWS Documentation: Choosing between Amazon RDS, Amazon EC2, or VMware Cloud)
•	Identify Amazon RDS (AWS Documentation: Amazon RDS DB instances)
•	Identify Amazon DynamoDB (AWS Documentation: Amazon DynamoDB)
•	Identify Amazon Redshift (AWS Documentation: Getting started with Amazon Redshift)

3.4 Identify resources for technology support

•	Recognize there is documentation (best practices, whitepapers, AWS Knowledge Center, forums, blogs) (AWS Documentation: Follow Security Best Practices, AWS Knowledge Center, AWS Whitepapers & Guides)
•	Identify the various levels and scope of AWS support
•	AWS Abuse (AWS Documentation: report abuse of AWS resources)
•	AWS support cases (AWS Documentation: Creating support cases and case management)
•	Premium support
•	Technical Account Managers (AWS Documentation: AWS Enterprise Support)
•	Recognize there is a partner network (marketplace, third-party) including Independent Software Vendors and System Integrators (AWS Documentation: AWS Partner Network, AWS Partner Paths)
•	Identify sources of AWS technical assistance and knowledge including professional services, solution architects, training and certification, and the Amazon Partner Network (AWS Documentation: technical support from AWS, AWS Professional Services, Successful solutions architects do these five things)
•	Identify the benefits of using AWS Trusted Advisor (AWS Documentation: AWS Trusted Advisor)

Domain 4: Billing and Pricing 16%

4.1 Compare and contrast the various pricing models for AWS (for example, On-Demand Instances, Reserved Instances, and Spot Instance pricing) (AWS Documentation: Amazon EC2 pricing)

•	Identify scenarios/best fit for On-Demand Instance pricing (AWS Documentation: Amazon EC2 On-Demand Pricing, On-Demand Instances)
•	Identify scenarios/best fit for Reserved-Instance pricing (AWS Documentation: Reserved Instances, Amazon EC2 Reserved Instances)
•	Describe Reserved-Instances flexibility (AWS Documentation: Instance Size Flexibility for EC2 Reserved Instances)
•	Describe Reserved-Instances behavior in AWS Organizations (AWS Documentation: Reserved Instances)
•	Identify scenarios/best fit for Spot Instance pricing (AWS Documentation: Spot Instances)

4.2 Recognize the various account structures in relation to AWS billing and pricing

•	Recognize that consolidated billing is a feature of AWS Organizations (AWS Documentation: Consolidated billing for AWS Organizations)
•	Identify how multiple accounts aid in allocating costs across departments (AWS Documentation: AWS Cost Allocation For Customer Bills, Cost Allocation Basics)
4.3 Identify resources available for billing support
•	Identify ways to get billing support and information (AWS Documentation: AWS Billing and Cost Management)
•	Cost Explorer, AWS Cost and Usage Report, Amazon QuickSight, third-party partners, and AWS Marketplace tools (AWS Documentation: Analyzing your costs with AWS Cost Explorer, AWS Cost and Usage Reports, Amazon QuickSight, AWS Managed Service Provider Partners)
•	Open a billing support case (AWS Documentation: Creating support cases and case management)
•	The role of the Concierge for AWS Enterprise Support Plan customers (AWS Documentation: AWS Enterprise Support)
•	Identify where to find pricing information on AWS services
•	AWS Simple Monthly Calculator (AWS Documentation: AWS Pricing Calculator console)
•	AWS Services product pages (AWS Documentation: Using the Products page)
•	AWS Pricing API (AWS Documentation: AWS Price List API)
•	Recognize that alarms/alerts exist (AWS Documentation: Creating a billing alarm to monitor your estimated AWS charges)
•	Identify how tags are used in cost allocation (AWS Documentation: Using Cost Allocation Tags)

