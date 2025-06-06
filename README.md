## Infrastructure As Code Tutorial

[![license](https://img.shields.io/github/license/Artemmkin/infrastructure-as-code-tutorial.svg)](https://github.com/Artemmkin/infrastructure-as-code-tutorial/blob/master/LICENSE)
[![Tweet](https://img.shields.io/twitter/url/http/shields.io.svg?style=social)](https://twitter.com/intent/tweet?text=Learn%20about%20Infrastructure%20as%20Code%20https%3A%2F%2Fgithub.com%2FArtemmkin%2Finfrastructure-as-code-tutorial%20%20Tutorial%20created%20by%20@artemmkins%20covers%20%23Packer,%20%23Terraform,%20%23Ansible,%20%23Vagrant,%20%23Docker,%20and%20%23Kubernetes.%20%23DevOps)

This tutorial is intended to show what the **Infrastructure as Code** (**IaC**) is, why we need it, and how it can help you manage your infrastructure more efficiently.

It is practice-based, meaning I don't give much theory on what Infrastructure as Code is in the beginning of the tutorial, but instead let you feel it through the practice first. At the end of the tutorial, I summarize some of the key points about Infrastructure as Code based on what you learn through the labs.

This tutorial is not meant to give a complete guide on how to use a specific tool like Ansible or Terraform, instead it focuses on how these tools work in general and what problems they solve.

> The tutorial was inspired by [Kubernetes the Hard Way](https://github.com/kelseyhightower/kubernetes-the-hard-way) tutorial. I used it as an example to structure this one.

_See [my presentation at DevOpsDays Silicon Valley](https://www.youtube.com/watch?v=XbcW2B7roLo&t=) in which I talk more in depth about the tutorial._

## Need your help!

This tutorial was created in 2018 and wasn't being kept up to date. Therefore, some of the instructions may not work due to updated APIs, obsolete repositories, etc. I apologize for that, but I currently don't have time to update this tutorial. So if you find that something is broken and you find a fix, please submit a PR. 

When submitting a PR, make sure you include a description for it, i.e. what's broken and a test plan for the fix.

Also, note that some of things need to be updated in several different repositories at the same time. Main repositories used in this tutorial:

* https://github.com/Artemmkin/infrastructure-as-code-tutorial
* https://github.com/Artemmkin/infrastructure-as-code-example
* https://github.com/Artemmkin/raddit

## Target Audience

The target audience for this tutorial is anyone who loves or/and works in IT.

## Tools Covered

* Packer
* Terraform
* Ansible
* Vagrant
* Docker
* Docker Compose
* Kubernetes

## Results of completing the tutorial

By the end of this tutorial, you'll make your own repository looking like [this one](https://github.com/Artemmkin/infrastructure-as-code-example).

NOTE: you can use this [example repository](https://github.com/Artemmkin/infrastructure-as-code-example) in case you get stuck in some of the labs.

## Labs

This tutorial assumes you have access to the Google Cloud Platform. While GCP is used for basic infrastructure requirements the lessons learned in this tutorial can be applied to other platforms.

* [Introduction](docs/00-introduction.md)
* [Prerequisites](docs/01-prerequisites.md)
* [Manual Operations](docs/02-manual-operations.md)
* [Scripts](docs/03-scripts.md)
* [Packer](docs/04-packer.md)
* [Terraform](docs/05-terraform.md)
* [Ansible](docs/06-ansible.md)
* [Vagrant](docs/07-vagrant.md)
* [Docker](docs/08-docker.md)
* [Docker Compose](docs/09-docker-compose.md)
* [Kubernetes](docs/10-kubernetes.md)
* [What is Infrastructure as Code?](docs/50-what-is-iac.md)
