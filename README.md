Template to create a Windows Server 2022 EC2 instance with specific requirements.

The server with the windows-2022 server actually throw an Error stating "Microsoft SQL Server is not supported for the instance type 't2.micro'.
However the EC2 was still created. 


Aws configure is set to us-east-1 so the subnet select is in the the avalibility zone. 
I made sure the Security group referrenced the EC2 and the VPC referrence both the EC2 and security group. 



