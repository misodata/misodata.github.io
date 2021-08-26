---
permalink: /learn-more/
title: "Learn More"
excerpt: "What is misodata.io?"
toc: true
---

## What is misodata.io?

Misodata.io let's data engineers and data scientist focus on building solutions, without worrying how to version, deploy and monitor their data workloads.
It leverages your own cloud environment and deploys your software on an auto-scalable kubernetes cluster.

## How does it work?

Using our UI or API point us to your cloud environment and code base and we will dockerize your workloads and make them runnable by using our API or UI interface.
Using your configuration we'll use as little and as cheap resources to run the jobs efficiently and cost effective.
Advanced monitoring will allow you to inspect the workloads as they run and after they have completed.
You can also hook us into your existing monitoring solutions.

## What technology do you support?

At the moment we focus mainly on running Apache Spark (2.4+, 3+) jobs on Kubernetes.
We deploy and manage the Kuberenetes cluster for you in your cloud.

Currently we only support AWS, but Azure & GCP are coming soon.

We are also developing interfaces for other tools workloads, like: dbt, Apache Flink, Jupyter Notebooks.
And also intergration with Kubeflow.

## Do I need to change my code?

You can either just push your docker image to the registry we setup (or that you provide for us) and point us in that direction, but for best results we advise you to use one of our templates. The template will only provide some CI/CD and kubernetes intergration config. You can still write your code the way you normally do. We're here just to help you with deploying and monitoring your workloads :-)

## What does it cost?

At the moment we are reviewing our pricing strategy, but it will be a fraction of the money you will save by running finely tuned workloads.

## What if I want to leave?

Just disable your account and you won't be billed anymore. Your code and binaries will still be yours in your cluster. You just have to run and monitor the jobs yourselves now.

## Notable Features

- Auto-scalable workloads on Kubernetes
- Spark as a Service
- Bring your own cloud
- Advance insights & monitoring
- Versatile API for integration & triggers
- High cost saving
- Low investment
- Easy to use
- No hidden dependencies
