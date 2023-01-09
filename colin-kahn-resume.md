# Colin Kahn

**[GitHub](https://github.com/colinkahn) • info@colinkahn.com • (626) 590 2323**

## Work History

### Mobot - April 2022 to Present

#### Senior Backend Software Developer

Mobot gives customers confidence in their mobile software releases by testing
on real devices using robots. I work on their Clojure backend and ClojureScript
frontend used by QA operators to run tests as well as display reports to
customers.

Responsibilities include:

- Extended OAuth2 login implementation to support Microsoft accounts
- Developed a back-testing framework to exercise image assessment changes
    - Technologies used: Clojure, Python, Docker, Google Cloud Run
- Customer facing charting for test run reports
    - Technologies used: ClojureScript, Reagent, Re-Frame, Oz (vega)
- Proof of concept for updating and viewing changes to their test plans
    - Backwards compatible implementation
    - Generative testing creating successive versions, checking their validity
    - Technologies used: Clojure, Reitit, Ring, Postgres, HugSQL, clojure.test.check

### Parkside Securities - May 2019 to April 2022

#### Lead Developer

Parkside Securities was developing a scalable financial platform for trading,
written in Clojure using Kafka and Datomic. When I first joined, I worked
mainly on their internal broker dealer operations frontend application doing
both development and design. I soon shifted into a full stack role, doing
development on their backend microservices as well. During that time I began an
initiative to write stateful model-based property based tests (PBTs) for the
most critical components of the system. Eventually a specific team was broken
out for test automation, which I led.


Responsibilities included:

- Developed product features for backend microservices
    - Technologies used: Clojure, Kafka, Datomic, GraphQL, QuickFIXJ
- Developed and designed the internal broker dealer operations frontend application
    - Technologies used: ClojureScript, re-frame, Storybook, Ant design system
    - Worked with product to create mocks in Storybook for fast iteration with stakeholders
    - Utilized feature flags for short cycle time
    - Abstracted common state machines to simplify development for other engineers
- Lead Developer for the test automation team
    - Developed an integration testing framework to run multiple services connected via the Kafka TestDriver to exercise application logic quickly without deploys
    - Developed a suite of stateful model-based PBTs in our integration test framework focused on finding bugs with order placement and execution code 
    - Extended integration test PBTs to run end-to-end, finding race conditions in k8s deployed services
    - Developed a market emulator implementing the FIX spec as a purely functional Clojure library to simulate responses from the market during testing
    - Managed the company's CodeScene account to provide valuable insights into code health, refactoring targets and team delivery efficiency

### JPL - December 2018 to May 2019

#### Frontend Developer

Contract work for the Enterprise Business Information Services team at the JPL
lab in Pasadena, CA. Helped refactor an Angular 7 application to use NgRx Store
for state management, and then implemented many additional features in a short
period of time.

Responsibilities included:

- Angular 7 application development
    - Used NgRx Store for state management
    - Practiced TDD for unit testing, achieving high code coverage
    - Used Storybook for component development and fast iteration with designers

### Disney Studio Technologies - April 2016 to January 2018

#### Frontend Developer

A project spearheaded by the User Experience team at Disney Studio
Technologies, Hex is a design language with Angular 2+ and CSS implementations.
I was brought onto the project to build their component libraries from the
ground up. Working closely with UX and visual designers to create a product
that was adopted by over half a dozen teams for production applications.

Responsibilities included:

- Created 60+ components following UX best practices with a visual style unique to Disney
    - Refined design patterns with other team members to create a consistent, development-ready, system
    - Implemented, tested and version controlled the components
        - Technologies used: Angular 2+, RxJS, TypeScript
    - Created documentation for components including live demos and code samples 
    - Created sample applications showcasing use cases for the components
- Developed a standalone CSS library which other framework implementations could use
    - Structured the library using the ITCSS architecture and advocated for its adoption for all projects - [Slides](http://bit.ly/2x1gVaO)
    - Worked with QA to develop a framework to visually compare CSS styles

### Ubiquiti Networks - September 2013 to April 2016

#### Senior Frontend Developer

The main project I worked on was to help develop a flawless user experience for
Ubiquiti Networks' disruptive wireless hardware line, AirCRM. The platform was
developed as a cloud connected interface to allow remote management of a
wireless internet service provider's entire network of devices. The project
eventually supported on-premise installation, seamlessly adapting the same
frontend code to the new backend.

Responsibilities included:

- Helped the team acheive frontend best practices for new projects
    - Shifted the team from using Backbone to AngularJS
        - Advocated for componentization to improve efficiency and reuse of frontend code
    - Developed and helped maintain a CSS style guide for use across several teams and projects
        - Coordinated development workshops to strengthen the teams CSS skills
- Lead Developer for the U CRM Control monitoring software
    - Developed dashboards for monitoring and managing hardware networking devices from the cloud as well as adapting it for on-premise use
    - Maintained high code quality standards with code reviews, end-to-end and unit testing.
    - Technologies used: Git, Karma, Protractor
