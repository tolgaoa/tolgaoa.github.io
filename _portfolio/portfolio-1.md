---
title: "O-RAN Security for xApps"
excerpt: "Design, Implementation and Testing of a Scalable Authentenication, Authorization and Discovery Framework for xApps in the O-RAN Ecosystem<br/><img src='/images/xrfov.png' width='600' height='400'>"
collection: portfolio
---

<img src='/images/xrfdet.png'><br>

The ongoing transformation of mobile networks from proprietary physical network boxes to virtualized functions and deployment models has led to more scalable and flexible network architectures capable of adapting to specific use cases. As an enabler of this movement, the OpenRAN initiative promotes standardization allowing for a vendor-neutral radio access network with open APIs. Moreover, the O-RAN Alliance has begun specification efforts conforming to OpenRAN's definitions. This includes the near-real-time RAN Intelligent Controller (RIC) overseeing a group of extensible applications (xApps). The use of these potentially untrusted third-party applications introduces a new attack surface to the mobile network plane with fundamental security and system design requirements that are yet to be addressed. To secure the 5G O-RAN xApp model, we introduce the xApp Repository Function (XRF) framework, which implements scalable authentication, authorization, and discovery for xApps. We first present the framework's system design and implementation details, followed by operational benchmarks in a production-grade containerized environment. The evaluation results, centered on active processing and operation times, show that our proposed framework can scale efficiently in a multi-threaded Kubernetes microservice environment and support a large number of clients with minimal overhead.
