---
layout: default
title: A study on the state of serverless technologies
tags: ["topics", "serverless"]
---
For one of the projects we're working on and we'll talk about soon, we've stumbled upon a very interesting paper entitled "[A Review of Serverless Use Cases and their Characteristics](https://arxiv.org/abs/2008.11110)" from the [SPEC RG Cloud Working Group](https://research.spec.org/working-groups/rg-cloud.html).

More specifically, the team comprises 8 researchers from universities and institutions located in Ecuador, Germany, The Netherlands and Sweden.

This work is a detailed and comprehensive evaluation of 89 real-world use-cases of serverless applications. The analysis included a set of 24 characteristics, grouped into 5 macro families (general, application, requirements, workload, and workflow).

For each of these, this paper highlights the most relevant findings and offers insightful suggestions. So far, it's one of the most complete analysis we've seen in this domain.

Here an excerpt of some conclusions from the study:

> 1. We find a dominating portion of serverless use cases already being in production with AWS as the most popular platform and web services being the most common application domain.
>
>
> 2. Serverless workloads tend to exhibit on-demand execution patterns exemplified by 81% bursty workloads, which makes their load hard to predict.
>
>   
> 3. Most cloud functions (67%) are short-running, with running times in the order of milliseconds or seconds, thus requiring serverless frameworks that impose small overheads when running functions.
>
>  
> 4. Cost savings (both in terms of infrastructure and operation costs) are a bigger driver for the adoption of cost than the offered performance and scalability gains.
>
>  
> 5. We observe an increasing trend toward ever-larger, ever more complex workflows, indicating the need to move toward (cloud-native) workflow engines.

In conclusion, this paper gives the reader a clever and meaningful conceptual framework to grasp the state of the art in this field.  Hence, if you have an interest in the "serverless world" and you want to know what's out there, we strongly encourage its reading.
