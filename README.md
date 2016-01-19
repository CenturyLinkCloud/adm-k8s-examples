# adm-k8s-examples

This is a collection of sample applications that are packaged to run inside a kubernetes cluster. To run these, you will need a kubernetes cluster and  the kubernetes command line client 'kubectl' installed on your client machine. 

These sample applications are provided as reference material for blog posts and documention that lives on www.ctl.io. 

## List of applications

Sample Application | Description
----- | -----
nginx-with-git-volume | A simple static web server running nginx that is backed by a gitrepo volume that automatically pulls web content from guthub into the pod. 


## Usage information

For more detail about these applications and how to use them, please check out the README files included in each sub-directory. 


## License

The project is licensed under the [Apache License v2.0](http://www.apache.org/licenses/LICENSE-2.0.html).
