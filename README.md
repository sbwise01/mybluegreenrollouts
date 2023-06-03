# mybluegreenrollouts
A demo of using Argo rollouts to perform blue green deployments on micro services

Deployment order
1.  Terraform apply tf sub-directory
2.  kubectl apply all resources in k8s sub-directory
3.  Terraform apply tf/post_istio sub-directory
