---
title: ruby-debug-ide
categories: ['ruby']
---
## [ruby-debug-ide](https://github.com/ruby-debug/ruby-debug-ide)

### An interface which glues ruby-debug to IDEs like Eclipse (RDT), NetBeans and RubyMine.


The 'ruby-debug-ide' gem provides the protocol to establish communication between the debugger engine (such as [debase](https://rubygems.org/gems/debase) or [ruby-debug-base](https://rubygems.org/gems/ruby-debug-base)) and IDEs (for example, RubyMine, Visual Studio Code, or Eclipse). 'ruby-debug-ide' redirect commands from the IDE to the debugger engine. Then, it returns answers/events received from the debugger engine to the IDE. To learn more about a communication protocol, see the following document: [ruby-debug-ide protocol](protocol-spec.md).
