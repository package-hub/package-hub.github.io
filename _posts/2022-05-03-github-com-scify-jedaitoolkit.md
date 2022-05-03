---
title: JedAIToolkit
categories: ['java', 'entity-resolution', 'entity-matching']
---
## [JedAIToolkit](https://github.com/scify/JedAIToolkit)

### An open source, high scalability toolkit in Java for Entity Resolution.

JedAI constitutes an open source, high scalability toolkit that offers out-of-the-box solutions for any data integration task, e.g., Record Linkage, Entity Resolution and Link Discovery. At its core lies a set of *domain-independent*, *state-of-the-art* techniques that apply to both RDF and relational data. These techniques rely on an approximate, *schema-agnostic* functionality based on *(meta-)blocking* for high scalability. 

JedAI can be used in three different ways:

  1) As an **open source library** that implements numerous state-of-the-art methods for all steps of the end-to-end ER work presented in the figure below.
  2) As a [**desktop application**](https://github.com/scify/jedai-ui) with an intuitive Graphical User Interface that can be used by both expert and lay users.
  3) As a **workbench** that compares the relative performance of different (configurations of) ER workflows.
  
This repository contains the code (in Java 8) of JedAI's open source library. The code of JedAI's desktop application and workbench is available in this [repository](https://github.com/scify/jedai-ui). 

Several **datasets** already converted into the serialized data type of JedAI can be found [here](./data).

You can find a short presentation of JedAI Toolkit [here](documentation/JedAIpresentation.pptx).
