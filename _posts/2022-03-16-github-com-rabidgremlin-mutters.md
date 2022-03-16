---
title: Mutters
categories: ['java', 'machine-learning', 'bot']
---
## [Mutters](https://github.com/rabidgremlin/Mutters)

### A framework for building bot brains.

A Java framework for building bot brains. Heavily inspired by Amazon Echo's natural language understanding model.  

Implements:

* Templated and/or machine learning based identification of a user's intent based on their utterance. Support out of the box for OpenNLP or Facebook's fastText.
* Templated and/or machine learning based (NER) extraction of data from the user's utterance
* State management to support complex conversations, using either:
  * a state machine
  * Inkle's narrative scripting engine [Ink](http://www.inklestudios.com/ink/)
* Pluggable intent matching, named entity extraction and conversation state management so you can use our own implementations.  
  