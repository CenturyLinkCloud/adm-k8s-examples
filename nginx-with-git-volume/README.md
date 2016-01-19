# nginx-git-k8

This is a simple static web server running nginx that is backed by a gitrepo volume that automatically pulls web content from guthub into the pod. This sample application is meant to highlight two kubernetes features:

* Rolling updates:  The main benefit of rolling updates is that it allows kubernetes users to update some aspect of their application without any downtime to the user. Using rolling updates, the kubernetes user simply declares what they want to change and Kubernetes handles the rest. The rolling update feature also provides a roll back feature making it easy to roll back changes that didn’t go as planned. 

* Github Volumes: Kubernetes allows for users to automatically pull content from a github repo into a directory accessible to a container on container startup. This allows users to create reusable containers with a server process (like a web server) into a container image but leaving the application specific content (like static html files or server side code) outside of the container image. 

## Detailed walkthrough

To read more about this application, rolling updates and the github volume type please see read the blog post posted here: 

## Simple installation instructions

If you don't want to read the above post, you can install this application with the following kubectl commands. 


kubectl create -f ./replication-controller-static-website-v1.yml
kubectl create -f ./service-lb.yml





