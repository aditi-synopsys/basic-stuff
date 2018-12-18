


> **Installing, Activating and Deactivating Virtualenv**

 
To install **virtualenv** we are going to use **pip**, pip is a tool to manage and install Python packages. 

1.`sudo pip install virtualenv`

To start with every project in python, we will first create a Virtual Environment.  

For example my work-space is main directory for cloning all the projects. We will first create a new folder here for a project cloning.

2.`mkdir myproject`

Inside myproject, we will create a virtual environment with any name. Here we have created virtualenv with name venv.

3.`cd myproject`

4.`virtualenv venv`

Now start the virtual environment.

5.`source venv/bin/activate`


To stop virtualenv 

6.`deactivate`



Note:  If we want to specify python version for our  project then the command looks like. 

`virtualenv venv -p python3.6`








<!--stackedit_data:
eyJoaXN0b3J5IjpbLTI4NDk3ODA4LDE1NzU5NzQ0NjEsLTE5MD
YwNTA3NzhdfQ==
-->