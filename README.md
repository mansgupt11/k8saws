This is sample terraform code for creating k8s cluster in AWS

cd aws-k8s-cluster
terraform init
terraform plan
terraform apply 

In eks-cluster.tf file, you can change the value desired value of node how many you wants to come up at once.
Right now value is 1 , but it can be changed.
