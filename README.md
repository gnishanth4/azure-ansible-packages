# azure-ansible-packages

For RHEL-8 instance

Pre Steps to do

# Update the RHEL Repo
1. yum update

# Install ansible package 
1. yum update
2. sudo dnf install https://dl.fedoraproject.org/pub/epel/epel-release-latest-8.noarch.rpm -y
3. sudo dnf install ansible
4. sudo ansible --version

# Install java in RHEL 8

1. yum install java -y 

# Install git package

1. yum install git -y

# Running the ansible playbooks

Note: Switch to root user
1. sudo su  

# Install instructions 

1. git clone  https://github.com/gnishanth4/azure-ansible-packages.git

2. cd azure-ansible-packages

3. sudo ansible-galaxy install -r requirements.yml

4. sudo ansible-playbook packages.yml
