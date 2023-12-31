# Databases
**Aurora**: `MySQL and PostgreSQL-compatible relational database. It features a distributed, fault-tolerant, self-healing storage system that auto-scales up to 128TB per database instance. It delivers high performance and availability with up to 15 low-latency read replicas, point-in-time recovery, continuous backup to Amazon S3, and replication across 3 AZs.`

**EMR**:`Elastic MapReduce`

**Glue**:`ETL: extract, transform and load`
**MSK**:`Managed Streaming for Apache Kafka`

# Protection
**Amazon GuardDuty** is a threat detection service that analyzes AWS CloudTrail, VPC Flow Logs, and DNS logs to detect malicious or unauthorized behavior.
**Amazon Macie** is a fully managed service that helps you discover and protect your sensitive data, using machine learning and pattern matching.

# Cost Optimization
**Cost Explorer** Choose an optimal Savings Plan (to lower prices on your bill)  Forecast usage up to 12 months based on previous usage with *graphs*

**monolithic application** -> containers
**ACL** Access Control List, NACL -> Network ACL,  Clients connect to a defined port, and expect a response on an ephemeral port Different Operating Systems use different port ranges, examples: IANA & MS Windows 10 è 49152 – 65535 Many Linux Kernels è 32768 – 60999

An **Internet Gateway** is used to connect a VPC to the internet while a **NAT Gateway** is used to connect the private subnet to the internet (through public subnet and Internet Gateway)¹. NAT Gateway is an access point for your private instance to access the internet but resources from the internet cannot access your private instance. NAT gateway is a one-way bridge for private resources

An EBS (Elastic Block Store) Volume is a network drive you can attach to your instances while they run They can only be mounted to one instance at a time (at the CCP level)
• They are bound to a specific availability zone Analogy: Think of them as a “network USB stick”