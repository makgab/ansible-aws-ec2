## Deploying AWS Linux szervers with Ansible
------------------------------------------------------------------------------

- Requires Ansible 1.x
- Expects CentOS/RHEL/Fedora hosts


### Linux servers
---------------------------------------------

![Alt text](images/aws.png "AWS")

AWS Linux servers with ansible management.
Many distribution are available in AWS.
RedHat, CentOS, Fedora, Debian, Ubuntu ...etc.


### Ansible
------------------------------------

![Alt text](images/ansible.png "AWS")

What is ansible?
No matter your role, or what your automation goals are, Ansible can help you demonstrate value, connect teams,
and deliver efficiencies for your organization. Built on open source, Red Hat® Ansible® Automation Platform is a hardened,
tested subscription product that offers full life cycle support for organizations.
Explore how Ansible can help you automate today—and scale for the future.

How Ansible works?
Ansible® is an open source, command-line IT automation software application written in Python.
It can configure systems, deploy software, and orchestrate advanced workflows to support application deployment, system updates, and more.

Both community Ansible and Ansible Automation Platform are built on the concept of a control node and a managed node.
Ansible is executed from the control node—for example, where a user runs the ansible-playbook command.
Managed nodes are the devices being automated—for example, a Microsoft Windows server.

For automating Linux and Windows, Ansible connects to managed nodes and pushes out small programs—called Ansible modules—to them.
These programs are written to be resource models of the desired state of the system.
Ansible then executes these modules (over SSH by default), and removes them when finished.
These modules are designed to be idempotent when possible, so that they only make changes to a system when necessary.

(source: ansible.com)


### Using
---------

- Link: https://medium.com/@a_tsai5/creating-an-ec2-instance-using-ansible-764cf70015f6

- Create Access Key/Secret Key in AWS Console.

- Install package awscli2: ~# dnf install awscli2

- Run configuration (settings stored ~/.aws/): ~# aws configure

- Run playbook: ~# play.sh

