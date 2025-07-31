# Gitops-ArgoCD

This repository aims at installing tools like gatekeeper, velero, Istio, kured on a kubernetes cluster using helm charts stored at Git and by using ArgoCD which is installed on the cluster. 

1. Each application folder contains their helm charts. 
2. Folder - argocd-crd contains application.yaml for each application which is a crd of argocd.