


> **Installing, Activating and Deactivating Virtualenv**

 
To install **virtualenv** we are going to use **pip**, pip is a tool to manage and install Python packages. 

`sudo pip3.6 install virtualenv`

To start with every project in python, we will first create a Virtual Environment.  

For example my work-space is main directory for cloning all the projects. We will first create a new folder here for a project cloning.

`mkdir myproject`

Inside myproject, we will create a virtual environment with any name. Here we have created virtualenv with name venv.

`cd myproject`

`virtualenv venv`

Now start the virtual environment.
`source venv/bin/activate`


To stop virtualenv 
`deactivate`



Note:  If we want to specify python version for our  project then the command looks like. 

`virtualenv venv -p python3.6`








<!--stackedit_data:
eyJoaXN0b3J5IjpbOTI0MjA5NzEwLC0xOTA2MDUwNzc4XX0=
-->