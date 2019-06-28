---
title: Open Policy Agent (OPA)
id: opa
date: 2019-06-28
full_link: https://www.openpolicyagent.org/
short_description: >
  A general purpose policy engine.

aka:
tags:
- extension
- security
- tool
---
A general purpose policy engine.

<!--more-->

OPA is a lightweight general-purpose policy engine (not Kubernetes-specific) that can be co-located with your service. You can integrate OPA as a sidecar, host-level daemon, or library. It is often used as an {{< glossary_tooltip text="admission controller" term_id="admission-controller" >}} in Kubernetes.

Services offload policy decisions to OPA by executing queries. OPA evaluates policies and data to produce query results (which are sent back to the client). Policies are written in a high-level declarative language and can be loaded into OPA via the filesystem or well-defined APIs.

* [Open Policy Agent documentation](https://www.openpolicyagent.org/docs)
