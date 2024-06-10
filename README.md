# AWS Wordpress Server Deployment

This repository provides a guide to deploying a WordPress website on an AWS EC2 instance using Apache2 and MySQL. It includes DNS configuration with Route 53, SSL setup using AWS Certificate Manager (ACM), and the implementation of an Application Load Balancer (ALB) for enhanced availability and security.

## Overview
This guide covers the following steps:

1. Launch an EC2 Instance: Create an Amazon Linux 2 instance and configure security groups to allow HTTP and SSH traffic.
   
3. Install and Configure Software: Install Apache2, MySQL, and PHP on the EC2 instance. Set up a MySQL database and user for WordPress.  
4. Deploy WordPress: Download WordPress, configure the wp-config.php file with database credentials, and adjust Apache2 settings.  
5. Set Up DNS with Route 53: Create a hosted zone for aryanvijcyberblog.com and configure DNS records.  
6. Verify Domain Ownership and Set Up SSL: Verify domain ownership via Google, request an SSL certificate from ACM, and configure HTTPS.  
7. Configure Application Load Balancer: Set up an ALB to distribute traffic across multiple instances and configure health checks.  
8. Finalize Deployment: Update DNS records to point to the ALB, ensuring the website is accessible and secure.  

## Results

Following these steps, aryanvijcyberblog.com will be a secure, scalable, and highly available WordPress site hosted on AWS. The deployment includes robust configurations for traffic management, security, and high availability.

This concise README provides an overview of the deployment process and highlights key steps involved.
