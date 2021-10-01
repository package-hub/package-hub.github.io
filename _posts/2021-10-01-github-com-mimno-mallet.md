---
title: Mallet
categories: ['java']
---
## [Mallet](https://github.com/mimno/Mallet)

### MALLET is a Java-based package for statistical natural language processing, document classification, clustering, topic modeling, information extraction, and other machine learning applications to text.


To build a Mallet 2.0 development release, you must have the Apache ant build tool installed. From the command prompt, first change to the mallet directory, and then type
`ant`

If `ant` finishes with `"BUILD SUCCESSFUL"`, Mallet is now ready to use.

If you would like to deploy Mallet as part of a larger application, it is helpful to create a single ".jar" file that contains all of the compiled code. Once you have compiled the individual Mallet class files, use the command:
`ant jar`

This process will create a file "mallet.jar" in the "dist" directory within Mallet.
