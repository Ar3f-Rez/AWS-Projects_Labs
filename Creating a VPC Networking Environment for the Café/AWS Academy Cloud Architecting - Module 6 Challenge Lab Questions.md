Question 1: What is the purpose of the internet gateway in the public subnet?

 Allows instances in the private subnet to obtain a public IP address
 
 Allows instances in the public subnet to obtain a public IP addresss
 
 Allows instances in the public subnet with a public IP address to communicate with the internet
 
 Allows instances in the private subnet with a public IP address to communicate with the internet
 


Question 2: What allows the instance in the private subnet to connect to the internet so that it can download updates?

 The internet gateway in the public subnet
 
 The NAT gateway
 
 The Elastic IP address
 
 The default network ACL
 


Question 3: Can the instance in the private subnet be accessed directly from the internet?

 Yes
 
 No


Question 4: Why do you use two different key pairs to access the private instance and the bastion host?

 Each instance needs a different key pair
 
 It provided practice with creating key pairs
 
 Separate key pairs could help reduce the impact of a compromised bastion host
 
 Key pairs can't be reused
 


Question 5: Can the bastion host use ping and get a reply from the instance in the private subnet?

 Yes
 
 No
 


Question 6: Which security group rules allow the private EC2 instance to receive the return traffic when it pings the test instance?

 Outbound on private and outbound on test
 
 Outbound on private and inbound on test
 
 Inbound on private and outbound on test
 
 Inbound on private and inbound on test
 
