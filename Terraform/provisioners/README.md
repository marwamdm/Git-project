In this folders, we are going to see how to use provisioners 
Note that Terraform recommands to user other software to provision 
your resources since at this leval, Terraform looses it's idempontence 

we will be creating: 
A VPC (with subnents, gtw, routes )
Two instances with nginx on them
an elastic loadbalancer
an S3 backet to store the static site and the logs from the two instances
an AIM policie to allow instances to read and write in the s3 backet
two security groups (for instances and elb)
