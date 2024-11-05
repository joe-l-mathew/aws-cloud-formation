# Cloud Formation templates

- ## S3 with versioning

Cloud Formation Output
![alt](./s3-cft.png)

S3 bucket Details Page
![alt](./s3-listing.png)


- ## EC2 with key pair and subnet 

* Created a VPC with prpvided CIDR Range
* Created a subnet inide the vpc by dynamicaly passig the ref
* Created a security group inside the vpc
* Created EC2 instance with image, key, subnet, vpc etc

Cloud Formation Layout

![alt](./ec2-cft.png)

Cloud Formation output

![alt](./ec2-op.png)

