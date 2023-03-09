## What is a Technology stack?
A technology stack is a set of tools or frameworks that is known to work nicely together to produce properly functional software products. Examples are:

- LAMP (Linux, Apache, MySQL, PHP or Python, or Perl)
- LEMP (Linux, Nginx, MySQL, PHP or Python, or Perl)
- MERN (MongoDB, ExpressJS, ReactJS, NodeJS)
- MEAN (MongoDB, ExpressJS, AngularJS, NodeJS

STEP 1 — INSTALLING APACHE AND UPDATING THE FIREWALL
Install Apache using Ubuntu’s package manager ‘apt’:

#update a list of packages in package manager
sudo apt update

#run apache2 package installation
sudo apt install apache2

To verify that apache2 is running as a Service in our OS, use following command
sudo systemctl status apache2

You should find a printout on your console like the one below:
![new project 1](https://user-images.githubusercontent.com/112444993/223901025-103955be-3979-464a-a05f-9db647d39a6a.png)

Step 2 is  installation   and log in to the MySQL console 
![Screenshot 2023-02-13 184405(3)](https://user-images.githubusercontent.com/112444993/223903086-08648280-cadb-4454-8979-6f82630f2c5b.png)

Step 3- Using these sudo apt install php libapache2-mod-php php-mysql to allows PHP to communicate with MySQL-based databases which brings the result below

![new-project 1(4)](https://user-images.githubusercontent.com/112444993/223904673-3b520462-cc41-432c-a397-853b96f7b3a6.png)

Step 4 - Setting  up projectlamp domain,make sure your configuration file doesn’t contain syntax errors and finally creating a index.html file in that location to make sure that the virtual host works as expected and run it on the browser which brings this below.

![new 1(5)](https://user-images.githubusercontent.com/112444993/223906432-d03a6345-0743-4057-aede-4780aad715d1.png)

Step 5 - The final step which we ENABLE PHP ON THE WEBSITE with these final command in the step "vim /var/www/projectlamp/index.php" and acessing the url below
http://<Public-IP-Address>:80, brings this result
  
  ![new pro 1](https://user-images.githubusercontent.com/112444993/223907225-ccd662cb-b7a3-40d5-ae21-465d259ee76a.png)
