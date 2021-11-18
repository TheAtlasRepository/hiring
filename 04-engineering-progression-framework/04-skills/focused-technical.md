### Accessibility (iACC) ### 

This is an elective skill. You may choose this as one of your required quota from the focused technical category.

Making sure our implementations are accessible to everyone regardless of disability or impairment, can be used with assistive technology, and follows WCAG guidelines.

**LVL 2 - Engineer I**

Is broadly familiar with accessibility and why it is important.

* understands a few basic accessibility considerations such as colour contrast ratio, image alternative text, and minimum text sizes.
* uses semantic HTML including hierarchical headings.

**LVL 3 - Engineer II**

Has a basic level of understanding of accessibility specifics. Able to implement accessible features, test their implementation, and understand recommendations from an audit.

* builds features conforming to WCAG 2.1 level AA.
* is familiar with the impact of DOM structure, semantic HTML, and other native patterns (form labels, alt tags, etc) on accessibility.
* knows about ARIA techniques and skip navigation links.
* knows about tools for testing accessibility.
* can act on feedback from an accessibility audit.

**LVL 4 - Senior I, TTL, SEM**

Has a good understanding of accessibility and considerations as it pertains to entire sites. Leads others on accessibility topics especially during design and code review. Can conduct a basic accessibility audit.

* builds sites conforming to WCAG 2.1 level AA, and may have built sites or features to higher levels.
* considers accessibility as part of implementation, not as an afterthought.
* can advise clients and designers during the design review phase.
reviews others' work for accessibility issues.
* has a higher understanding of ARIA techniques and applying them, including roles, states, and properties.
* can create a simple accessibility report using automated tools (Wave, Lighthouse, etc).

**LVL 5 - Senior II**

Defines the accessibility approach on their project, ensuring it is an integral part of our design and development process. Able to clarify accessibility topics, especially to clients, and provide alternative solutions. Able to create (or contribute to) detailed reports from accessibility audits which specify priorities, risks, and opportunities.

* introduces or enforces processes to include accessibility as part of implementation, not as an afterthought.
* introduces automated accessibility auditing tools for use in engineer workflows and/or CI pipelines
* suggests accessibility improvements to clients and their team for new or existing features.
* able to escalate issues related to the client brand, such as brand colours and fonts/sizes, and recommend accessible solutions.
* can create a full accessibility report using manual testing in addition to automated tools (Wave, Lighthouse, etc).
* guides and trains others on accessibility topics outside of their project.

**LVL 6 - Principal**

Guides Enernite's overall approach to accessibility, recommending tools and processes that can be applied across multiple projects. An authority in this domain who guides and educates others on our best practice.

* ensures accessibility across multiple projects matches at least WCAG 2.1 level AA for topics within Enernite's control (eg. not necessarily content).
* considers accessibility for any site they're involved in and knows its implications for any project.
* advises on specific tools and approaches in this domain.
might conduct external accessibility training.

### Data Storage & Retrieval (iDSR) ###

This is an elective skill. You may choose this as one of your required quota from the focused technical category.

Knowledge required for software engineers to work with data storage systems. This includes relational databases like MySQL, key-value stores like Redis, or use of browser stores such as cookies and local storage. This also covers the methods of interacting with data stores, such as SQL in RDBMS, and GraphQL when working with APIs.

**LVL 2 - Engineer I**

Has basic knowledge of data stores, capable of performing simple storage and retrieval operations.

**LVL 3 - Engineer II**

Is familiar with data stores within their domain, likely one or two specifically, and the common ways of interacting with them on projects.

* can architect simple structures appropriate to the application domain within their data store, understanding the core principles to make them efficient (e.g. having indexes for SQL tables, GraphQL object caching).
* uses the tools and libraries within the platform they regularly work with to interact with data stores, such as using Doctrine to interact with MySQL.
* understands the native mechanisms for interacting with data stores (SQL for RDBMS), so they can interrogate them standalone effectively, without relying on libraries and abstraction layers.
* is able to examine the contents of a data store to correlate the behaviour of an application to the data being stored.
* can select an appropriate place to store data, understanding the implications of doing so. For example, when to use a cookie, local storage or session.
* knows how to store or reference sensitive data appropriately and securely.

