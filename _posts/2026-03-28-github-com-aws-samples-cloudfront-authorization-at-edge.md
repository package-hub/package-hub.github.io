---
title: cloudfront-authorization-at-edge
categories: ['typescript']
---
## [cloudfront-authorization-at-edge](https://github.com/aws-samples/cloudfront-authorization-at-edge)

### Protect downloads of your content hosted on CloudFront with Cognito authentication using cookies and Lambda@Edge


This repo accompanies the [blog post](https://aws.amazon.com/blogs/networking-and-content-delivery/authorizationedge-using-cookies-protect-your-amazon-cloudfront-content-from-being-downloaded-by-unauthenticated-users/).

In that blog post a solution is explained, that puts **Cognito** authentication in front of (S3) downloads from **CloudFront**, using **Lambda@Edge**. **JWTs** are transferred using **cookies** to make authorization transparent to clients.

The sources in this repo implement that solution.

The purpose of this sample code is to demonstrate how Lambda@Edge can be used to implement authorization, with Cognito as identity provider (IDP). Please treat the code as an _**illustration**_––thoroughly review it and adapt it to your needs, if you want to use it for serious things.
