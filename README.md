### Hostinger DevOps homework (Practical)

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

### Question 1
A service daemon in production stopped working and not responding to network requests. You received alert about the health of the service and logged in the affected node to troubleshoot. Please describe in detail what actions would you do and how are you going to do that.

### Question 2
A user on a Linux machine enters `curl https://www.hostinger.com`. Please describe in as much detail as you can the lifecycle of the command and what happens in the kernel, over the network, and on Hostinger servers before the command completes.

### Question 3
You have one MySQL instance which becomes saturated. Please describe in as much detail as you can how and what technologies would you use to scale MySQL service to handle thousands of requests.

## Requirements for the homework

* Please answer each question in a separate _txt_ file.
* Please use _git_ for practical exercise to log all changes you do.
* Write the summary line and description of what you have done in the imperative mode, that is as if you were commanding someone. Start the line with "Add", "Change" instead of "Fixed", "Added", "Changed".
* Archive homework practical exercise into a single .tar.gz, .zip, etc.
* Send homework to our HR as a single file.
