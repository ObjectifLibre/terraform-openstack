# terraform-openstack
deploy with terraform a instance in Openstack

Installation of Terraform
==========================

Download the package from the hashicorp website

```
curl -O https://releases.hashicorp.com/terraform/0.12.19/terraform_0.12.19_linux_amd64.zip > /tmp/terraform_0.12.19_linux_amd64.zip
sudo unzip /tmp/terraform_0.12.19_linux_amd64.zip -d /usr/local/bin/
rm /tmp/terraform_0.12.19_linux_amd64.zip

terraform --version
```

How to use
==========

```
git clone https://github.com/ObjectifLibre/terraform-openstack.git
cd terraform-openstack
terraform init 
terraform apply
```
