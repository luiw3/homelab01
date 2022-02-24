# DevOps Home Lab Project
### Objective
This project's objective is to setup a simple store stock manager application in a cloud server based in AWS with all the infrastructure provisioned using Terraform and Ansible, setting up a complete pipeline that will test, build, check code quality and deploy the app to dev and prod environments. And then finally automating key manual points in the process.

 

### Application To do

 - [ ] Create the front-end using Vue.js
	 - [ ] Index page with some info about the store
	 - [ ] Products listing
	 - [ ] Add product to cart
	 - [ ] Registration page
	 - [ ] Login page
	 - [ ] Check out page
 - [ ] Create the back-end using Adonis
	 - [ ] Set up bearer token to verify users
	 - [ ] Bearer token auto-refresh
	 - [ ] Products CRUD
	 - [ ]  User details
	 - [ ]  Set up email notification sender
		 - [ ]  When finishing the purchase
		 - [ ]  When changing the order status to shipped
	 - [ ]  WebSockets

### Environment Set Up To Do

 - [ ] Set up the AWS machine with the basics packages needed
 - [ ] Configure Jenkins agent on the server to execute the pipelines remotely
 - [ ] Set up nginx server so the application can be accessed 
 - [ ] Configure reverse proxy
 - [ ] Verify all basic security configuration
 - [ ] Create ssh users and set up permissions
 - [ ] Translate to code all configurations that were made
	 - [ ]  Create a Terraform definition to set up AWS instace with basic configuration
	 - [ ] Create Ansible playbooks that will deal with the post instalation configuration
 - [ ]  Containerize the entire application
	 - [ ] Orchestrate the deploys with Kubernetes
 - [ ] Automate key manual tasks

### Automations To Do

This part will remain unfinished as the more I work on the projects more items that will need automation will surge
	

 - [ ] Local dev environment set up automation (Will install basic software needed)
 - [ ] Branch creation and commits routines
 - [ ] Application backups into Amazon S3
 - [ ] Production deploy
