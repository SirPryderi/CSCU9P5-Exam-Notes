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

All SDLCs share these steps:
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

### Feasibility Study
  - Can the users needs be satisfied with the current technology?
  - Is the project going to be cost-effective?

### Requirements _Elicitation_ and _Analysis_
#### Elicitation
  - Extracting the requirements
  - There are two approaches:
    - Viewpoints
      - A way of classifying _stakeholders_ and other sources of requirements
    - Scenarios
      - Real-life examples of how the system will be used
      - Related to UML use-cases

#### Analysis
  - Discover problems and inconsistencies in the requirements
  - Requirements change must be negotiated with the client

### Requirements Specification
  - _Viewpoints_ and _Scenarios_ are represented in a structured way
  - Improves the understanding of the requirements
  - Must support the development of the systems
  - Must also be understandable by the stakeholders
  - Can be _formal_, _informal_ and _semi-formal_

### Requirements Validation
 - Requirements reviews
    - Systematic manual checking
    - Stakeholders should be involved
  - Prototyping
    - Check requirements on the prototype
    - Stakeholders can try out the prototype
  - Test-case Generation
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
### The Process
![Risk Management Process][RiskManagementProcess]
- Risk identification
  - Identify project, product and business risks
  - Can be a team activity or assigned to the project manager
  - Common risks:
    - Technology risks
    - People risks
    - Organisational risks
    - Requirements risks
    - Estimation risks
- Risk analysis
  - Assess the likelihood, seriousness, and consequences of each risk
- Risk planning
  - Draw up plans to avoid or minimise the effects of the risk
    - Avoidance strategies
    - Minimisation strategies
    - Contingency plans
- Risk monitoring
  - Monitor the risks throughout the project to see if probability and/or consequences have changed


## Teamwork
### Why working in a team?
- Accomplish projects an individual cannot
- Effective brainstorming (more point of views)
- Detect flaws in solution
- Build a workplace community

### Why **not** working in a **large** team?
- Adds line of communication equals to `n × (n - 1) ÷ 2` where `n` is the team size
- Large teams have too much overhead and are hardly effective
- The approximate optimal range seems to be from `3` to `7` members
- **Meredith Belbin** said:
> When effective decision-making is required, three selected teams of four are better than one group of twelve. ... small teams deliberating separately can quickly reach significant decisions.

### Why **not** adding more people to a team?
- More communication lines
- Training cost/time
- Lower productivity
- **Brook's Law**:
> Adding more people to a late project makes it later

### Team Organisation Options
- Hierarchical
- Non-hierarchical
  - Egoless Team
- Peer Organisation
- Project-based Organisation

![Hierarchical Organisation][HierarchicalOrganisation]
![Egoless Organisation][EgolessTeam]
![Peer Organisation][PeerOrganisation]


### Team Dynamics
#### **Tuckermann** and **Jensen** (1965) Model
A commonly accepted model of how teams form and become productive is due to **Tuckermann and Jensen**, with their four stages model.
- **Forming** ─ The initial stage when the individual groups try to determine the purpose of the group and what role they will play
- **Storming** ─ A conflict-filled stage in which the individuals try to form a group by resolving differences in goals and perspectives. The individuals struggle for status and power within the team
- **Norming** ─ Having come to a common understanding of the goals and functioning of the team, the conflict disappears and members focus on the work at hand
- **Performing** ─ The team has developed a clear identity with loyal team members who have a clear understanding of how the team operates and how they will interact as individuals

#### **Belbin**'s Roles
Meredith Belbin identified nine **team roles**. These roles are:
- **Plant** ─ Generates ideas and solves difficult problems.
- **Coordinator** ─ Clarify goals and delegates tasks effectively.
- **Monitor**/**Evaluator** ─ Sees all options and judges accurately.
- **Implementer** ─ Turns idea into actions and organises work that needs to be done.
- **Completer**/**Finisher** ─ Searches out errors. Polishes and perfects.
- **Resource Investigator** ─ Explores opportunities and develops contacts.
- **Shaper** ─ Has the drive and courage to overcome obstacles.
- **Teamworker** ─ Listens and averts friction.
- **Specialist** ─They provide specialistic knowledge and skills.


