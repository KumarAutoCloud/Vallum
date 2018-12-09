1.       Create a hosted git repository account of your choice (if you do not already possess one) e.g. github, gitlab, bitbucket, etc.

2.       Provide us with the account name

3.       Create a public repository for this assessment and provide the name once complete

4.       Use the repository for the configuration and code that will:

a.       Spin up a Linux Vagrant box of your choice

b.       Configure Vagrant to use Ansible as the provisioner

c.       Configure the box with an IP address available to the hosting OS

d.       Write playbook/playbooks to:

                                                           i.      Install and start docker

                                                           ii.      Build a docker container based on the official Alpine Linux container (library/alpine:latest)

                                                           iii.      Build the container so that nginx is installed and started

                                                           iv.      Configure nginx to serve out some static “Hello World” content

                                                           v.      Start the container as a micro service

e.       At the end of the provisioning the URL to the web page should be available from the hosting OS

f.        Write appropriate documentation in the repository to explain how someone cloning it should provision the Vagrant VM and access the web URL serving out the “Hello World”

Prerequisites - The setup was test on the version listed below

Install vagrant version 2.2.2
Install VirtualBox version 5.2.22

Git repository:


