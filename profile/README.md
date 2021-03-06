# Apollo-Core

Welcome to the documentation of the Apollo-Core Github organization.

---------------------------------------------------

## ApolloWf Project

The Apollo-Core organization is part of the [ApolloWf](https://apollowf.github.io/) project of the [distributed and parallel systems group](http://dps.uibk.ac.at/) of the University of Innsbruck, Austria. The purpose of this open-source project is to enable the execution of complex applications using serverless functions which are distributed across cloud, edge, and IoT resources. At the core of this project is the **Apollo Runtime System** which orchestrates and optimizes the execution of the application. This GitHub organization (Apollo-Core) contains the source code of the fundamental parts of this runtime system.

-----------------------------------

## Getting Started

- A short introduction of Apollo's purpose and its focus user group is provided in a [Youtube video](https://www.youtube.com/watch?v=Jb-jaxuSUDs).

- A brief guide to quickly set up a running orchestration is provided in the [EE-Demo](https://github.com/Apollo-Core/EE-Demo) repository and in a [Youtube video](https://www.youtube.com/watch?v=KFoT99tpJBk).

- A hands-on tutorial demonstrating the tooling and the steps necessary to orchestrate applications with Apollo is provided in the [Tutorial](https://github.com/Apollo-Core/Tutorial) repository and in a [series of Youtube videos](https://youtube.com/playlist?list=PL6bKn3xU682w9z7IIUMezpixWf5_ye2sN).

----------------------------

## Issues and Feature Requests

If you find issues/bugs or have an idea or need for certain extensions of the framework, please formulate an issue in the repository which seems most appropriate and/or reach our directly by writing an email to [apolloruntime@gmail.com](mailto:apolloruntime@gmail.com).

-----------------------------------


## Citation

Apollo's system and orchestration models have been published in [[1]](#1) and [[2]](#2). If you find Apollo to be useful for your work, please consider citing [[2]](#2).

-----------------------------------

## Organization Overview

The Apollo-Core organization consists of 13 repositories:

- [EE-Core](https://github.com/Apollo-Core/EE-Core) - main interfaces shared across the other repositories
- [EE-Guice](https://github.com/Apollo-Core/EE-Guice) - [google guice](https://github.com/google/guice) modules used for dynamic dependency injection
- [EE-Model](https://github.com/Apollo-Core/EE-Model) - graph-based system model used to represent the application and the available resources
- [EE-IO](https://github.com/Apollo-Core/EE-IO) - definition of the input file format, parsers for the input files ([AFCL](https://apollowf.github.io/learn.html) among others) used to generate the system model
- [EE-Enactables](https://github.com/Apollo-Core/EE-Enactables) - atomic units of execution such as serverless function triggers or control- and data flow constructs
- [SC-Core](https://github.com/Apollo-Core/SC-Core) - interfaces for schedulers used during the orchestration
- [EE-Control](https://github.com/Apollo-Core/EE-Control) - main components controlling the orchestration at runtime
- [EE-Visualization](https://github.com/Apollo-Core/EE-Visualization) - (real-time) visualization of the system model throughout the orchestration
- [EE-Docker](https://github.com/Apollo-Core/EE-Docker) - execution of application functions in local Docker containers
- [EE-Deploy](https://github.com/Apollo-Core/EE-Deploy) - infrastructure for deploying Apollo as an orchestration (web) service
- [EE-Demo](https://github.com/Apollo-Core/EE-Demo) - simple applications for demonstration purposes
- [IntegrationTests](https://github.com/Apollo-Core/IntegrationTests) - integration tests used for the CI workflows
- [RepositoryConfiguration](https://github.com/Apollo-Core/RepositoryConfiguration) - style for the code format, code quality rules applied during the CI checks

<!--
------------------------------

## Versioning

The following table provides the currently stable versions of the organization repositories:

Repository | Most Recent Stable Version | gradle dependency
-----------|----------------------------|------------------
[EE-Core](https://github.com/Apollo-Core/EE-Core) | 1.0.1 | implementation 'com.github.Apollo-Core:EE-Core:v1.0.1'
[EE-Guice](https://github.com/Apollo-Core/EE-Guice) | 1.0.2 | implementation 'com.github.Apollo-Core:EE-Guice:v1.0.2'
[EE-Model](https://github.com/Apollo-Core/EE-Model) | 1.0.2 | implementation 'com.github.Apollo-Core:EE-Model:v1.0.2'
[EE-IO](https://github.com/Apollo-Core/EE-IO) | 1.0.2 | implementation 'com.github.Apollo-Core:EE-IO:v1.0.2'
[EE-Enactables](https://github.com/Apollo-Core/EE-Enactables) | 1.0.3 | implementation 'com.github.Apollo-Core:EE-Enactables:v1.0.3'
[SC-Core](https://github.com/Apollo-Core/SC-Core) | 1.0.2 | implementation 'com.github.Apollo-Core:SC-Core:v1.0.2'
[EE-Control](https://github.com/Apollo-Core/EE-Control) | 1.0.2 | implementation 'com.github.Apollo-Core:EE-Control:v1.0.2'
[EE-Visualization](https://github.com/Apollo-Core/EE-Visualization) | 1.0.2 | implementation 'com.github.Apollo-Core:EE-Visualization:v1.0.2'
[EE-Docker](https://github.com/Apollo-Core/EE-Docker) | 1.0.2 | implementation 'com.github.Apollo-Core:EE-Docker:v1.0.2'
[EE-Deploy](https://github.com/Apollo-Core/EE-Deploy) | 1.0.2 | implementation 'com.github.Apollo-Core:EE-Deploy:v1.0.2'
[EE-Demo](https://github.com/Apollo-Core/EE-Demo) | 1.0.2 | -
[IntegrationTests](https://github.com/Apollo-Core/IntegrationTests) | 1.0.2 | -


--------------------------------
-->

## Uses

- [VertX](https://vertx.io/)
- [OpenDse](https://github.com/SDARG/opendse)

## Related Apollo Organizations 

- [Apollo-AFCL](https://github.com/Apollo-AFCL)
- [Apollo-Functions](https://github.com/Apollo-Functions)
- [Apollo-Tools](https://github.com/Apollo-Tools)
- [Apollo-Workflows](https://github.com/Apollo-Workflows)

--------------------------------

## References
<a id="1">[1]</a> 
Smirnov, F. S. et al. (2021). 
Apollo: Modular and distributed runtime system for serverless function compositions on cloud, edge, and iot resources. 
Proceedings of the 1st Workshop on High Performance Serverless Computing, 5-8.

<a id="2">[2]</a> 
Smirnov, F. S. et al. (2021). 
Apollo: Towards an efficient distributed orchestration of serverless function compositions in the cloud-edge continuum. 
Proceedings of the 14th IEEE/ACM International Conference on Utility and Cloud Computing, 1-10.


<!--

**Here are some ideas to get you started:**
????
????????????? A short introduction - what is your organization all about?
???? Contribution guidelines - how can the community get involved?
??????????? Useful resources - where can the community find your docs? Is there anything else the community should know?
???? Fun facts - what does your team eat for breakfast?
???? Remember, you can do mighty things with the power of [Markdown](https://guides.github.com/features/mastering-markdown/)
-->
