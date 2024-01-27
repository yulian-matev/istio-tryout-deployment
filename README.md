# istio-tryout-deployment
This repo acts as an 'Application deployment repo' for [istio-tryout](https://github.com/yulian-matev/istio-tryout)  project


## Workflow

1. `istio-tryout` pipeline generate _deployment_ files that are stored inside this repo
  
    * `deployment.yml`
    * `service.yml`
    
2. ArgoCD monitors changes inside this repo and performs deployment accordingly.
