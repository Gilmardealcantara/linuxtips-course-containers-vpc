# linuxtips-course-containers-vpc


```
export AWS_DEFAULT_PROFILE=linuxtips

terraform init -backend-config=enviromment/dev/backend.tfvars
terraform fmt --recursive
terraform apply --auto-approve -var-file=enviromment/dev/terraform.tfvars

```
