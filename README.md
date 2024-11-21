 # CREATION IN WEB APPLICATION FOR TEST ENVIRONMENT
 NAME : Santhosh S

 REGISTER NO : 212222220039
 ## AIM
 To Creation in Web Application for Test Environment.
   
## PROBLEM STATEMENT
 Creating a web application for a test environment is essential to provide developers and testers with a dedicated platform to simulate, test, and validate software functionalities. The challenge lies in building an easy-to-use, scalable, and efficient application that supports realistic testing scenarios, automates workflows, and ensures smooth collaboration while minimizing setup and maintenance efforts.
    
## ALGORITHM
# Step 1:
Launch an EC2 instance in AWS using an Amazon Linux 2 AMI with a Security Group allowing HTTP and SSH traffic.
# Step 2:
Connect to the instance using SSH and install a web server like Apache
# Step 3:
Create a simple HTML file in the server's default directory with basic content for testing.
# Step 4:
Access the instance's public IP in a browser to verify the HTML page is displayed.

## COMMANDS
# webserver
To install httpd:
```
yum install httpd -y
```
To enable and start httpd :
```
systemctl enable httpd
systemctl start httpd
```
Create a simple HTML page :
```
cd /var/www/html
```
test.php
```
<!DOCTYPE html>
<html lang="en">
<head>
    <title>MY FIRST PHP!</title>
</head>
</body>
</html>
```

## OUTPUT
# TERMINAL

![Screenshot (295)](https://github.com/user-attachments/assets/1cae665f-6754-42cd-ab4f-df3898707059)

![Screenshot (296)](https://github.com/user-attachments/assets/8ce8f1cf-135d-4bd4-bbb1-d26c5b62f5ff)

![Screenshot (297)](https://github.com/user-attachments/assets/e2124e81-63ca-4f53-b7fd-c70486a03391)

# WEBPAGE

![Screenshot (292)](https://github.com/user-attachments/assets/87e339a2-ba81-4505-8935-ca2a0fb0822d)



## RESULT
Thus the web application for test environment has successfully been created and executed.
 

  


