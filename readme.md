#  Terraform


> Documentation Reference

https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/instance


## Some Basic Commands:

> Initialize the terraform and download the plugins for the providers

```shell
    terraform init
```

> This command just dry run the checks before actually proceding the actual steps.
```shell
terraform plan
```

> Run the plan
```shell
terraform apply
```
 
```shell
terraform apply --auto-approve
```

> Destroying / Removing the resources

```shell
terraform destroy
```

> See the list of states of resources
```shell
terraform state list
```
> To check the particular resource state 
```shell
terraform state show <resource-name>
```




