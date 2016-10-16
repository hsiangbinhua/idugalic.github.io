---
layout: post
title: Accelerating the digitization with microservices
---


For some executives, it’s about technology. For others, digital is a new way of engaging with customers.

It’s tempting to look for simple definitions, but to be meaningful and sustainable, we believe that digital should be seen less as a thing and more a way of doing things. To help make this definition more concrete, we’ve broken it down into three attributes: creating value at the new frontiers of the business world, creating value in the processes that execute a vision of customer experiences, and building foundational capabilities that support the entire structure.

Strategic application architects need to establish consistent, holistic approaches that enable the flexibility, scalability and versatility that digital business requires.

## The trio

To accomplish this we choose the trio of microservices, DevOps, and continuous delivery.

Microservices is the architecture,
DevOps—specifically CALMS (collaboration, automation, learning, measuring, and sharing)—is the culture,
and continuous delivery is the process.
All three aspects are required to achieve consistent throughput, with low risk in your software-delivery process.

### Microservices

The microservice architectural style is an approach to developing a single application as a suite of small services, each running in its own process and communicating with lightweight mechanisms, often an HTTP resource API (RESTful). These services are built around business capabilities and independently deployable by fully automated deployment machinery. There is a bare minimum of centralized management of these services, which may be written in different programming languages and use different data storage technologies.

When organizations make the choice to put a digital platform in place, a discussion on Microservices is never far behind. By putting a Microservices layer in place, an organization creates the springboard to launch into the digital future, whether that involves apps, rich Web clients, or IoT devices such as in-store beacons. Individual Microservices, or orchestrated groups of Microservices, serve as the foundation for this innovation. The data being passed to and from Microservices also serves as the basis for behavioral analytics and Big Data, allowing organizations to tailor their digital services based on their users.

A Microservices architecture style brings a lot of operations overhead. Where a monolithic application might have been deployed to a small application server cluster, you now have tens of separate services to build, test, deploy and run, potentially in polyglot languages and environments.

#### Cloud

If you look at the concerns typically expressed about microservices, you will find that they are exactly the challenges that a PaaS (Platform As A Service) is intended to address.

PaaS offerings like Cloud Foundry have raised the level of abstraction to a focus on an ecosystem of applications and services. Cloud Foundry is open source and it can be deployed on private or public (IaaS) infrastructure.

Linux container technology, such as Docker, can be used to streamline the development, testing and deployment experience. The Docker platform empowers you to build a CaaS (Containers as a service) that fits your business requirements.

#### Cloud native

A cloud-native application is an application that has been designed and implemented to run on a PaaS or CaaS installation, and to embrace horizontal elastic scaling.

### Collaboration, automation, learning, measuring, and sharing

However, with the uptake of microservices and containers new challenges are rising: “How can we manage aspects such as API contracts?” and “How can we apply changes across several repositories at once?”. Those challenges highlight the need for greater collaboration between, and within, teams and this is a challenge that [Atomist](https://www.atomist.com) is addressing. Atomist is setting out to tackle with a set of tools that integrate seamlessly with the teams’ practices.

With the rise of microservices, project creation is more and more important to individuals and organizations, as is maintaining consistency between a potentially large number of services.

### Continous Devlivery

The idea of automated deployment is important. Indeed, if you take automating the deployment process to its logical conclusion, you could push every build that passes the necessary automated tests into production. The practice of automatically deploying every successful build directly into production is generally known as Continuous Deployment.

However, a pure Continuous Deployment approach is not always appropriate for everyone. For example, many users would not appreciate new versions falling into their laps several times a week, and prefer a more predictable (and transparent) release cycle. Commercial and marketing considerations might also play a role in when a new release should actually be deployed. The notion of Continuous Delivery is a slight variation on the idea of Continuous Deployment that takes into account these considerations.

[Spinnaker](http://www.spinnaker.io/) is an open source, multi-cloud continuous delivery platform for releasing software changes with high velocity and confidence.

[Jenkins 2](https://jenkins.io/2.0/) pipelines are pretty neat to. We don't think Spinnaker will every fully replace Jenkins and the million things it does. Spinnaker goal is to just make the 'deploy to cloud' step simpler and more extensible.

## References

  * <http://www.mckinsey.com/industries/high-tech/our-insights/what-digital-really-means>
  * <http://microservices.io/>
  * <https://www.oreilly.com/ideas/achieving-cloud-native-operability-with-microservices-devops-and-continuous-delivery>
  * <http://www.martinfowler.com/articles/microservices.html>
