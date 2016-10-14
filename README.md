# An Ansible playbook to provision a cluster of Raspberry Pis as an Apache Spark cluster.

## Warning!

I'm pretty new to all this right now. I probably haven't done everything right!

## Dependencies:

You'll need to install the ansible galaxy role [azavea.spark](https://galaxy.ansible.com/azavea/spark/),
if you install it into the subdir `roles/` of the directory you run the playbook from, ansible should pick it up.

ie; `ansible-galaxy install azavea.spark -p ./roles/`
