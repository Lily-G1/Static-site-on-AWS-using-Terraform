# Static website on AWS S3 using Terraform   
Hosting a static website on Amazon Web Services (AWS) can be a cost-effective and scalable solution for small to medium-sized websites.   
This repository contains terraform files that will quickly deploy a website on AWS S3, using AWS Cloudfront for global content delivery & provisions
a free SSL certificate with AWS Certificate Manager  

To run:  
$ terraform init  
$ terraform plan  
$ terraform apply  

NOTE: The folder 'site_files' will contain your website's source documents    

![S3_site_Diagram drawio](https://github.com/Lily-G1/Static-site-on-AWS-using-Terraform/assets/104821662/5801ecf6-432e-43df-900d-c99552c9b19b)
