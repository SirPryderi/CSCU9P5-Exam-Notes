# System and Software Engineering

## Why Software Engineering?
- Building large systems
- Understanding requirements
- Modelling the problem
    - Real world
      - Environment where the system operates
    - Problem domain
      - Concepts from the real world relevant to the requirements
    - Solution domain
      - Concepts from the problem domain relevant to the solution
- Dividing the problem

## Software Development Life Cycles

All Software development life cycles share these steps:
  - Requirements
    - Understand what the the client or the users want
    - Often they do not know what they want
    - Often the clients are not the end users
    - Build early prototypes to better understand the user requirements
  - Analysis
    - Identify what is going to be implemented
    - Identify the major components of the system
  - Design
    - Identify major components
    - Decompose major components into subsystems
    - Interface major components with subsystems
    - Identify new components to bridge the problem domain and the solution domain
  - Implementation
    - Code the components devised in the design phase
    - Integration of the components
    - Deploy the new system
  - Testing
    - Check that a component acts according to the requirements
    - Check if the system matches the requirements specifications
    - Check if the system meets the clients' expectations
    - Check if the system meets the users' expectations
  - Maintenance
    - Solve any issue that arises
    - Add new features if required

## The Waterfall Methodology
![Waterfall Model][WaterfallModel]

Inherited from the real world engineering, it follows the steps mentioned above, assuming that every previous step has been completed with absolute success, but this is almost never the case in Software Engineering. It is rarely effective in real life.

## Boehm's Spiral Model
![Boehm's Spiral Model][BoehmSpiralModel]

Boehm's model is an risk-driven model that integrates risk management and incremental model. It tries to overcome the issues with the Waterfall model.


# Requirements Capture and Analysis
## Requirements Engineering
Requirements engineering is
- Understand what services are required
- Identify the constraints on the system

## System Identification
- Purpose (What is the main function of the system?)
- Scope (What's included in the system?)
- Boundary (What is inside, what is outside?)
- Context (What is the environment of the system?)

## Types of Requirements Engineering
- Greenfield Engineering
  - Building a new system from scratch
  - Requirements from end-users and/or clients
- Re-engineering
  - Redesign an rebuild an existing system
  - Requirements can be extracted from previous users
- Interface Engineering
  - Interfaces an old system to a new environment

## Types of requirements
- Functional requirements
  - Describe the interactions between the system and its environment
- Non-functional requirements
  - User visible aspects of the system, not directly related to the functional behaviour
- Constraints
  - Imposed by the client or the environment of the system

## Requirements Engineering Process
![Requirements Engineering Process][RequirementsEngineeringProcess]
- Feasibility Study
  - Can the users needs be satisfied with the current technology?
  - Is the project going to be cost-effective?
- Requirements _Elicitation_ and _Analysis_
  - Elicitation
    - Extracting the requirements
    - There are two approaches:
      - Viewpoints
        - A way of classifying _stakeholders_ and other sources of requirements
      - Scenarios
        - Real-life examples of how the system will be used
        - Related to UML use-cases
  - Analysis
    - Discover problems and inconsistencies in the requirements
    - Requirements change must be negotiated with the client
- Requirements Specification
  - _Viewpoints_ and _Scenarios_ are represented in a structured way
  - Improves the understanding of the requirements
  - Must support the development of the systems
  - Must also be understandable by the stakeholders
  - Can be _formal_, _informal_ and _semi-formal_
- Requirements Validation
  - Requirements reviews
    - Systematic manual checking
    - Stakeholders should be involved
  - Prototyping
    - Check requirements on the prototype
    - Stakeholders can try out the prototype
  Test-case Generation
    - Develop tests for the requirements
    - Can expose untestable requirements
    - All requirements should be tested, although some can be hard to test, such as:
      - System Requirements
        - performance
        - usability
      - Exclusive requirements
        - requirements that forbids a specific behaviour
      - Some non-functional requirements
        - reliability requirements


# Project management, Risk Management and Teamwork
## Project Management
Makes sure that the software is:
- delivered in time
- in accordance with the requirements

It is require because:
- budged limitation
- time limitation

There are many difference between a software project and a real world engineering project such as a building. For instance, the final product is **intangible**, it has a greater deal of **flexibility**, and it has no fixed **standards**.


Some of the activities carried out during software project management include:
- Proposal writing
- Project planning and scheduling
- Project costing
- Personnel selection and evaluation
- Project monitoring and reviews
- Report writing and presentations

### Software Project Planning
The project plan may address aspects of the **project design** such as:
- Quality plan
- Validation plan
- Configuration management plan
- Maintenance plan
- Staff development plan

But also aspects of the **development process**:
- Introduction
- Project organisation
- Risk analysis
- Hardware/Software
- Work breakdown
- Project schedule
- Monitoring and reporting mechanisms

### Road Map for Project management
1. Understand the project content
2. Identify development process
  - Methods, tools, languages, documentation and support
3. Determine organisational structure
  - organisational elements involved
4. Identify managerial process
  - Responsibilities of the participants
5. Develop schedule
  - Times at which the work portions are to be performed
6. Develop staffing plan
7. Begin risk management
8. Identify documents to be produced
9. Begin the process
  - On-going monitoring and reviewing

### Project scheduling
Project scheduling aims at:
- Splitting the project into **tasks** and estimate **time** and **resources** required to complete each task
- Organise tasks **concurrently** to make optimal use of the **workforce**
- Minimise the task **dependencies** to avoid delay

Some of the schemes that can be used for project scheduling are:
- Activity network
- Gantt Chart

#### Functions, Activities, and Tasks chart
- Functions
  - Activities that span the duration of the project
- Activities
  - Major units of work with precise dates
  - Consists in smaller activities or tasks
  - Culminates in a **milestone**
- Tasks
  - Smaller units of work
  - Easy to plan and track
  - Large enough to avoid micromanagement


- Milestones
  - Internal checkpoints
  - Scheduled event used to measure progress within the process
  - They may produce a **baseline**
- Baselines
  - Formally reviewed work product
  - Change requires formal procedures
  - A fixed point to work on from

## Risk Management
## Teamwork

# Legal, Social, Ethical and Professional Issues


[BoehmSpiralModel]: https://upload.wikimedia.org/wikipedia/commons/thumb/e/ec/Spiral_model_%28Boehm%2C_1988%29.svg/1200px-Spiral_model_%28Boehm%2C_1988%29.svg.png
[WaterfallModel]: http://duncanpierce.org/files/images/Waterfall_model.png
[RequirementsEngineeringProcess]: https://cdn-images-1.medium.com/max/1600/1*g9_1K3puHH37UoqP7d3M_g.png
