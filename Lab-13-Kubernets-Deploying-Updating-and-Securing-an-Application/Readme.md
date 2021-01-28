# Deploying, Updating, and Securing an Application with Kubernetes

In the previous chapter, we learned about the basics of the container orchestrator, Kubernetes. We got a high-level overview of the architecture of Kubernetes and learned a lot about the important objects used by Kubernetes to define and manage a containerized application. 

In this chapter, we will learn how to deploy, update, and scale applications into a Kubernetes cluster. We will also explain how zero downtime deployments are achieved to enable disruption-free updates and rollbacks of mission-critical applications. Finally, we will introduce Kubernetes secrets as a means to configure services and protect sensitive data.

# This chapter covers the following topics:

- [Deploying a first application](Deploying-a-first-application.md)
- [Defining liveness and readiness](Defining-liveness-and-readiness.md)
- [Zero downtime deployments](Zero-downtime-deployments.md)
- [Kubernetes secrets](Kubernetes-secrets.md)

# Technical requirements
In this chapter, we're going to use Minikube on our local computer.  Setting Up a Working Environment, for more information on how to install and use Minikube.

```
kubectl config use-context minikube

minikube start
```

The code for this chapter can be found here: cd .\Lab-13-Kubernets-Deploying-Updating-and-Securing-an-Application\sample

In your Terminal, navigate to the **~/Lab-13-Kubernets-Deploying-Updating-and-Securing-an-Application/sample** folder.

# Summary
In this chapter, we have learned how to deploy an application into a Kubernetes cluster and how to set up application-level routing for this application. Furthermore, we have learned how to update application services running in a Kubernetes cluster without causing any downtime. Finally, we used secrets to provide sensitive information to application services running in the cluster.

In the next chapter, we are going to learn about different techniques that are used to monitor an individual service or a whole distributed application running on a Kubernetes cluster.

# Further reading
Here are a few links that provide additional information on the topics that were discussed in this chapter:

Performing a rolling update: https://bit.ly/2o2okEQ
Blue-green deployment: https://bit.ly/2r2IxNJ 
Secrets in Kubernetes: https://bit.ly/2C6hMZF
