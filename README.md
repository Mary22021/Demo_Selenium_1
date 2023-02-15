# Kubernetes & OpenShift Java Client [![Join the chat at https://gitter.im/fabric8io/kubernetes-client](https://badges.gitter.im/fabric8io/kubernetes-client.svg)](https://gitter.im/fabric8io/kubernetes-client?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)
This client provides access to the full [Kubernetes](http://kubernetes.io/) &
[OpenShift](http://openshift.org/) REST APIs via a fluent DSL.

[![Build](https://github.com/fabric8io/kubernetes-client/workflows/Build/badge.svg)](https://github.com/fabric8io/kubernetes-client/actions?query=workflow%3ABuild)
[![Sonar Scanner](https://github.com/fabric8io/kubernetes-client/workflows/Sonar%20Scanner/badge.svg)](https://github.com/fabric8io/kubernetes-client/actions?query=workflow%3A%22Sonar+Scanner%22)
[![Bugs](https://sonarcloud.io/api/project_badges/measure?project=fabric8io_kubernetes-client&metric=bugs)](https://sonarcloud.io/dashboard?id=fabric8io_kubernetes-client)
[![E2E Tests](https://github.com/fabric8io/kubernetes-client/workflows/E2E%20Tests/badge.svg)](https://github.com/fabric8io/kubernetes-client/actions?query=workflow%3A%22E2E+Tests%22)
[![Release](https://img.shields.io/github/v/release/fabric8io/kubernetes-client)](https://search.maven.org/search?q=g:io.fabric8%20a:kubernetes-client)
[![Twitter](https://img.shields.io/twitter/follow/fabric8io?style=social)](https://twitter.com/fabric8io)

| Module | Maven Central | Javadoc |
|-|:-:|:-:|
| kubernetes-client | [![Maven Central](https://maven-badges.herokuapp.com/maven-central/io.fabric8/kubernetes-client/badge.svg?color=blue)](https://maven-badges.herokuapp.com/maven-central/io.fabric8/kubernetes-client) | [![Javadocs](https://www.javadoc.io/badge/io.fabric8/kubernetes-client.svg?color=blue)](https://www.javadoc.io/doc/io.fabric8/kubernetes-client) |
| openshift-client | [![Maven Central](https://maven-badges.herokuapp.com/maven-central/io.fabric8/openshift-client/badge.svg?color=blue)](https://maven-badges.herokuapp.com/maven-central/io.fabric8/openshift-client) | [![Javadocs](https://www.javadoc.io/badge/io.fabric8/openshift-client.svg?color=blue)](https://www.javadoc.io/doc/io.fabric8/openshift-client) |

| Extensions | Maven Central | Javadoc |
|-|:-:|:-:|
| knative-client | [![Maven Central](https://maven-badges.herokuapp.com/maven-central/io.fabric8/knative-client/badge.svg?color=blue)](https://maven-badges.herokuapp.com/maven-central/io.fabric8/knative-client) | [![Javadocs](https://www.javadoc.io/badge/io.fabric8/knative-client.svg?color=blue)](https://www.javadoc.io/doc/io.fabric8/knative-client) |
| tekton-client | [![Maven Central](https://maven-badges.herokuapp.com/maven-central/io.fabric8/tekton-client/badge.svg?color=blue)](https://maven-badges.herokuapp.com/maven-central/io.fabric8/tekton-client) | [![Javadocs](https://www.javadoc.io/badge/io.fabric8/tekton-client.svg?color=blue)](https://www.javadoc.io/doc/io.fabric8/tekton-client) |
| servicecatalog-client | [![Maven Central](https://maven-badges.herokuapp.com/maven-central/io.fabric8/servicecatalog-client/badge.svg?color=blue)](https://maven-badges.herokuapp.com/maven-central/io.fabric8/servicecatalog-client) | [![Javadocs](https://www.javadoc.io/badge/io.fabric8/servicecatalog-client.svg?color=blue)](https://www.javadoc.io/doc/io.fabric8/servicecatalog-client) |
| chaosmesh-client | [![Maven Central](https://maven-badges.herokuapp.com/maven-central/io.fabric8/chaosmesh-client/badge.svg?color=blue)](https://maven-badges.herokuapp.com/maven-central/io.fabric8/chaosmesh-client) | [![Javadocs](https://www.javadoc.io/badge/io.fabric8/chaosmesh-client.svg?color=blue)](https://www.javadoc.io/doc/io.fabric8/chaosmesh-client) |
| volumesnapshot-client | [![Maven Central](https://maven-badges.herokuapp.com/maven-central/io.fabric8/volumesnapshot-client/badge.svg?color=blue)](https://maven-badges.herokuapp.com/maven-central/io.fabric8/volumesnapshot-client) | [![Javadocs](https://www.javadoc.io/badge/io.fabric8/volumesnapshot-client.svg?color=blue)](https://www.javadoc.io/doc/io.fabric8/volumesnapshot-client) |
| volcano-client | [![Maven Central](https://maven-badges.herokuapp.com/maven-central/io.fabric8/volcano-client/badge.svg?color=blue)](https://maven-badges.herokuapp.com/maven-central/io.fabric8/volcano-client) | [![Javadocs](https://www.javadoc.io/badge/io.fabric8/volcano-client.svg?color=blue)](https://www.javadoc.io/doc/io.fabric8/volcano-client) |
| istio-client | [![Maven Central](https://maven-badges.herokuapp.com/maven-central/io.fabric8/istio-client/badge.svg?color=blue)](https://maven-badges.herokuapp.com/maven-central/io.fabric8/istio-client) | [![Javadocs](https://www.javadoc.io/badge/io.fabric8/istio-client.svg?color=blue)](https://www.javadoc.io/doc/io.fabric8/istio-client) |
| open-cluster-management-client | [![Maven Central](https://maven-badges.herokuapp.com/maven-central/io.fabric8/open-cluster-management-client/badge.svg?color=blue)](https://maven-badges.herokuapp.com/maven-central/io.fabric8/open-cluster-management-client) | [![Javadocs](https://www.javadoc.io/badge/io.fabric8/open-cluster-management-client.svg?color=blue)](https://www.javadoc.io/doc/io.fabric8/open-cluster-management-client) |

 `✓` means All OpenShift resources provided by this specific release are supported. In other cases, OpenShiftClient would work for standard resources (Pod, Deployment, Service, etc.) but won't guarantee support for all api resources provided by this specific
 version of OpenShift implementation.
