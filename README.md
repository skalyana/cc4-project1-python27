OpenShift Python project for Cloud Computing Exercise #4

# Introduction

This is a hello world Python project that deploys on RedHat's
OpenShift Developer Preview


# Steps

1. Register with Github at https://api.preview.openshift.com/

2. Get a token to log in: https://api.preview.openshift.com/oauth/token/request

3. Install oc: https://console.preview.openshift.com/console/command-line

4. Try the Console: https://console.preview.openshift.com/console/

5. Create a new Project

6. Add a Python2.7 component

   1. Make a github repo for your component with these files: 
	  * [app.py](app.py) - must start a service that listens on port 8080 forever
	  * [requirements.txt](requirements.txt) - extra python dependencies
	  
   2. Add new Python2.7 component in the OpenShift dashboard with your
      github repo's url
	  
   3. Add OpenShift's webhook url to your github repo
   
   4. push more changes to your repo, OpenShift will rebuild it

   
