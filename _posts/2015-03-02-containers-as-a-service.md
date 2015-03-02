---
published: true
layout: post
categories: 
  - blog
img: caas_layers.png
author: Bas Tichelaar
thumb: caas_layers_thumb.png
---

With all the hype around Docker, a new layer of cloud computing is being formed. Traditionally, the cloud consists of IaaS, PaaS and SaaS offerings. IaaS is the Infrastructure-as-a-Service layer, which provides an API that is being consumed by the Platform-as-a-Service layer. This PaaS layer is an abstraction layer, that makes it easy for developers to build and deploy their applications. Popular providers are Heroku and EngineYard, but there are also private solutions like Cloud Foundry and Openshift.

But these layers are fundamentally very different. The IaaS layer provides raw building blocks like CPU, memory and storage, that allow you to compose your infrastructure in a free format. On the other hand, PaaS is pretty much locked down and enforces you to build your applications in a certain way. So what if you don't want to care about the underlying infrastructure, but you do want more freedom to build your applications? I think the container layer solves these problems.

![CaaS layers.png](/media/CaaS layers.png)

[Read more on Bas' personal blog](http://tichelaar.io/containers-as-a-service)