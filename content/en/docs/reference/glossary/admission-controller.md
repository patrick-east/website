---
title: Admission Controller
id: admission-controller
date: 2019-06-28
full_link: /docs/reference/access-authn-authz/admission-controllers/
short_description: >
  A piece of code that intercepts requests to the Kubernetes API server prior to persistence of the object.

aka:
tags:
- extension
- security
---
A piece of code that intercepts requests to the Kubernetes API server prior to persistence of the object.

<!--more-->

Admission controllers may be “validating”, “mutating”, or both. Mutating controllers may modify the objects they admit; validating controllers may not. Multiple controllers may be enabled. If any of the controllers reject the request, the entire request is rejected immediately and an error is returned to the end-user.

* [Admission contollers in the Kubernetes documentation](/docs/reference/access-authn-authz/admission-controllers/)
