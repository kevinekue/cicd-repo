# cicd-v0.0

This latest version/commit is an attempt at providing a cleaner folder structure/documentation of the work pertaining to this repository.
It's mainly been used in order to test and experiment with the creation and deletion of CICD pipelines. The main tools  used so far have been CircleCI for the Sontinuous Integration part, and Ansible for the Continuous Deployment.

A successful pipeline, using this specific set up will allow us to automatically: 
    - Configure a manually created AWS EC2 instance
    - Copy on said instance web site information
    - start and provision a web service (apache in the present case)
    - Start a web service 

Once the pipeline successfully created, the user should be able to access the webpage from their browser using the EC2 instance's public address, with port at port 3000.