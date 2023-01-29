---
layout: home
title: DS5110, Spring 2023
nav_exclude: true
type: Course
name: DS5110, Big Data Systems
---

# {{ site.title }}: {{ site.tagline }}
{: .mb-2 }
{: .fs-6 .fw-300 }

{% if site.announcements %}
{{ site.announcements.last }}
 [Announcements]({{ site.baseurl }}{% link announcements.md %}){: .btn .btn-outline .fs-3 }
{% endif %}


## Overview

Welcome to the graduate course on Big Data Systems.  Scalable big
data systems are a central part of modern data science.  This course
will cover topics including design and use of parallel dataflow
systems (MapReduce/Hadoop and Spark), scalable and parallel Python
analytics frameworks, cloud data systems (cloud storage, cloud-native
data processing), and machine learning systems. A major component of
this course is hands-on programming using scalable analytics tools
and cloud resources on Amazon Web Services (AWS) and Google Cloud.


## Lecture Info

* Instructor: [Yue Cheng](https://tddg.github.io)
* Meeting time: MW 3:30 pm - 4:45pm
* Location: Olsson Hall 009


## Topics (tentative)

* Basic of computer systems, principles of parallel and distributed computing
* Google big data infrastructures (MapReduce, Google File System)
* Spark RDD
* Parallel Python analytics
* Large-scale databases, cloud storage systems (Amazon Dynamo/AWS DynamoDB)
* Cloud computing
* Cloud-native big data systems (serverless computing, serverless analytics)
* Machine learning systems (PyTorch, federated learning)
* Data warehouse/datacenter (Snowflake, Alibaba)


## Prerequisite

* All students should be comfortable with programming in **one** of the following programming languages: Python, Java, Go, C/C++. This is a strong requirement as DS 5110 features hands-on programming.
	* That said, being comfortable with Python is **strongly recommended** as all the programming assignments will be done using Python. Having some experience in Java, Go, C/C++ is a big plus!
