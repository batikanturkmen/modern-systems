## Useful resources for infrastructure and modern web development.

## Apache

- **[Kafka](https://kafka.apache.org/):** 
 Distributed streaming platform.
 
- **[Avro](https://avro.apache.org/):** 
 Data serialization system.
  
- **[Camel](https://camel.apache.org/):** 
 Message-oriented middleware with a rule-based routing and mediation engine.

> Apache Camel is based on [Enterprise Integration Patterns](https://www.enterpriseintegrationpatterns.com/patterns/messaging/)

- **[Airflow](https://airflow.apache.org/):** 
 Programmatically author, schedule and monitor workflows.
 
> Apache Airflow can be used kubernetes pod deployment and testing with a single command.

## Logging, Tracing & Metrics

- **[ELK](https://www.elastic.co/what-is/elk-stack):** 
Elasticsearch, Logstash, and Kibana. Data search, transform and visualization stack.

> 🔄 Fluentd is a good substitution of Logstash

- **[Jaeger](https://www.jaegertracing.io/):** 
End-to-end distributed tracing

- **[Opentelemetry](https://opentelemetry.io/):** 
Services to capture distributed traces and metrics from your application.

- **[Prometheus](https://prometheus.io/) / [Grafana](https://grafana.com/):**
Time series based monitoring solutions.

## Docker & Kubernetes

- **[Helm](https://helm.sh/):** The package manager for Kubernetes.

- **[Rancher](https://rancher.com/):** Centralized Kubernetes management solution.

- **[Harbor](https://goharbor.io/):** CNCF's Container Registry solution.

- **[skaffold](https://github.com/GoogleContainerTools/skaffold/):** Easy and Repeatable Kubernetes Development 

- **[kubectx](https://github.com/ahmetb/kubectx/):** Faster way to switch between clusters and namespaces in kubectl.

#### Service Mesh

- **[Istio](https://istio.io/):** Service mesh solution that lets you connect, monitor, and secure microservices.

#### Kubernetes Config Management

- **[Kustomize](https://github.com/kubernetes-sigs/kustomize):**
customize raw, template-free YAML files for multiple purposes, leaving the original YAML untouched and usable as is.

- **[flux](https://fluxcd.io/):** GitOps operator for Kubernetes

#### Kubernetes Operators

- **[Confluent Operator](https://www.confluent.io/confluent-operator/):** Confluent Operator simplifies running Confluent Platform as a cloud-native system on Kubernetes, on-premises or in the cloud.

> 💡 Recommended if you're planning to use Apache Kafka on Kubernetes

## Go

- **[Inject build-time variables](https://blog.alexellis.io/inject-build-time-vars-golang/):**
 Blog post about how to inject variables into your Golang executable at build-time. 

- **[pprof](https://golang.org/pkg/net/http/pprof/):**
Package pprof serves via its HTTP server runtime profiling data in the format expected by the pprof visualization tool.

- **[Concurrency in Go](https://www.youtube.com/watch?v=LvgVSSpwND8):**
An introduction to Concurrency in Go.

- **[Concurrency Patterns In Go](https://www.youtube.com/watch?v=YEKjSzIwAdA):**
Overview of common concurrency patterns and ends with best practices on lockless programming in Go.

- **[Go module proxy](https://arslan.io/2019/08/02/why-you-should-use-a-go-module-proxy/):**
Why you should use a Go module proxy.

## Java

- **[Lambdas and Streams](https://www.youtube.com/watch?v=1OpAgZvYXLQ):** 
 Venkat Subramaniam's Session about lambdas and streams in Devoxx for beginners.

- **[Quarkus Microservice Workshop](https://quarkus.io/quarkus-workshops/super-heroes/):**
  Microservice example using Quarkus and GraalVM.
  
- **[Garbage Collection](https://www.oracle.com/webfolder/technetwork/tutorials/obe/java/gc01/index.html):**
  Java Garbage Collection Basics
  
- **[OSGi](https://www.osgi.org/):** The Dynamic Module System for Java

- **[OSGi Modularity Tutorial](https://www.vogella.com/tutorials/OSGi/article.html):** This tutorial gives an overview of OSGi and its modularity layer using Eclipse Equinox.

- **[BND Tools](https://bndtools.org/):** Tooling to build OSGi bundles.

- **[Mockito](https://github.com/mockito/mockito):** 
Mocking framework for unit tests in Java

- **[Guice](https://github.com/google/guice):** 
 Lightweight dependency injection framework for Java.
 
- **[Vert.x](https://vertx.io/):** 
 Tool-kit for building reactive applications on the JVM.

## Website
- **[12 Factor Methodology](https://www.12factor.net/):**
The Twelve-Factor App methodology is explaining 12 best practices that are designed to enable applications to be built with portability and resilience.

- **[Martin Fowler](https://martinfowler.com/):**
Martin Fowler's blog about microservices and software architecture.

- **[High Scalability](http://highscalability.com/):**
Building bigger, faster and more reliable websites.

## Other

- **[Microservices Demo](https://github.com/GoogleCloudPlatform/microservices-demo):** 
Sample cloud-native application with 10 microservices showcasing Kubernetes, Istio, gRPC and OpenCensus.

- **[gRPC](https://grpc.io/):** 
A high-performance RPC framework.

- **[Google Cloud Code](https://cloud.google.com/code):**
provides IDE support for the full development cycle of Kubernetes applications.

- **[Google SRE Books](https://landing.google.com/sre/books/):**
Google's Site Reliability Engineering related books.

- **[Google's Monolithic Repository Paper](https://research.google/pubs/pub45424/):**
Explaining Why and How Google stores billions of lines of code in a single repository.

- **[Ahmet Alp Balkan's Channel](https://www.youtube.com/channel/UC6LgxY4YwVoE1F-v8sT9Jaw):** 
Ahmet is working at Google Cloud and explaining modern infrastructure and cloud-native technologies in his channel.

- **[Hashicorp Vault](https://www.vaultproject.io/):**
Tool for managing secrets and protecting sensitive data.

- **[Hashicorp Terraform](https://www.terraform.io/):**
Infrastructure as Code solution to provision and manage any cloud, infrastructure, or service.

- **[Semantic Versioning](https://semver.org/):**
Simple set of rules and requirements that dictate how version numbers are assigned and incremented.

- **[Configuration Management Database](https://en.wikipedia.org/wiki/Configuration_management_database):**
CMDBs are used to keep track of the state of assets such as products, systems, software, facilities, people as they exist at specific points in time, and the relationship between all assets.