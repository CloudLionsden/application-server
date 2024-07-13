This is a template to create an AWS t2.micro ec2 with a windows-2022 server in us-east-1, default vpc with access to a sql database server.


I will be honest, the Windows -2022 server and the SQL had me thinking because there are no  2022 Microsoft SQL Server versions  that support t2 micro or t3.micro. That was an easy fix, the SQL servers support those grades are versions before 2017.

Thought did go in to this. I wondered how I could launch ec2 without exposing my vpcID. I kept going back to the parameters, to open up the options for vpc, like the requirements stating. All I could think about is how to make this template reusable and secure.  I'm sure I could have figured it out later. 

I made sure the VpcId was in parameter to have the option to choose at launch.
I verified everything is working as expected on the management console. 
