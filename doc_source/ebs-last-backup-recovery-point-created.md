# ebs\-last\-backup\-recovery\-point\-created<a name="ebs-last-backup-recovery-point-created"></a>

Checks if a recovery point was created for Amazon Elastic Block Store \(Amazon EBS\)\. The rule is NON\_COMPLIANT if the Amazon EBS volume does not have a corresponding recovery point created within the specified time period\. 

**Identifier:** EBS\_LAST\_BACKUP\_RECOVERY\_POINT\_CREATED

**Trigger type:** Periodic

**AWS Region:** All supported AWS regions except China \(Beijing\), Asia Pacific \(Jakarta\), Middle East \(UAE\), Asia Pacific \(Osaka\), AWS GovCloud \(US\-East\), AWS GovCloud \(US\-West\), Europe \(Spain\), China \(Ningxia\), Europe \(Zurich\) Region

**Parameters:**

resourceTags \(Optional\)Type: String  
Tags of Amazon EBS volumes for the rule to check, in JSON format `{"tagkey" : "tagValue"}`\.

resourceId \(Optional\)Type: String  
ID of Amazon EBS volume for the rule to check\.

recoveryPointAgeValue \(Optional\)Type: intDefault: 1  
Numerical value for maximum allowed age\. No more than 744 for hours, 31 for days\.

recoveryPointAgeUnit \(Optional\)Type: StringDefault: days  
Unit of time for maximum allowed age\. Accepted values: 'hours', 'days'\.

## AWS CloudFormation template<a name="w2aac12c31c27b9d167c15"></a>

To create AWS Config managed rules with AWS CloudFormation templates, see [Creating AWS Config Managed Rules With AWS CloudFormation Templates](aws-config-managed-rules-cloudformation-templates.md)\.