**LVL 4 - Senior I, TTL, SEM**

Understands different data stores to the level of being able to optimise and improve their use from design and performance perspectives.

* can plan their code to minimise the impact of utilising a data store, such as retrieving larger amounts of data as a batch rather than individually.
* employs simple techniques for improving the performance of data store operations, such as when using a normalised table structure in a relational database is appropriate.
* is familiar with tools and techniques for analysing data store interactions to identify bottlenecks and opportunities for optimisation, for example using the output of EXPLAIN on a MySQL query to identify KEYs being used.
* understands the key ways a data store may be configured to optimise interactions with it, such as choosing the appropriate level of transaction isolation to use in an RDBMS.
* is aware of how a platform, and the libraries it uses, interact with the data store, the benefits this provides but also the pitfalls that may arise. For example: tracking database transactions, or how the data schema may be constructed.
* is aware of techniques on how to monitor and diagnose issues, such as using the MySQL slow query log, or browser developer tools to examine cookies and local storage.

**LVL 5 - Senior II**

Is considered an authority with the data stores commonly used within their domain. Can extend their knowledge to less familiar technologies, and plan their use in conjunction with those used as standard.

* considers the movement of data between different data stores and plans their implementation to interact with all of them effectively, for example ensuring that content updates are coordinated between browser local storage and the application database.
* is familiar with replication and how this affects the behaviour of the application, such as with a Document Store that replicates data between multiple nodes.
* can plan their code to utilise the most appropriate node for each operation and can recognise when issues have arisen from this, for example writing data to the primary database, reading data from a replica.
* is capable of performing in-depth investigations to identify the causes of problems, and implement or recommend appropriate solutions, For example using MySQL ‘SHOW ENGINE INNODB STATUS’ to diagnose transaction issues.
* is aware of the common configuration options for a storage system, and can work with devops and service providers to tune these for improving performance and uptime.
* guides others within their team on the standard and optimal approaches for utilising the data stores with which they are most familiar.

**LVL 6 - Principal**

Uses their broad and deep experience of data storage solutions to architect complex project applications, guiding and upskilling teams on the rationale behind their decisions at every opportunity.

* is able to build systems with distributed data points, and plan how they will interact together to create the most seamless experience for the end user. For example, the interaction of the browser with the server, optimistic UI updates, messages being sent to a queue, subscribers processing those messages and storing data in DB, and a fast key-pair store such as Redis.
* can assess the pros and cons of different data store solutions and make a recommendation based upon reference architectures and project requirements, for example MySQL versus pSQL, Redis vs Memcached, local component state vs Redux.
* understands replication and clustering techniques for a variety of data store types and can make recommendations on the set up of these for scalability purposes, such as multi-primary or multi-replica replication, sharding, and failover in RDBMS.
* is able to convey the intention of the architecture to a project team, and advise on the management of data between data-points so that the team may competently implement the solution.
* mentors team members of the projects they are involved with, and the wider Enernite community on the best practices and advanced techniques for utilising data stores.

### Design Realisation & User Experience (iDUX) ###

This is an elective skill. You may choose this as one of your required quota from the focused technical category.

The process of interpreting design references, prototyping and accurately replicating them, while taking into account user experience concerns and technical limitations. Iterating on the implementation and design of features, interactions, and interfaces to meet usability and accessibility requirements.

**LVL 2 - Engineer I**

Can implement basic responsive sites from designs.

* able to implement a mostly-accurate representation from design references.
* interprets and follows visual design and branding guidelines to create consistent and impactful user experience.
* familiar with considerations for implementing responsive designs for a variety of browsers and devices.

