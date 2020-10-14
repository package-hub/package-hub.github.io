---
title: ts-protoc-gen
categories: ['typescript', 'protocol-buffers', 'protoc']
---
## [ts-protoc-gen](https://github.com/improbable-eng/ts-protoc-gen)

### Protocol Buffers Compiler (protoc) plugin for TypeScript and gRPC-Web.


> Protoc Plugin for generating TypeScript Declarations

This repository contains a [protoc](https://github.com/google/protobuf) plugin that generates TypeScript declarations
(`.d.ts` files) that match the JavaScript output of `protoc --js_out=import_style=commonjs,binary`. This plugin can
also output service definitions as both `.js` and `.d.ts` files in the structure required by [grpc-web](https://github.com/improbable-eng/grpc-web), and as `.d.ts` files in the structure required by [grpc-node](https://github.com/grpc/grpc-node).

This plugin is tested and written using TypeScript 2.7.
