# ecs\-task\-definition\-nonroot\-user<a name="ecs-task-definition-nonroot-user"></a>

Checks if ECSTaskDefinitions specify a user for Amazon Elastic Container Service \(Amazon ECS\) EC2 launch type containers to run on\. The rule is NON\_COMPLIANT if the ‘user’ parameter is not present or set to ‘root’\. 

**Identifier:** ECS\_TASK\_DEFINITION\_NONROOT\_USER

**Trigger type:** Configuration changes

**AWS Region:** All supported AWS regions except China \(Beijing\), Asia Pacific \(Jakarta\), Middle East \(UAE\), Asia Pacific \(Osaka\), AWS GovCloud \(US\-East\), AWS GovCloud \(US\-West\), Europe \(Spain\), China \(Ningxia\), Europe \(Zurich\) Region

**Parameters:**

None  

## AWS CloudFormation template<a name="w2aac12c31c27b9d243c15"></a>

To create AWS Config managed rules with AWS CloudFormation templates, see [Creating AWS Config Managed Rules With AWS CloudFormation Templates](aws-config-managed-rules-cloudformation-templates.md)\.