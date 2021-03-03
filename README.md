* Create an IAM user with programatic access and preferably admin access to manage EKS.
* Create a policy for EKS to manage EC2 on your behalf.
* When a cluster is created using eksctl, aws user running the creation will be added to kubeconfig file with admin previllages.
* Nodegroups are immutable in nature, any changes other than scaling requires deletion.

// Cluser autoscaler //