# Creating-IAM-roles-within-AWS
Documentation designed to help you efficiently create IAM roles for a service

Sign in to the AWS Management Console and search for IAM

<img width="949" height="515" alt="image" src="https://github.com/user-attachments/assets/03a40650-7e47-462d-81ca-7daaee75b787" />

In the left-hand navigation pane, click on Roles

<img width="957" height="1023" alt="image" src="https://github.com/user-attachments/assets/b85ee82d-0e1a-4aed-bbb8-d015a436a78d" />

Click the Create role button

Then you can choose one of the five types of trusted entity that will use this role: AWS Service

<img width="1920" height="738" alt="image" src="https://github.com/user-attachments/assets/d3890382-b1d8-4635-9fd0-ff905be96ffe" />

In the Use case section, select the specific service (for example, EC2), then click Next

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/a9047b82-049a-4752-8bfb-7f91483d6339" />

Search and select the appropriate permission policy for the role. For this setup, select IAMReadOnlyAccess to grant the EC2 instance read-only access to IAM resources, then proceed by clicking Next

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/8ac0caf3-5608-4c22-9e30-9eaab24189d9" />

