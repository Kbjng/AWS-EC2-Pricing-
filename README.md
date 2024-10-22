# AWS-EC2-Pricing-
Data Visualization and Normalization - A Key component
finding the middle between FinOps and Engineering data

Overview of AWS EC2 Pricing
Amazon EC2 (Elastic Compute Cloud) pricing is structured around several key components, allowing users to select the most cost-effective options based on their specific needs. Understanding these components is crucial for optimizing cloud expenditure.
Key Pricing Components
Clock Hours of Server Uptime: Charges are incurred based on the time instances are running, from launch until termination.
Instance Configuration and Type: Different instance types (e.g., t2.micro, m5.large) offer varying combinations of CPU, memory, and storage, impacting pricing.
Number of Instances: Users can provision multiple instances to handle varying workloads, affecting total costs.
Load Balancing: Using Elastic Load Balancing (ELB) incurs additional costs based on hours of operation and data processed.
Detailed Monitoring: Enhanced monitoring through Amazon CloudWatch incurs a fixed monthly fee in addition to basic monitoring costs.
Auto Scaling: Automatically adjusts the number of instances based on demand without extra charges beyond CloudWatch fees.
Pricing Models
AWS offers several pricing models tailored to different usage patterns:
1. On-Demand Instances
Description: Pay for compute capacity by the hour or second with no long-term commitment.
Ideal For: Applications with unpredictable workloads that cannot tolerate interruptions.
Cost Savings: None compared to other models; flexibility is the primary benefit.
2. Savings Plans
Description: Commit to a consistent amount of usage (EC2 + Fargate + Lambda) for one or three years.
Ideal For: Workloads with predictable usage patterns; offers significant savings (up to 72%) compared to On-Demand pricing.
Cost Savings: Discounts based on committed usage.
3. Spot Instances
Description: Purchase unused EC2 capacity at reduced rates (up to 90% off On-Demand prices).
Ideal For: Flexible workloads that can tolerate interruptions; suitable for batch processing jobs.
Cost Savings: Significant savings but subject to availability and potential termination by AWS.
4. Reserved Instances (RIs)
Description: Commit to using specific instance types for one or three years at discounted rates.
Ideal For: Steady-state workloads requiring guaranteed capacity.
Cost Savings: Offers substantial discounts compared to On-Demand pricing.
Cost Estimation Tools
To assist in budgeting and cost management, AWS provides the AWS Pricing Calculator, which allows users to estimate costs based on their specific configurations:
Select Services: Choose EC2 and other relevant services.
Configure Instances: Specify instance types, quantities, and regions.
Choose Pricing Models: Select from On-Demand, Savings Plans, or Reserved Instances as needed.
Review Estimates: The calculator provides a detailed breakdown of expected costs.
Practical Lab Exercise
Objective
To familiarize users with AWS EC2 pricing and cost estimation using the AWS Pricing Calculator.
Steps
Log into the AWS Management Console.
Open the AWS Pricing Calculator.
Create an estimate for two scenarios:
Scenario 1: Estimate costs for ten EC2 nodes in the Asia Pacific (Tokyo) region with specific resource requirements over a three-year term, partially paying upfront.
Scenario 2: Adjust the number of instances dynamically based on workload demands during peak hours.
Deliverables
Record both total upfront and monthly costs for each scenario and submit a link to your estimates generated in the calculator.
By understanding these pricing models and utilizing tools like the AWS Pricing Calculator, users can effectively manage their AWS expenditures while optimizing resource utilization.
