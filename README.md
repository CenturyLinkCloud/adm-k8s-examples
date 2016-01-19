# Kubernetes Sample Applications by CL

This is a collection of sample applications that are packaged so that they run inside a kubernetes cluster. These sample applications are provided as reference material for blog posts and documention that lives on CenturyLink Clouds websites (www.ctl.io). 

## List of applications

These applications can be found in this repo:

Sample Application | Description
----- | -----
nginx-with-git-volume | A simple static web server running nginx that is backed by a gitrepo volume that automatically pulls web content from guthub into the pod. 


## Usage information

For more detail about these applications and how to use them, please check out the README files included in each sub-directory. 

## Requirements

To run these, you will need a kubernetes cluster and have the kubernetes command line client 'kubectl' installed on your client machine. 

## License

The project is licensed under the [Apache License v2.0](http://www.apache.org/licenses/LICENSE-2.0.html).
