# DevOps Home Lab Project
### Objective
The project's objective is to solve my struggle with financial planning and give me a nice overview on how far away I'm from my next goal and will also keep track of my crypto investments.
Once the application is ready I will deploy it in a AWS based cloud server with all the infrastructure provisioned using Terraform and Ansible, setting up a complete pipeline that will test, build, check code quality and deploy the app to dev and prod environments. And then finally automating key manual points in the process.

 

### Application To do

 - [ ] Create the [front-end](https://github.com/luiw3/homelab01_front-end) using React and Typescript
	 - [ ] Login and Register page
	 - [ ] Expenses CRUD
	 - [ ] Cryptos CRUD
	 - [ ] Goals CRUD
	 - [ ] Profile
	 - [ ] Make it responsive
	 - [ ] Dashboard
	 - [ ] Tax calculator (future)
 - [ ] Create the [back-end](https://github.com/luiw3/homelab01_back-end) using Node.js
	 - [ ] Configure project with typescript
	 - [ ] Configure automatic lint
	 - [ ] Set up bearer token to verify users
	 - [ ] Bearer token auto-refresh
	 - [ ] Products CRUD
	 - [ ] Expenses CRUD
	 - [ ] Cryptos CRUD
	 - [ ] Goals CRUD
	 - [ ] User CRUD
	 - [ ] WebSockets
	 - [ ] Errors logging

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
