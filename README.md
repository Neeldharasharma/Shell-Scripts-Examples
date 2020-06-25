# Shell-Scripts-Examples

!#/bin/bash

#Check to see if Python is already installed
python --version

#install python
sudo yum install python3

#verify that Python installed correctly
python3 --version

# Run pip --version to see if your version of Linux already includes Python and pip
pip --version
cd /tmp

#Download the installation script from pypa.io:
curl -O https://bootstrap.pypa.io/get-pip.py

#Run the script with Python
python get-pip.py --user

#Add an export command to your profile script
export PATH=~/.local/bin:$PATH

#Load the profile into your current session
source ~/.bash_profile

#Verify that pip is installed correctly
pip --version

#Use pip to install the AWS CLI
pip install awscli --upgrade --user

#Verify that the AWS CLI installed correctly
aws --version

#To upgrade to the latest version, run the installation command again
pip install awscli --upgrade --user

#Configure region
aws configure

#Install boto3
pip install boto3 --user
AWS configure will create 2 files 
config
credentials
in the .aws folder
