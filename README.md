# Important
> This repo is for my own personal development and learning. *I DO NOT TAKE ANY RESPONSIBILITY* for any server/cloud provider charges you incur as a result of using this code.

## Requirements
What is actually required depends on what you want to run.

#### Mandatory
1. Terraform installed, duh.

#### Docker (optional)
1. docker desktop/engine or Orbstack installed

#### AWS (optional)
1. AWS CLI installed
1. Valid AWS CLI credentials/profile(aws_access_key_id and aws_secret_access_key)

## How to run (not that you'd want to!)
1. `cd` into one of the top-level dirs, i.e. `cd docker`
1. run `terraform plan` to check
1. run `terraform apply` to run

### How to teardown
1. run `terraform destroy`
