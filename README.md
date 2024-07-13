This is a template to create a aws t2.micro ec2 with a windows-2022 server in us-east-1 in default vpc with access to a sql database server.

As you can see in the script I use two subnets, One for the app instance and one for the RDS. Each resource My rationale, the RDs is referencing the Subnet group and the Subnet group is referencing the
I will be honest, the Windows -2022 server and the SQL had me thinking because there are no  2022 Microsoft SQL Server versions  that support t2 micro or t3.micro. That was an easy fix, the SQL servers support those grades are versions before 2017.

Thought did go in to this. I wondered how I could launch ec2 without exposing my vpcID. I kept going back to the parameter to open up the option vpc like the requirement stating. I'm sure I could have figured it out later. 

I made sure the VpcId was in parameter to have the option to choose at launch.
I verified everything is working as expected on the management console. 
