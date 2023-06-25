---
title: gAnswer
categories: ['java', 'semantic-parsing', 'question-answering']
---
## [gAnswer](https://github.com/pkumod/gAnswer)

### A KBQA system based on DBpedia.


GAnswer system is a natural language QA system developed by Institute of Computer Science & Techonology Data Management Lab, Peking University, led by Prof. Zou Lei. GAnswer is able to translate natural language questions to query graphs containing semantic information. Then, the system can further turn query graphs into standard SPARQL query, which will be executed in graph databases, in order to attain answers for the users. We apply an innovative data-driven method for semantic disambiguation. In details, while generating query graphs, we maintain multiple plans for entities and predicate mappings and we conduct semantic disambiguation in the query execution phrase according to entities and predicate matches ( incorrect mappings ).

This is an implementation for TKDE 2018 paper [Answering Natural Language Questions by Subgraph Matching over Knowledge Graphs](docs/TKDE18_gAnswer.pdf) 

**For help document, click here [中文(ZH)](docs/gAnswer_help.pdf), [English](docs/gAnswer_help_en.pdf)
