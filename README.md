Introduction to Jenkins
=======================

Firstly, download a Vagrant Box at http://files.vagrantup.com/precise32.box (or precise64.box)

Then add a box by running the command below

`vagrant box add jenkins http://files.vagrantup.com/precise32.box`

or if you have already downloaded the box to your local machine, run

`vagrant box add jenkins precise32.box`

Finally, run `vagrant up` to start the virtual machine.


Installing Jenkins on Ubuntu
============================

Run the following commands:

1. `wget -q -O - http://pkg.jenkins-ci.org/debian/jenkins-ci.org.key | sudo apt-key add -`
2. `sudo sh -c 'echo deb http://pkg.jenkins-ci.org/debian binary/ > /etc/apt/sources.list.d/jenkins.list'`
3. `sudo apt-get update`
4. `sudo apt-get install jenkins`

For more inforamtion, read https://wiki.jenkins-ci.org/display/JENKINS/Installing+Jenkins+on+Ubuntu.

Setting Up Jenkins with Github
==============================

1. Install Git Plugin to integrate with Git SCM.
2. Install GitHub Plugin to integrate with GitHub.
3. Install Build Pipeline Plugin.
4. Install Green Balls to use green balls instead of blue for successful builds.