**LVL 3 - Engineer II**

Understands and considers the approaches for implementing robust designs. Interprets and collaborates on designs and implementations.

* able to produce an accurate representation from design references or prototyping programmes, including responsive designs.
* understands how to implement features compatible with a variety of browsers and devices, is able to test them for compatability.
* understands and applies usability and accessibility requirements defined for a project, supporting more junior members to work within these requirements.
* proactively asks questions about designs, escalating to the design team or a senior member of the team as appropriate.
* proactively interprets cases not documented in the provided design references, including interactions and layouts at various viewports.
* uses visual PRs to provide context to UI or behaviour changes using screenshots or screen recordings.

**LVL 4 - Senior I, TTL**

Proactively collaborates with designers through every stage of a project, defining deliverables and identifying limitations or opportunities. Considers wider topics when approaching new work and measures or anticipates the need of end-users.

* collects user or client feedback on implementations and consults with designers on this feedback.
* applies progressive enhancement and graceful degradation approaches, and understands which to use in what cases.
* makes recommendations on designs to help improve build efficiency, performance, usability, and accessibility.
* is capable of setting up A/B testing tools, suggest testing scenarios, and advise on the interpretation of the testing results.
* understands how features are linked to user or client needs and the wider context, so that they make decisions with the user in mind.
* provides guidance to designers on what deliverables are required, specifying level of detail, timelines, formats, etc.
* might be able to translate tracking data or UX findings into specific recommendations for technical approach.
* able to quickly prototype changes for consideration, and demonstrate these changes in screenshots, recordings, or on calls.

**LVL 5 - Senior II**

Implements advanced designs and theming systems. Identifies and escalates opportunities to improve user experience for administrators and end users.

* able to implement complex visual designs and animations.
* translates user or client feedback of implementations into alternative design recommendations, collaborating with the design team.
* makes UI recommendations such as microinteractions or animations to enhance user experience.
* recommends improvements to existing interfaces, for example making the admin interface of existing platform easier to use.
* can work with the design team to engineer a multi-theme system and communicate the value to the client.
* is able to develop, suggest, and implement an A/B testing strategy to target set goals.

**LVL 6 - Principal, SEM**

Leads the collaborative process between the design and engineering teams. Ensures project teams are using processes that result in high-quality and robust implementations.

* works with the design team to identify opportunities to improve our ways of working.
* guides and supports engineers across Enernite and advises on approaches for project teams.
* identifies areas of weakness and makes plans for improving the skills of our team.

### DevOps (iOPS) ###

This is an elective skill. You may choose this as one of your required quota from the focused technical category. This skill is a required skill for members of our DevOps team.

Bridging traditional software engineering with the world of ops, with a focus on continuous integration/continuous delivery, automation, provisioning, monitoring, resilience and scalability.

**LVL 3 - Engineer II**

Is familiar with the tools, services and processes commonly used on projects to support the team on day-to-day tasks.

* Is comfortable pairing with others to resolve common engineering and pipeline related environment issues
* Can install and configure the tools and services most commonly used on projects, such as jenkins, nginx, php-fpm, mysql, docker, docker-compose
* Makes tool and service recommendations based on already well understood and documented architecture patterns

**LVL 4 - Senior I, TTL, SEM**

Can document and implement an end-to-end project pipeline adhering to best practice of the chosen architecture. With appropriate guidance, can implement more complex architectures and pipelines.

* Is active in providing ops insight to application architecture decisions
* Can pair with an engineer to debug and diagnose application-specific issues with ops insight
* Can decide on an appropriate architecture and CI/CD pipeline for a project based on documented patterns, but knows how and when to deviate in minor ways from these standards to satisfy client requirements.
* Is proficient with the tooling used on more complex projects such as kubernetes, helm, grpc, prometheus and other associated tools in the distributed application ecosystem.
* Has in-depth knowledge of a cloud hosting provider, especially around the services most applicable to the documented architectures eg. compute, containers, database, cache, queuing and CDN.
* Is able to make hosting recommendations from a list of vetted options.

