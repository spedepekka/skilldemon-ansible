# skilldemon-ansible

Ansible playbooks for skilldemon

# AWS authentication

Remember to set AWS credentials with [boto][boto].

[boto]: http://boto.cloudhackers.com/en/latest/getting_started.html

# Run

## Playbooks

* site.yml - Set EC2 instance
* install-tomcat.yml - Install Tomcat

## Test

Setup a test box to 192.168.33.10 (I use Vagrant) and use inventory `test`

## AWS/EC2

Use `ec2` inventory

