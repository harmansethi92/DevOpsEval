# DevOpsEval

The requirments for this project are:-

Create a new t2.micro Amazon EC2 instance in us-east-1 using the provided credentials and keypair (named DevOpsEval).

Upload the binary found here.

Place the binary somewhere on the system (use your best judgment as to where this should live).

Configure the binary to run on system startup.

Reboot the instance.

# Task

I have written an ansible-playbook to run all the tasks.

# Setup

Launch an EC2 instance using AWS configure with the Access and Private key or run the EC2creation.yml with your vpc_subnet_id in which you want to launch the instance.

Using the Public IP of the launched instance add it to the /etc/ansible/hosts file like I have done for ansiblehosts.txt for ssh access.

You would need to change the file location of eval-server.linux-x86_64 and nginx.con in the main.yml as your source.

# Execution

Run the main.yml playbook with all the setup

# Application

The application is running on the public IP 34.204.68.188 and is accessible on port 80.