**LVL 5 - Senior II**

Work with project teams who have non-standard requirements to plan out an appropriate architecture and pipeline.

* Can mentor and advise less senior engineers on more complex and less commonly used architectures.
* Is able to debug, diagnose and advise on more complex inter-service and network issues relating to the application.
* Can plan out architectures and pipelines where project requirements deviate greatly from existing architecture patterns, or do not match an existing pattern at all.
* Can advise on appropriate hosting providers when none of the already vetted options are appropriate.
* Is familiar with various hosting paradigms; PaaS, CaaS, SaaS, IaaS, DIY, and the associated pros and cons of each.
* Is familiar with distributed architecture concepts and options such as SOA and Microservices.

**LVL 6 - Principal, Head of DevOps**

Aware of wider industry trends and technologies, helps to establish the architectural patterns to be used by projects of varying types and complexity.

* Will consider new and upcoming technologies and how they might benefit projects and work within existing and new architectures.
* Can plan and document pipelines and architectures, of varying complexity to be used as standard across projects.
* Can facilitate a team in assessing the suitability of tools and technologies where you may have very little existing knowledge or experience.
* Is aware of developments in the industry of existing technologies and how they might impact projects and reference architectures that are utilising those technologies, for example a major version update of such technology, an older version becoming end-of-life, or of a technology being discontinued.

### Object Oriented Programming & Design Principles (iOOP) ###

This is an elective skill. You may choose this as one of your required quota from the focused technical category.

Object orientation and how to use it effectively to architect modern solutions.

**LVL 2 - Engineer I**

New to object-oriented programming.

* has a grounding in OO and is able to write simple classes and interfaces.
* understands inheritance and the different levels of scope within a class.
* has minimal exposure to, and understanding of, design patterns.

**LVL 3 - Engineer II**

Understands the fundamentals of object-oriented programming and applies them in their day-to-day work, often needing input on class design.

*is fluent in OO fundamentals and can apply them in their respective language.
*is learning SOLID principles and/or types of design pattern (behavioural, creational, structural), and is starting to incorporate them into their work.
*understands anti-patterns and the reasons why some approaches are preferred over others (e.g. composition vs inheritance).

**LVL 4 - Senior I, TTL, SEM**

Writes well-architected object-oriented code by default and helps others learn and apply good techniques.

* aware of most design patterns and uses them appropriately.
* knows SOLID principles and applies them where feasible/possible.
assists others on good design.

**LVL 5 - Senior II**

An authority for others to follow on good design patterns with significant proven experience. Understands the trade-offs and when not to apply these patterns.

* adapt at well-architected OO code, able to advise and collaborate on solutions.
* has significant experience with many design patterns and knows when to use them situationally.
* is seen as a technical authority for well-written code on the team that others will turn to.
* understands the virtues and drawbacks of using these techniques and applies them pragmatically.
* openly teaches good techniques, and intuitively understands why we adopt these approaches.

**LVL 6 - Principal**

An evangelist for object-oriented programming and design principles. Keeps Enernite's best practice up to date with industry trends through discussion and cross-project consultation.

* preaches good design, but also a pragmatic and accessible approach to multiple teams, helping manage trade-offs to quality / readability / efficiency.
* is aware of evolving architectural trends in the industry, and where they offer improvements on existing implementations.

### Performance (iPRF) ###
This is an elective skill. You may choose this as one of your required quota from the focused technical category.

The consideration of performance during development. Diagnosing and fixing performance problems in new and existing code or applications and the use of appropriate tools to assess site and application performance.

**LVL 2 - Engineer I**

Has a basic awareness of the importance of performance.

* is learning how to improve the performance of their implementations with support from more senior engineers.

**LVL 3 - Engineer II**

