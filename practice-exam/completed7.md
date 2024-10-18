12. Which service provides a virtually unlimited amount of online highly durable object storage?
    - A. Amazon Redshift
    - B. Amazon Elastic File System (Amazon EFS)
    - C. Amazon Elastic Container Service (Amazon ECS)
    - D. Amazon S3

    <details markdown=1><summary markdown="span">Answer</summary>

    Correct Answer: D

    Explanation: <https://aws.amazon.com/what-is-cloud-object-storage/>

    </details>

16. Which AWS service provides a simple and scalable shared file storage solution for use with Linux-based AWS and on-premises servers?
    - A. Amazon S3
    - B. Amazon Glacier
    - C. Amazon EBS
    - D. Amazon EFS

    <details markdown=1><summary markdown="span">Answer</summary>

    Correct Answer: D

    Explanation:
    - Amazon Elastic File System (Amazon EFS) provides a simple, scalable, fully managed elastic NFS file system for use with AWS Cloud services and on-premises resources.
    - It is built to scale on demand to petabytes without disrupting applications, growing and shrinking automatically as you add and remove files, eliminating the need to provision and manage capacity to accommodate growth.
    - Amazon EFS is designed to provide the throughput, IOPS, and low latency needed for Linux workloads.
    - Throughput and IOPS scale as a file system grows and can burst to higher throughput levels for short periods of time to support the unpredictable performance needs of file workloads.
    - For the most demanding workloads, Amazon EFS can support performance over 10 GB/sec and up to 500,000 IOPS.

    </details>
    
25. What is Amazon CloudWatch?
    - A. A code repository with customizable build and team commit features.
    - B. A metrics repository with customizable notification thresholds and channels.
    - C. A security configuration repository with threat analytics.
    - D. A rule repository of a web application firewall with automated vulnerability prevention features.

    <details markdown=1><summary markdown="span">Answer</summary>

    Correct Answer: B

    Explanation:
    - Amazon CloudWatch is basically a metrics repository.
    - An AWS service -- such as Amazon EC2 -- puts metrics into the repository, and you retrieve statistics based on those metrics.
    - If you put your own custom metrics into the repository, you can retrieve statistics on these metrics as well.

    Reference: <https://docs.aws.amazon.com/AmazonCloudWatch/latest/monitoring/> cloudwatch_architecture.html

    </details>

27. Which of the following services could be used to deploy an application to servers running on-premises? (Select TWO.)
    - A. AWS Elastic Beanstalk
    - B. AWS OpsWorks
    - C. AWS CodeDeploy
    - D. AWS Batch
    - E. AWS X-Ray

    <details markdown=1><summary markdown="span">Answer</summary>

    Correct Answer: BC

    Explanation:
    - <https://docs.aws.amazon.com/codedeploy/latest/userguide/instances-on-premises.html>
    - <https://aws.amazon.com/blogs/aws/opsworks-on-prem-and-existing-instances/>

    </details>

30. Which is the MINIMUM AWS Support plan that allows for one-hour target response time for support cases?
    - A. Enterprise
    - B. Business
    - C. Developer
    - D. Basic

    <details markdown=1><summary markdown="span">Answer</summary>

    Correct Answer: B

    Explanation: <https://aws.amazon.com/premiumsupport/plans/>

    </details>


34. Which of the following steps should be taken by a customer when conducting penetration testing on AWS?
    - A. Conduct penetration testing using Amazon Inspector, and then notify AWS support.
    - B. Request and wait for approval from the customer's internal security team, and then conduct testing.
    - C. Notify AWS support, and then conduct testing immediately.
    - D. Request and wait for approval from AWS support, and then conduct testing.

    <details markdown=1><summary markdown="span">Answer</summary>

    Correct Answer: D

    Explanation:
    - AWS customers are welcome to carry out security assessments or penetration tests against their AWS infrastructure without prior approval for 8 services.

    Reference: <https://aws.amazon.com/security/penetration-testing/>

    </details>


37. Which AWS Cost Management tool allows you to view the most granular data about your AWS bill?
    - A. AWS Cost Explorer
    - B. AWS Budgets
    - C. AWS Cost and Usage report
    - D. AWS Billing dashboard

    <details markdown=1><summary markdown="span">Answer</summary>

    Correct Answer: C

    Explanation:
    - The Cost & Usage Report is your one-stop-shop for accessing the most granular data about your AWS costs and usage.
    - You can also load your cost and usage information into Amazon Athena, Amazon Redshift, AWS QuickSight, or a tool of your choice.

    Reference: <https://aws.amazon.com/aws-cost-management/>

    </details>


49. Which of the following features can be configured through the Amazon Virtual Private Cloud (Amazon VPC) Dashboard? (Select TWO.)
    - A. Amazon CloudFront distributions
    - B. Amazon Route 53
    - C. Security Groups
    - D. Subnets
    - E. Elastic Load Balancing

    <details markdown=1><summary markdown="span">Answer</summary>

    Correct Answer: CD

    Explanation:
    - Amazon Virtual Private Cloud (Amazon VPC) lets you provision a logically isolated section of the AWS Cloud where you can launch AWS resources in a virtual network that you define.
    - You have complete control over your virtual networking environment, including selection of your own IP address range, creation of subnets, and configuration of route tables and network gateways.
    - You can use both IPv4 and IPv6 in your VPC for secure and easy access to resources and applications.
    - You can easily customize the network configuration for your Amazon VPC.
    - For example, you can create a public-facing subnet for your web servers that has access to the Internet, and place your backend systems such as databases or application servers in a private-facing subnet with no Internet access.
    - You can leverage multiple layers of security, including security groups and network access control lists, to help control access to Amazon EC2 instances in each subnet.

    Reference: <https://aws.amazon.com/vpc/>

    </details>


