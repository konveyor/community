# Konveyor Charter

## Overview
Konveyor is an open-source application modernization platform that helps organizations safely and predictably modernize applications to new technologies, with an initial focus on accelerating the adoption of legacy applications to Kubernetes.

The project’s design incorporates years of experience with consulting engagements successfully helping companies move existing applications to new technologies, such as Kubernetes.  The patterns and processes that led to successful, predictable, and safe modernization engagements were distilled into an [open-source methodology](https://github.com/konveyor/methodology).  This methodology is not required to be used with Konveyor but remains available to help guide others embarking on their own modernization journey who don’t have a preferred methodology.

Konveyor aims to make the modernization of legacy applications to Kubernetes its #1 priority while realizing that technology is evolving and the need for modernizing to new technologies will remain in the future.  We believe the basic patterns to address modernization needs can be built generically into a platform with technology-specific information added as new technologies emerge, thereby allowing the platform to evolve over time to address new needs.

![alt_text](img/konveyor_header.png "image_tooltip")

## Vision Statement

To become the ultimate open-source application modernization platform, helping organizations safely and predictably modernize their portfolios to evolving technology needs.

## Mission Statement

Accelerate the adoption of Kubernetes by helping organizations modernize their legacy applications to Kubernetes and cloud-native technologies in a safe and predictable manner at scale, providing value at each phase of the adoption journey.

## Objectives

Konveyor will deliver a [Unified Experience](https://github.com/konveyor/enhancements/tree/master/enhancements/unified_experience) developed in a technology-agnostic manner, meaning Konveyor will codify discrete steps to build a workflow for any modernization journey, relying on additional components to provide the technology-specific details. The aim is that this solution will be able to evolve in time as technology needs change beyond the initial goal of enabling legacy applications to be modernized to Kubernetes.

The platform will:

* Surface information to empower an [enterprise architect](#personas) to make better-informed decisions in regard to application modernization, i.e. the [6Rs made popular by Amazon](https://aws.amazon.com/blogs/enterprise-strategy/6-strategies-for-migrating-applications-to-the-cloud/).  
  * Analysis and assessment capabilities will allow the detection of technologies, patterns, and concerns that may pose problems to containerizing and deploying an application to Kubernetes. 
  * Allow an enterprise architect to see high-level trends across the entire portfolio of applications and then drill down into a specific technical issue for a given application and see the exact lines of source code involved.
* Record decisions from the enterprise architect in regard to what they deem as appropriate for each application given the information provided.
  * The platform will **not** make automatic decisions about what should be done with an application.  The platform is focused on raising awareness of technical factors to consider but defers the business value judgment to a knowledgeable enterprise architect.
* Aid the enterprise architect in planning and managing the work related to modernization decisions
  * Integration with external issue management systems will help stakeholders to plan and correlate work tasks for [migrators](#personas) to perform
* Reduce the effort required to bring a legacy application to Kubernetes
  * Ease the transition to containerization and Kubernetes by assisting with the generation of artifacts for applications at scale
  * Allow recipes or remediation workflows to be constructed and run to kickstart the work a Migrator needs to accomplish their modernization work.
* Allow organizations to manage their application portfolio in a centralized fashion, and from there be able to classify applications and launch any kind of actions that might be related to them, such as analysis and assessments
* Establish a pattern of continual enhancement of technology-specific information via leveraging the open source community to contribute knowledge and concerns related to modernizing applications to Kubernetes
  * A  [user-group of subject matter experts](https://github.com/konveyor/community/tree/main/ug-migration-experience) has been established who are engaging in application modernization efforts on a regular basis.  The intent is to solicit use cases, problems, recommendations, and remediations from the challenges the members encounter and bring those learnings back into the larger community and platform.

## Personas

* Enterprise Architect
  * A decision maker leading the modernization/migration initiative, who will review information Konveyor surfaces about an application's suitability for a given platform or runtime technology and ultimately make decisions of planning work for a Migrator to complete.
    * Surfaced information will be used to help this user make informed decisions, plan, and begin to execute modernization work.
    * Architects are expected to be knowledgeable individuals that understand the business value an application provides and are capable of weighing technical costs versus expected business value to decide on the best course for modernization need.
* Migrator 
  * A developer assigned to handle the source code updates and development efforts to satisfy issues identified and allow the application to run on a target platform or runtime technology and ideally leverage its capabilities.
* Project Manager
  * A management lead for the migration project that can create and modify [migration waves](https://github.com/konveyor/enhancements/tree/master/enhancements/migration-waves) and assign applications to them.
* Executive
  * An individual who is interested in viewing summary information for migration projects

## What is in Scope?

The Konveyor community is focused on

* Building a modernization platform that will be able to evolve in time as new technologies arise
* Building analysis and assessment capabilities for multiple languages, frameworks, and new technologies with an emphasis on Kubernetes
* Integrating tools from other Open Source communities, such as those related to
  * Analysis and assessment capabilities
  * Help with onboarding an application to Kubernetes such as manifest generation, setting up secure pipeline builds, embracing GitOps, etc
  * Tools that expand capabilities to aid in reducing work required for a developer involved in a modernization activity, i.e. test generation, running openrewrite rules, automating tasks, etc
* Capturing information and learnings from use-cases, problems, and recommendations over a wide array of legacy technologies and their paths to embracing new framework and/or cloud-native technologies
  * Goal is to translate learnings from subject matter experts into rules and remediation recipes that others may benefit from shared experiences.

## What is out of Scope?

* Automatic decision making of “what to do” in regard to the [6Rs](https://aws.amazon.com/blogs/enterprise-strategy/6-strategies-for-migrating-applications-to-the-cloud/).  
  * Konveyor aims to automate the gathering and surfacing of information, yet it makes a hard call to abstain from making decisions about what path to recommend.  We believe an enterprise architect who understands the business value needs to make the ultimate decision of what is best for the business.  Konveyor’s goal is to better inform the enterprise architect of technology related concerns in each application and defer decisions to their judgment.
* Creating a “magic button” that will auto-translate a legacy application to be cloud-native
  * We have a strong interest in keeping aware of advancements in AI and are open to incorporating new tools, but at present, this is an unattainable goal for the resources and skillsets we have available in the Konveyor Community.
    * The current focus will remain on “surfacing information”
* Automatic refactoring
  * Similar to above, a full application refactoring is out of scope, yet we will entertain bringing recipes into Konveyor that can handle well known specific situations of executing refactoring capabilities.  This is not our primary focus, but it is an area we believe could expand in time for certain frameworks and problems.

## Konveyor Ecosystem

Konveyor consists of 2 GitHub Organizations:

* [https://github.com/konveyor](https://github.com/konveyor)
  * The essential repositories and integration code associated with delivering the modernization platform and analysis capabilities
* [https://github.com/konveyor-ecosystem](https://github.com/konveyor-ecosystem) 
  * A related GitHub organization focused as an incubator for rapid innovation on tools that solve for specific steps of the modernization process

## Governance

The Konveyor Project is [governed](https://github.com/konveyor/community/blob/main/GOVERNANCE.md) by a Steering Committee composed of community leaders, project maintainers, and contributors. The Steering Committee is responsible for setting the strategic direction of the project, managing the community, and ensuring the quality and sustainability of the Konveyor projects.

The Konveyor Project follows the principles of the CNCF [Code of Conduct](https://github.com/konveyor/community/blob/main/CODE_OF_CONDUCT.md) to ensure a welcoming, respectful and inclusive environment for all participants. We encourage diversity and value the contributions of everyone, regardless of their background or affiliation.

## Contributing

The Konveyor Project welcomes contributions from all individuals, including developers, testers, designers, documentation writers, and users. Contributions can take various forms, including code, documentation, testing, bug reports, feature requests, and community engagement.

To contribute to the Konveyor Project, follow the [project's contribution guidelines](https://github.com/konveyor/community/blob/main/CONTRIBUTING.md), which outline the process of submitting and reviewing contributions. Contributions are subject to review and approval by the project maintainers and the Steering Committee.

A great way to get started is to attend a [community meeting](https://github.com/konveyor/community#community-meeting) and introduce yourself, a maintainer will be happy to answer questions and point you to appropriate paths for your contribution interests.

## Updates/Changes to the Charter

The Konveyor community may propose changes to this charter as the community grows.  Any changes to the vision, mission, scope of the charter will require a 2/3 majority vote of the Konveyor Steering committee.