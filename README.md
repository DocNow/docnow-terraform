# docnow-terraform
Builds docnow's application on different cloud providers

## Status of this Repo

### Components

- [ ] Create Scaleway
- [ ] Create Vultr
- [ ] Create DigitalOcean
- [ ] Create Cloud Scale
- [ ] Create Google Cloud

### Critical Clean up and review

- [ ] test with ansible
- [ ] test on Windows

## Quick introduction to Terraform

Terraform is a tool that lets you provision, change and version the infrastructure that will host your docnow application. That infrastructure will be virtual machines, IP/DNS records that will then be used to configure your [docnow application](https://github.com/DocNow/docnow). Terraform works with many infrastructure providers through a system of plugins. This repo will contain different cloud providers that you can run your docnow application on. 

### Install Terraform

Hashicorp provides [binaries to
install](https://www.terraform.io/downloads.html) for most platforms. The DocNow
team will always test with the latest version of Terraform and their providers.

### Cloud Providers

* [Scaleway](scaleway)
