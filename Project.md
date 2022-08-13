Step 1 - Create a directory named vagrant-vms

Command: mkdir vagrant

Step 2 - Clone the source code into a directory.

Command: git clone <source code>

Step 3 - Open sublime text editor or visual studio code.
![vagrant file](https://user-images.githubusercontent.com/52894481/184517120-1e4b0a7c-1915-48b9-b462-a74f11fffa30.PNG)

Step 4 - When the shell scripts in the vagrantfile pan out to be accurate, bring up the VMs on which the services will run on.

Command: vagrant up

Output

![servers](https://user-images.githubusercontent.com/52894481/184517128-82783e7c-5afe-4396-a84a-85d2e57c53d5.PNG)

Step 5 - Log in via browser to validate that the stack runs as expected. NGINX --> Tomcat --> RabbitMQ --> Memcached --> Mysql

![webs](https://user-images.githubusercontent.com/52894481/184517140-960d0e0f-a38e-4351-8473-72db3297cd22.JPG)