Read more [here](http://www.belbin.com/media/1486/team-role-summary-descriptions-2016.pdf).

# Legal, Social, Ethical and Professional Issues
## Professional issues
A profession operates on two levels:
- **Practitioner Level** ─ professionals, knowledge, professional practice.
- **Infrastructure Level** ─ Initial professional education, accreditation, skills, development, certification, professional development, code of ethics, professional society.

### Basic technical competence
A professional computing scientist must have:
- **Firm knowledge** in the crucial areas of the field.
- **In-depth knowledge** in one or more other areas of the discipline, depending upon the person's particular **area of practice**.

A well-educated computing scientist should be able to apply fundamental concepts and techniques of:
- **Computation**
- **Algorithms**
- **Computer Design**

They must also **systematically improve** their professional knowledge and skills.

### Professional Bodies
In order to be a professional you need to be part of of a professional body.

Professional bodies for IT are not yet well officially established, but the most important are:

- UK
  - **IET** ─ Institution of Engineering Technology
  - **BCS** ─ The Chartered Institute for IT


- USA
  - **ACM** ─ Association for Computing Machinery
  - **IEEE-CS** ─ Institution of Electrical and Electronic Engineers - Computer Society

### Why is it important to be a Professional
- Recognition by
  - Peers
  - Clients
  - External Bodies
  - The Public
- Continuing professional development
  - Preservation of qualification standards
- Lobbying
- Contracts and networking
- _Closed-shop_ effects
- Access to learned society activities
- Financial and other services
- Professional register

### Professional Codes
Professional Code are **formal expression** of the expectations and requirements a professional organisation has for its members.

## Legal issues
### IT Related Regulations
#### 1990 ─ Computer Misuse Act
The UK **Computer Misuse Act** came into force in **1990**. Three new criminal offences were introduced.
1. **Unauthorised Access** ─ accessing (or attempting to) private computer material. This covers simple hacking and is an offence if if thing is changed.
2. **Unauthorised Access for further offence** ─ This cover situations for example where the material obtained was used to access a person's bank account.
3. **Unauthorised Modification** ─ modifying private computer material. This covers issues such as planting viruses, malicious deletion of files or altering bank account details.

One area it is deemed to be ineffective is **denial-of-service** (DoS) attacks, where a target computer is saturated with requests and cannot operate properly, since no unauthorised access is performed. This issue is addressed by the **Police and Justice Act**.

#### 1984/1998 ─ Data Protection Act
Data Protection Act states that **personal data** must be:
1. Processed fairly and lawfully and, in particular, shall not be processed unless:
 - at least one of the conditions in Schedule 2 is met, and
 - in the case of sensitive personal data, at least one of the conditions in Schedule 3 is also met.
2. Obtained only for one or more specified and lawful purposes, and shall not be further processed in any manner incompatible with that purpose or those purposes.
3. Adequate, relevant and not excessive in relation to the purpose or purposes for which they are processed.
4. Accurate and, where necessary, kept up to date.
5. **Not** be kept for longer than is necessary for their purpose .
6. Processed in accordance with the rights of data subjects (individuals).
7. Protected with appropriate technical and organisational measures, against unauthorised or unlawful processing and against accidental loss or destruction, or damage.
8. **Not** transferred to a country or territory outside the European Economic Area unless that country or territory ensures an adequate level of protection for the rights and freedoms of data subjects in relation to the processing of personal data.

#### 2000 ─ Freedom of Information Act
Grants **the public** access to information held by **public authorities**.
In **conflict** with the **Data Protection Act**.

#### 2000 ─ Regulation of Investigatory Powers Act (RIP)
Empowers the **government** to:
- Demand that an **ISP** provides access to a customer's **communications** in secret, i.e. to divulge the website you have visited and the email you have sent.
- Demand your **decryption keys** so that they can access any encrypted data on your computer
- Further activities

#### 2002 ─ Cyber Security Act
Allows **electronic surveillance**, such as internet and telephone tapping, without a **court order** in the US.

#### 2006 ─ Police and Justice Act
Among many other things, this act amends the **Computer Misuse Act** with the creation of certain offences including unauthorised acts with intent to impair the operation of a computer, such as a **DoS** attack.
It also made illegal do produce **hacking tools**, even for legitimate use, such as **penetration testing**.

### Ethical Issues and Conflicts
There are conflicts between the **RIP** Act and the **Data Protection Act**, since one allows the government to freely access personal data, while the second enforces the security of the same personal data.

Is there an **ethical** difference between:
  - getting a **warrant** to gather personal data of a **suspect** and
  - gathering information on **everybody** **pre-emptively**?


## Ethical issues
### What is Ethics?
Ethics is the **Systematic study of morals**.
It deals with the uncertainties and conflicts of opinion over matters of what is right and wrong conduct ethical conduct, or doing the right thing. or ding the right thing.

Reasons for following an ethical could include:
- **Trust** ─ an individual known to work within a consistent ethical framework is one who can be relied upon.
- **Duty** ─ because it's the right thing to do.
- **Security** ─ being aware of the consequences of your actions can guard against unexpected outcomes.
- **Comfort** ─ peace of mind.
- **Fear** ─ there may be sanctions imposed on those who act unethically.

An action that is **unethical**, although not necessarily **illegal**.

[BoehmSpiralModel]: https://upload.wikimedia.org/wikipedia/commons/thumb/e/ec/Spiral_model_%28Boehm%2C_1988%29.svg/1200px-Spiral_model_%28Boehm%2C_1988%29.svg.png
[WaterfallModel]: http://duncanpierce.org/files/images/Waterfall_model.png
[RequirementsEngineeringProcess]: https://cdn-images-1.medium.com/max/1600/1*g9_1K3puHH37UoqP7d3M_g.png
[RiskManagementProcess]: RiskManagementProcess.svg
[HierarchicalOrganisation]: HierarchicalOrganisation.svg
[EgolessTeam]: EgolessTeam.png
[PeerOrganisation]: PeerOrganisation.png
