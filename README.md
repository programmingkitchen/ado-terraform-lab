# DEPLOY INFRASTRUCTURE WITH ADO & TERRAFORM

# Overview
Deploy Azure infrastructure using ADO and Terraform. 

- Source is in Git. 

```
$ git remote -v
origin  git@github.com:programmingkitchen/ado-terraform-lab.git (fetch)
origin  git@github.com:programmingkitchen/ado-terraform-lab.git (push)
```

## Architecture


## Revision History

| VER  | DETAILS                                                     |
| -----|------------------------------------------------------------ |
| v0.0 | Start                                                       |
| v0.1 | Testing manually complete                                   |
| v0.2 | TBD                                                         |


## Basics
- Use modules to create:
  1. A RG
  2. Network
  3. NSG
  4. Public IP
  5. Load Balancer
  5. Linux VM (Standard_B1s)


## Misc
- State sorted in a Storage Account
- Credentials from the Storage account and a Service Principal (with secret)

# TODO
- Change the Resource Group for the Storage Account (for state) to be somthing other than the RG 
named UdacityProject3.1

# Notes/Issues


# Procedure


