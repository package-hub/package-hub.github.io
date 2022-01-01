---
title: simple-websockets-chat-app
categories: ['javascript', 'websockets', 'apigateway']
---
## [simple-websockets-chat-app](https://github.com/aws-samples/simple-websockets-chat-app)

### This SAM application provides the Lambda functions, DynamoDB table, and roles to allow you to build a simple chat application based on API Gateway's new WebSocket-based API feature. 


This is the code and template for the simple-websocket-chat-app.  There are three functions contained within the directories and a SAM template that wires them up to a DynamoDB table and provides the minimal set of permissions needed to run the app:

```
.
├── README.md                   <-- This instructions file
├── onconnect                   <-- Source code onconnect
├── ondisconnect                <-- Source code ondisconnect
├── sendmessage                 <-- Source code sendmessage
└── template.yaml               <-- SAM template for Lambda Functions and DDB
```