Is able to write efficient code, avoiding common performance issues especially within their domain.

* can use profiling tools to a basic level.
aware of caching but not necessarily able to select the best approach.
* is aware of web vitals and is broadly aware of topics in their domain that can impact these measurements.

**LVL 4 - Senior I, SEM**

Confidently handles common performance challenges through effective use of tooling, including profiling.

* can write efficient code, and understands the difference between doing so and micro-optimising
* can micro-optimise code, knows different methods to do so and which to choose situationally.
* has a good grasp of profiling tools and uses them instinctively.
* aware of different caching mediums and how to use them.
* judges when to use caching and when to optimise the code.
* understands web vitals and can define work towards achieving specific goals for these measurements.
* can identify and choose from multiple solutions for common performance issues.
* supports other team members to learn and improve their skill for performance-related work.

**LVL 5 - Senior II, TTL**

Proactively handles performance topics, guiding others' technical approaches and educates clients on the impact of good performance. Sets project-level goals for performance and judges when to stop investing in performance.

* is keenly aware of performance when peer reviewing.
* has a proactive approach to caching for performance.
* has a full end-to-end knowledge of the impact of optimisations.
* knows how to leverage multiple performance analysis tools.
* works with other senior members to set goals or work to improve performance.
* knows when to stop optimising consdiering diminishing returns and project constraints.
* can guide clients on the practical value of tracking web vitals and how it impacts their end users to help prioritise work related to performance.

**LVL 6 - Principal**

* Defines and promotes our best practice across multiple teams. Is a technical authority for performance and can advise on improvements for any context.

* evangelises about performance and promotes this across projects, impacting design decisions and helping teams make trade-off decisions.
* drives the performance audit strategy for new and existing projects.
* advises teams on caching strategies at a high level.
* is able to advise on performance strategy and improvements even in unfamiliar contexts.
* recommends training topics to improve our competency for performance-related topics.

### Security and Data Handling (iSEC) ###

This is an elective skill. You may choose this as one of your required quota from the focused technical category.

Understands fundamental security implications, common attack vectors, and how to handle sensitive data carefully.

**LVL 3 - Engineer II**

Aware of common features that have security considerations, and works with more senior members to meet security requirements.

* basic knowledge of avoiding vulnerabilities whilst developing applications.
* relies on the constructs within a framework to abstract the security implementation details and understands what's not handled by default and needs to be considered separately.
* knows how to access/transmit sensitive data safely.

**LVL 4 - Senior I, TTL, SEM**

Considers security implications as part of day-to-day work. Uses good data handling practices and encourages others to do so.

* possesses advanced knowledge of common attack vectors and how to address them, such as XSS, CSRF, login protection, insecure object serialisation etc.
* has practical knowledge of how to make a project GDPR compliant, and guides their team and client to handle data securely.
* addresses issues raised by a security audit.

**LVL 5 - Senior II**

Owns and looks to improve our security and data handling approaches on their project. Actively guiding others to be compliant through implementation, defining work for others, and education.

* is aware of tools and approaches to ensure applications and servers are secure against possible exploits.
* follows the security checklist to secure applications and servers, knows how to implement all points within the checklist.
* conducts security audits using our security checklist as a guide, and sets a list of prioritised tasks from findings.
* contributes to and helps maintain the security checklist, keeping it up-to-date with new vulnerabilities and also knows who to implement all the points.
* understands multiple levels of PCI compliance and can advise projects on the most appropriate route for compliance.
* understands and knows how to implement security headers for a variety of projects.

**LVL 6 - Principal**

Leads our approach across Enernite, teaching and guiding engineers and clients on security topics.

* is able to secure a complete web server including the operating system and application layer.
* drives the security audit strategy for new and existing projects.
* is able to describe and implement a number of cryptographic attacks such as length extension attack and adaptive chosen-cipher attack.
* communicates new security concerns and how to handle them, and manages a plan for teams to implement mitigations for client projects.
