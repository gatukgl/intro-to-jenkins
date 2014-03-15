intro-to-jenkins
================

Introduction to Jenkins

Download Vagrant Box at http://files.vagrantup.com/precise32.box

Add a box using

`vagrant box add jenkins http://files.vagrantup.com/precise32.box`

or

`vagrant box add jenkins precise32.box`

if you have already downloaded the box to your local machine.

Installing Jenkins on Ubuntu
============================

`wget -q -O - http://pkg.jenkins-ci.org/debian/jenkins-ci.org.key | sudo apt-key add -`
`sudo sh -c 'echo deb http://pkg.jenkins-ci.org/debian binary/ > /etc/apt/sources.list.d/jenkins.list'`
`sudo apt-get update`
`sudo apt-get install jenkins`

For more inforamtion, read https://wiki.jenkins-ci.org/display/JENKINS/Installing+Jenkins+on+Ubuntu.

Setting Up Jenkins with Github
==============================

1. Install Git Plugin to integrate with Git SCM.
2. Install GitHub Plugin to integrate with GitHub.
3. Install Build Pipeline Plugin.
4. Install Green Balls to use green balls instead of blue for successful builds.
