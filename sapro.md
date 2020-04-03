I will attempt to document as i have been preparing to launch an affordable training course on AWS Solution Architect - Professional.

Services/ difficult topics I encountered:

1. Lots of AWS Organizations scenario (Multi AWS accounts)

2. Difference between SCP vs IAM Policy

3. AWS Organizations which has multiple Organizational Units (OU)

4. All services within Systems Manager ( Automation, Run Command, Session Manager, State Manager, Patch Manager, Maintenance Window)

5. When to use AWS Serverless Application Model (SAM) vs CloudFormation in deploying Lambda with DynamoDB

6. Server Migration Service (SMS) + DMS + SCT - Can you migrate non-VM servers using SMS?

7. AWS Rekognition

8. AWS Mechanical Turk, AppStream?

9. AWS CI/CD Services (CodeCommit, CodeBuild, CodeDeploy, CodePipeline)

10. S3 Requester Pays

11. AWS Config and its integration with other services. Like managing "approved" AMI.

12. Managing S3 Bucket Permissions - Notify if there is a publicly accessible object in the bucket. Trusted Advisor vs AWS Config?

13. AWS WAF - applying rules for ELB, CloudFront, Amazon API Gateway and EC2

14. AWS Shield Advanced vs AWS Shield Standard

15. Amazon ES (Elasticsearch?) - Kibana

16. Providing access to data and visualization tool: QuickSight vs Kibana

17. Direct Connect, Direct Connect Gateway, VIFs and LAG

18. Lambda accessing a database from outside your VPC.

19. Transit VPC + Connecting hundreds of VPCs in your on-premise data center

20. A difficult scenario on VPC Peering when one VPC is peered with 2 VPCs which uses Longest Prefix Match.

21. Migration on-premise IBM MQ / WebSphere? Use Amazon MQ or EC2?

22. Private Hosted Zone in Route 53 to connect the routing of your multiple VPCs..

23. Lambda@edge when authenticating a website

24. Improving CloudFront performance (Cache Hit Rate?)

25. X-Ray vs Inspector vs Systems Manager

26. Athena, S3 Select, Glacier Select differences

27. Provisioned IOPS vs GP2,

28. DynamoDB Streams

29. AWS Batch,

30. AWS Directory Service

31. SWF vs Step Functions

32. Cached Volume vs Stored Volume vs File vs Tape Gateway

33. VPC Endpoint + Private vs Public VIF?

34. 6 Rs of migration: https://aws.amazon.com/blogs/enterprise-strategy/6-strategies-for-migrating-applications-to-the-cloud/

Note: these are useful hints from Mukul G who has attempted the Feb 2019 version of the exam.