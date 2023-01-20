Consul Cluster Peering with GKE
================================================================================

This repo contains sample configuration to:

- Deploy two GKE clusters with Consul
- Deploy HashiCups frontend in the first GKE cluster
- Deploy HashiCups backend in the second GKE cluster
- Configure Consul cluster peering between the two clusters
- Export the HashiCups `products-api` service in the second cluster
- Connect the HashiCups frontend and backend via the cluster peering
- Verify peered Consul services
- Destroy environment

Thanks
--------------------------------------------------------------------------------

This repository has borrowed code from the following other repositories. Thank you!

- https://github.com/hashicorp-education/learn-consul-cluster-peering
- https://github.com/vanphan24/cluster-peering-demo
- https://github.com/hashicorp/learn-terraform-provision-aks-cluster
