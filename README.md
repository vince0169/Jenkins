![Texte
   alternatif](https://upload.wikimedia.org/wikipedia/commons/thumb/e/e3/Jenkins_logo_with_title.svg/1200px-Jenkins_logo_with_title.svg.png)

## This repository contains the projects and exercises that I was able to perform on Jenkins during my training at Eazytraining

## :file_folder: TP2 :file_folder:


This repository is a fork of https://github.com/heroku/alpinehelloworld that i will modify to perform the other exercises.

## :file_folder: TP6 -  deployment   :file_folder:

In this exercise we will create a Jenkins pipeline based on a Jenkinsfile.
In the Jenkinsfile we will find several steps :
- a step to build our imaged based on the Dockerfile
- a step to run container based on the builded image
- So we will test the image with a curl command.
- After we will clean our container, push the image and deploy it in a staging environment and in a production environment on Heroku.

## :file_folder: TP7 -  notifications :file_folder:

Here we will add a part of code in our Jenkinsfile to allow sending notification of pipeline success or failure via slack (slack plugin is required).

## :file_folder: TP8 - shared library :file_folder:

In this lab we will discover the shared librairy.
The aim is to create a shared library to factorize the slack notification step
So you will find the upadated Jenkinsfile based on the shared library (https://github.com/vince0169/shared-library.git)

## :file_folder: Mini-projet :file_folder:

The goal of this mini-project is to set up a complete Jenkins pipeline to deploy a website (https://github.com/diranetafen/static-website-example.git).
It allows to implement all the notions seen in the previous exercises.
Moreover we have to build the Dockerfile.
you will notice that we add a nginx.conf file with our Dockerfile to build our image
