# The Swagger Specification

[![Build Status](https://travis-ci.org/swagger-api/swagger-spec.svg?branch=master)](https://travis-ci.org/swagger-api/swagger-spec)

![](https://raw.github.com/swagger-api/swagger-spec/master/swagger-logo.jpg)
## Welcome to the Swagger Project! 

The goal of Swagger™ is to define a standard, language-agnostic interface to REST APIs which allows both humans and computers to discover and understand the capabilities of the service without access to source code, documentation, or through network traffic inspection.  When properly defined via Swagger, a consumer can understand and interact with the remote service with a minimal amount of implementation logic.  Similar to what interfaces have done for lower-level programming, Swagger removes the guesswork in calling the service.

Use cases for machine-readable API interfaces include interactive documentation, code generation for documentation, client, and server, as well as automated test cases.  Swagger-enabled APIs expose JSON files that correctly adhere to the Swagger Specification, documented in this repository.  These files can either be produced and served statically, or be generated dynamically from your application.

Without going into a long history of interfaces to Web Services, this is not the first attempt to do so.  We can learn from CORBA, WSDL and WADL.  These specifications had good intentions but were limited by proprietary vendor-specific implementations, being bound to a specific programming language, and goals which were too open-ended.  In the end, they failed to gain traction.

Swagger does not require you to rewrite your existing API.  It does not require binding any software to a service--the service being described may not even be yours.  It does, however, require the capabilities of the service be described in the structure of the Swagger Specification.  Not all services can be described by Swagger--this specification is not intended to cover every possible use-case of a REST-ful API.  Swagger does not define a specific development process such as design-first or code-first.  It does facilitate either technique by establishing clear interactions with a REST API.

This GitHub project is the starting point for Swagger.
Here you will find the information you need about the Swagger Specification, a simple static sample of what it looks like,
and some general information regarding the project.


## Current Version - 2.0

The current version of the Swagger specification is 2.0 - and you can find it [here](versions/2.0.md).

### [Swagger 2.0 Specification](versions/2.0.md)

This repository contains the existing Swagger 1.2 specification as well as proposals for the 2.0 version.

## Structure

Each section should contain v1.2 and v2.0 folders to avoid confusion between the versions.

Please keep in mind that the other projects under Swagger use an independent version system.
As such, don't confuse the version of the Swagger Specification they support and the version of that given library.
For example, Swagger-Core with the version 1.3.2 supports Swagger Specification 1.2.

## The Wiki

Check out the [wiki](https://github.com/swagger-api/swagger-spec/wiki) for additional and relevant information about the project.

This includes:
- Static sample tutorial.
- List of known deployments.
- Revision history.

## See it in Action

If you just want to see it work, check out the [pet store sample](http://petstore.swagger.io/).

## Tools and Libraries

Looking to see how you can create your own Swagger definition, present it or otherwise use it? Check out our [list of tools](http://swagger.io/open-source-integrations/) over at [http://swagger.io](http://swagger.io/open-source-integrations/).

(Yes, there used to be a really long list here, we just moved it to the main website)

## License

Copyright 2015 SmartBear Software

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at [apache.org/licenses/LICENSE-2.0](http://www.apache.org/licenses/LICENSE-2.0)

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.

