---
title: SerializationDumper
categories: ['java']
---
## [SerializationDumper](https://github.com/NickstaDB/SerializationDumper)

### A tool to dump Java serialization streams in a more human readable form.

A tool to dump and rebuild Java serialization streams and Java RMI packet contents in a more human readable form.

The tool does not deserialize the stream (i.e. objects in the stream are not instantiated), so it does not require access to the classes that were used in the stream*.

This tool was developed to support research into Java deserialization vulnerabilities after spending many hours manually decoding raw serialization streams to debug code!

Download v1.11 built and ready to run from here: [https://github.com/NickstaDB/SerializationDumper/releases/download/1.13/SerializationDumper-v1.13.jar](https://github.com/NickstaDB/SerializationDumper/releases/download/1.13/SerializationDumper-v1.13.jar "SerializationDumper-v1.13.jar")

\* See the limitations section below for more details.

**Update 19/12/2018:** SerializationDumper now supports rebuilding serialization streams so you can dump a Java serialization stream to a text file, modify the hex or string values, then convert the text file back into a binary serialization stream. See the section below on [Rebuilding Serialization Streams](#rebuilding-serialization-streams) for an example of this.
