# azure-ansible-packages

For RHEL-8 instance

Pre Steps to do

# Update the RHEL Repo
1. yum update

# Install ansible package 
1. sudo dnf -y install python3-pip
2. pip3 install ansible --user
3. ansible --version

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
