# Kubernetes CronJob Example

The repository contains a simple example of a Kubernetes CronJob.

## Usage

```shell
$ minikube start
$ minikube docker-env
$ eval $(minikube -p minikube docker-env)
$ docker build -t simplejob .
$ kubectl apply -f job.yaml
```