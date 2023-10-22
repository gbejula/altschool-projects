# Cloud Engineering Second Semester Examination Project.
## This is the documentation for Deployment of Laravel and installation of LAMP stack.


Using the Vagrantfile script, the master and the slave Ubuntu-based servers are created. 

- Master Ubuntu
![Master Ubuntu](/images/master_ubuntu.png)

- Slave Ubuntu
![Slave Ubuntu](/images/slave_ubuntu.png)

Using the script.sh in the master box, the deployment of the LAMP stack was created.

- LAMP Stack

![LAMP STACK in master](/images/LAMP_shot.png)

The PHP application is cloned from GitHub and it installs all the necessary packages, and configure Apache web server and MYSQL.

- The laravel is application is installed and shown on the browser. The ip address of the master is 192.168.20.5 and it is shown in the image below:

![Laravel in Master box](/images/master_laravel.png)

Also, using the ansible playbook, the script is run and the LAMP stack is also deployed in the slave Ubuntu-based server. See below:

![LAMP stack in slave](/images/slave_lamp_shot.png)

The ip address of the slave box is 192.168.20.6. Laravel in the slave machine below:

![Laravel in Slave box](/images/slave-laravel.png)