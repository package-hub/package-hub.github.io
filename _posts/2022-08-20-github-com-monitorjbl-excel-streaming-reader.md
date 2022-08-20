---
title: excel-streaming-reader
categories: ['java']
---
## [excel-streaming-reader](https://github.com/monitorjbl/excel-streaming-reader)

### An easy-to-use implementation of a streaming Excel reader using Apache POI


If you've used [Apache POI](http://poi.apache.org) in the past to read in Excel files, you probably noticed that it's not very memory efficient. Reading in an entire workbook will cause a severe memory usage spike, which can wreak havoc on a server. 

There are plenty of good reasons for why Apache has to read in the whole workbook, but most of them have to do with the fact that the library allows you to read and write with random addresses. If (and only if) you just want to read the contents of an Excel file in a fast and memory effecient way, you probably don't need this ability. Unfortunately, the only thing in the POI library for reading a streaming workbook requires your code to use a SAX-like parser. All of the friendly classes like `Row` and `Cell` are missing from that API.

This library serves as a wrapper around that streaming API while preserving the syntax of the standard POI API. Read on to see if it's right for you.

**NOTE**: This library only supports reading XLSX files.
