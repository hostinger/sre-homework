## Hostinger SRE practical homework

Please create Ansible playbook with a role(s) which should do the following tasks:

The role(s) should do the following tasks:

- Install OpenResty
- Install Redis
- Configure OpenResty with Lua support to talk with Redis service
- Write a simple Lua snippet which will create a connection to Redis, fetch the data and return the data as a body response
- Write tests for all those aforementioned tasks
- Redis credentials MUST be under an encrypted vault

Please use the software stack below:

https://github.com/test-kitchen/kitchen-vagrant

https://github.com/neillturner/kitchen-ansible

https://github.com/sstephenson/bats

## Question 1
A service daemon in production stopped working and not responding to network requests. You received alert about the health of the service and logged in the affected node to troubleshoot. Please describe in detail what actions would you do and how are you going to do that.

## Question 2
You are asked to prepare a development environment to be fully ready to develop and test the application using Kubernetes and [12factor](https://12factor.net) methodology. Please define how the CI/CD workflow would look like and which tools you gonna use and why.

## Requirements for the homework

* Please answer each question in a separate _txt_ file.
* Please use _git_ for practical exercise to log all changes you do.
* Write the summary line and description of what you have done in the imperative mode, that is as if you were commanding someone. Start the line with "Add", "Change" instead of "Fixed", "Added", "Changed".
* Archive homework practical exercise into a single .tar.gz, .zip, etc.
* Send homework to our HR as a single file.
