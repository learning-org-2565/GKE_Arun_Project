 # GKE project , deploy containerized apps in it:

 If you are getting issues with git push , even after tried with git pull . try 
   ## <git push --force>

 In high level we have to make doc how we are building the manifest file and make it helm before deploy

 ## Step 1: Authenticate and Configure the GCP Project using SDK GCLOUD
 gcloud auth login
 gcloud projects list
 gcloud config set project [PROJECT_ID]
 gcloud config list

## Step 2: Install kubectl
gcloud components install kubectl
kubectl version --client

## Step 3: Connect to Your Kubernetes Cluster
gcloud container clusters get-credentials [CLUSTER_NAME] --region [REGION]
kubectl get pods
<If this works, your kubectl is correctly set up and connected to your cluster.>

gcloud container clusters list  
=================





