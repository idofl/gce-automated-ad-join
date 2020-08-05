# Active Directory Automation

This reporistory contains scripts and tools to automate common Active Directory
deployment tasks on Google Cloud.

The repository is organized as follows:

* `ad-network` contains a Terraform module for deploying a VPC that meets all prerequisites
   for an Active Directory deployment.
* `ad-forest` contains a Terraform module for deploying a self-managed Active Directory forest.
* [`ad-joining`](ad-joining/) contains a Cloud Function that enables you to [automatically join VM instances 
  to an Active Directory domain](https://cloud.google.com/solutions/configuring-active-directory-for-vms-to-automatically-join-the-domain).


## License

All files in this repository are under the
[Apache License, Version 2.0](LICENSE.txt) unless noted otherwise.