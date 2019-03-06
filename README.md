# README #

### What is this repository for? ###

* This repo contains code to set up and launch compliance analysis in the cloud.
* This code operates on the output of the program VC_DoAnalysis. Please, do that first.

### What is the status of this code? ###

* This is beta code for testing only.
* It does run on a limited number of data sets, but needs wider testing prior to release to users.

### How do I install the code? ###

* This code was tested only on Linux platforms.
* Copy the contents of the bin directory into your bin directory and make them executable.
* Make a directory called "descriptors" in your bin directory
* Copy the contents of this repos descriptor directory into the ~/bin/descriptors directory.
* This code operates on data as calculated by the vcprod code (ex. ~/data/pathtodata/sub1)
* For a list or required files see "VC_requiredFiles.txt" in the bin dir.
* You will need to provide your user name on the remote processing server (ex. username) 
* Launch the code using VC_cloudRun username ~/data/pathtodata/sub1

### Who is the contact for this code? ###

Contact: Robert Bussell, rbussell@ucsd.edu
