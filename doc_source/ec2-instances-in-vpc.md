# ec2\-instances\-in\-vpc<a name="ec2-instances-in-vpc"></a>

Checks if your EC2 instances belong to a virtual private cloud \(VPC\)\. Optionally, you can specify the VPC ID to associate with your instances\.

**Identifier:** INSTANCES\_IN\_VPC

**Trigger type:** Configuration changes

**AWS Region:** All supported AWS regions except Asia Pacific \(Jakarta\), Africa \(Cape Town\), Middle East \(UAE\), Asia Pacific \(Osaka\), Europe \(Milan\), Europe \(Spain\), Europe \(Zurich\) Region

**Parameters:**

vpcId \(Optional\)Type: String  
VPC ID that contains these EC2 instances\.

## AWS CloudFormation template<a name="w2aac12c31c27b9d353c15"></a>

To create AWS Config managed rules with AWS CloudFormation templates, see [Creating AWS Config Managed Rules With AWS CloudFormation Templates](aws-config-managed-rules-cloudformation-templates.md)\.