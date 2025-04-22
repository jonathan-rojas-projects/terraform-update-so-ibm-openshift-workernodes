# terraform-update-so-ibm-openshift-workernodes
This project uses Terraform to automate OS upgrades of worker nodes in IBM Cloud OpenShift clusters, migrating from RHEL to RHCOS. It provisions a new worker pool, gradually replaces old nodes, and ensures a smooth transition with zero downtime.
