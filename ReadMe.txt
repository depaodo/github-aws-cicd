CloudFormation Scripts
These scripts automate the creation and configuration of VPCs, Subnets, EC2 Instances and CodePipeline. 


AB3 Pipeline- Creates a CI/CD pipeline for GitHub projects via Code Pipeine
EC2-VPCs Dev- Creates a Dev enviorment with an EC2 instance, VPC, and Subnet
EC2-VPCs Prod- Creates a Production enviorment with an EC2 instance, VPC, and Subnet

Sign in to the AWS Management Console and launch Clod Formation.

On the Create stack page, verify that the correct template name shows.

On the Specify stack details page, assign a name to your solution stack.

Under Parameters, review the parameters for the template and modify them as necessary.

Choose Next.

On the Configure stack options page, choose Next.

On the Review page, review and confirm the settings. Be sure to check the box acknowledging that the template will create AWS Identity and Access Management (IAM) resources.

Choose Create stack to deploy the stack.

You can view the status of the stack in the AWS CloudFormation console in the Status column. You should see a status of CREATE_COMPLETE.