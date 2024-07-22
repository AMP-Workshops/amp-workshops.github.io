---
title: "A service mesh for collaboration between geo-distributed services: the replication case"
layout: paper
feature_image: "image9.jpg"
image_source: "<a href=\"https://pixabay.com/users/manuchi-1728328\" target=\"_blank\">Manuchi</a>"
current_link: assets/papers/paper1.v0.pdf
previous_links:
---

### Authors

Marie Delavergne,
Ronan-Alexandre Cherrueau,
and Adrien Lebre

LS2N, INRIA, France

### Abstract

Edge computing is becoming more and more present, with edge infrastructures
geo-distributed around the globe. These infrastructures must be able to manage
the latency and disconnections inherent to their distribution. In parallel, the
behavior of cloud applications is getting more complex to apprehend as they are
composed of a lot of small services, which serve each a defined purpose. To
manage these applications more easily, service meshes handle communications
between services and offer different features such as service discovery or
traffic monitoring.

We believe that service meshes are an opportunity to create a service dedicated
to manage the geo-distribution of applications. To do so, we created scope-lang,
a language that allows DevOps to specify precisely where a request will be
executed. By reifying the location of application instances in requests and
allowing redirections between these requests thanks our service and some service
mesh functionalities, we make possible three types of collaborations between
services. This paper focuses on the replication of a resource on different
services instances across different sites and presents Cheops, the service to
manage geo-distribution.