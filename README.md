# DeepCluster-API
Provision of declarative API for clyster creation, configuration and management 

This is a simple example of how we can use Cluster API to provision multiple edge clusters from a central management cluster. It uses Cluster API CRD specifically created to do cluster creation, configuration and management to build edge nodes. 
This is extended into multi cluster application manager CRD that enables the user to deliver applications and services across the clusters from a single pane of glass. 
![image](https://github.com/Deepankar0303/DeepCluster-API/assets/79351928/1190eac2-109c-43cf-97a4-fbf5c85fd582)

The cluster API CRDs can be integerated with any bootstrap providers like kubeadm for kubernetes clusters, k3s for lightweight clusters, even extending to OpenShift clusters. 
It also works with all leading infrastructure providers like AWS, Google Cloud, VMware, MAAS etc. 
![image](https://github.com/Deepankar0303/DeepCluster-API/assets/79351928/3132f8f8-67ff-42e2-b121-bfff05a05d42)
![image](https://github.com/Deepankar0303/DeepCluster-API/assets/79351928/0eca8339-08e6-499d-affb-9a5757a30362)
Tested Scenarios:

<img width="722" alt="image" src="https://github.com/Deepankar0303/DeepCluster-API/assets/79351928/02a07c30-20cc-4e8d-830d-5e84266aafeb">



