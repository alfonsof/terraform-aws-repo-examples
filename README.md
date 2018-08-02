# Terraform Web Server Cluster module in a repo example

This folder contains a Web Server Cluster module in a repo example of a [Terraform](https://www.terraform.io/) file.

This Terraform file define a cluster of web servers module in Amazon Web Services (AWS) using EC2 and Auto Scaling, and a load balancer using ELB.

The cluster of web servers returns "Hello, World" for the URL `/`. The load balancer listens on port 80.

## Requirements

* You must have [Terraform](https://www.terraform.io/) installed on your computer.
* You must have an [Amazon Web Services (AWS) account](http://aws.amazon.com/).

This code was written for Terraform 0.10.x.

## Using the code

Terraform modules are not meant to be deployed directly. Instead, you should be using them from other templates. Furthermore, this module is in a repo in order to be used by Terraform files from other repos.

See:

[https://github.com/alfonsof/terraform-examples-aws/tree/master/code/10-multi-repo-example](https://github.com/alfonsof/terraform-examples-aws/tree/master/code/10-multi-repo-example)

where this module is used by:

* Terraform Web Server Cluster example (staging environment)
* Terraform Web Server Cluster example (production environment)

These can be use different versions of this module.
