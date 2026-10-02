# Creating-IAM-roles-within-AWS
Documentation designed to help you efficiently create IAM roles for a service

Sign in to the AWS Management Console and search for IAM

<img width="949" height="515" alt="image" src="https://github.com/user-attachments/assets/03a40650-7e47-462d-81ca-7daaee75b787" />

In the left-hand navigation pane, click on Roles

<img width="957" height="1023" alt="image" src="https://github.com/user-attachments/assets/b85ee82d-0e1a-4aed-bbb8-d015a436a78d" />

Click the Create role button

Then you can choose one of the five types of trusted entity that will use this role: AWS Service

<img width="1920" height="738" alt="image" src="https://github.com/user-attachments/assets/d3890382-b1d8-4635-9fd0-ff905be96ffe" />

In the Use case section, select the specific service (for this example, EC2), then click Next

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/a9047b82-049a-4752-8bfb-7f91483d6339" />

Search and select the appropriate permission policy for the role. For this setup, select IAMReadOnlyAccess to grant the EC2 instance read-only access to IAM resources, then proceed by clicking Next

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/8ac0caf3-5608-4c22-9e30-9eaab24189d9" />

On the following page, you then provide a unique Role name and optional description. Review your trust policy and selected permissions. Upon finishing you review you can then click Create role

<img width="936" height="819" alt="image" src="https://github.com/user-attachments/assets/4bdcd65a-67d3-4e55-b7bc-23faf10e479a" />

JSON policy allows the Amazon EC2 service (ec2.amazonaws.com) to assume (take on) this IAM role and temporarily use its permissions

<img width="545" height="592" alt="image" src="https://github.com/user-attachments/assets/45f4dcea-d7dc-4919-8d78-d37973eff72e" />

Quick review of the permission policy summary verifies the role has IAMReadOnlyAccess as i selected 

<img width="538" height="616" alt="image" src="https://github.com/user-attachments/assets/c61b25d4-e7f4-4cc2-b5cc-3ab88341bcce" />
