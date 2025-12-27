# Deploying Dynamic Webserver using LAMP in Amazon-Linux 
## Introduction:  
This project display how to set up and deploy a dynamic web server using the 
LAMP (Linux, Apache, MySQL, PHP) in Amazon Linux. The LAMP stack is one of the 
most widely used open-source solutions for hosting dynamic websites and web 
application. 
 Linux – Operating system (Ubuntu / Amazon- linux)  
 Apache – Web server to serve Http request 
 MySQL / Mariadb – Database server to store application data  
 PHP – Server-side scripting language for dynamic content 
# Step of deployment 
## Step1: Linux ec2 instance 

![tg](image/1.png)

## Step2 : Connect the ec2 instances and updates the packages 
![tg](image/2.png)

## Step3: Install package manager httpd- 
![tg](image/3.png)

## Step4: Check the instances Start ,enable, status httpd instances 

![tg](image/4.png)

 
 
## Step5: Install the  mariadb105-server database

![tg](image/5.png)

 
 
 
## Step6: Check the mariadb 105-server start ,enable ,status. 

![tg](image/6.png)

## Step7: Install php and extension  
![tg](image/7.png)

## Step8 Start and enable ,status of the php –fpm  
![tg](image/8.png)

## Step 9: Go to html folder and edit the files using vim editor- 
![tg](image/9.png)

## Step10: Write a simple html file. 
![tg](image/10.png)

## Step11:  Create a index.php file 

![tg](image/11.png)

## Step12: Write a simple php file 

![tg](image/13.png)

 
 
## Step13:  Test Website copy the public IP address and past. 

![tg](image/14.png)

 
 
 
 
 
 
 
 
 
 