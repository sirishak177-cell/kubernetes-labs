# LAB 1 - Pods

## Goal
Created a Kubernetes Pod using YAML.

## Commands Used

kubectl apply -f pod.yaml

kubectl get pods

kubectl describe pod mynginx

kubectl delete pod mynginx

kubectl get pods -w

## What Broke

Deleted the standalone Pod.

No auto-healing because there was no ReplicaSet or Deployment.

## What I Learned

- YAML components:
  - apiVersion
  - kind
  - metadata
  - spec

- Basic kubectl commands

- Difference between Node IP and Pod IP

- Standalone Pods are not used in production
