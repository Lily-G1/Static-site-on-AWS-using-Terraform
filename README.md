# Static website on AWS S3 using Terraform   
Hosting a static website on Amazon Web Services (AWS) can be a cost-effective and scalable solution for small to medium-sized websites.   
This repo contains terraform files that will quickly deploy a website on AWS S3, using Cloudfront for content delivery & provisioning
Certificate Manager for a free SSL certificate  

To run:  
$ terraform init  
$ terraform plan  
$ terraform apply  

NOTE: The foler 'site_files' will contain your website's files  
