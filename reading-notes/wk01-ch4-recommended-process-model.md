# Chapter 4: Recommended Process Mode
## Quick Look
- Every project needs a road map for the longterm life of the project
- Software development can easily become chaotic without the control and organization offered by a defined process. However, a project can be over organized to the detriment of the actual project
- General weakness of prescriptive software life-cycle approaches:
    1. It is risky to use a linear process model without ample feedback.
    2. It is never possible nor desirable to plan big up-fron requirement gathering.
    3. Up-front requirements gathering may not reduce costs or prevent time slippage.
    4. Appropriate project management is integral to software development.
    5. Documents should evolve with the software and should not delay the start of construction.
    6. Involve stakeholders early and frequently in the development process.
    7. Testers need to become involved in the process prior to software construction.
- Key characteristics of agile process model are:
    - Prototypes created are designed to be extended in future software increments.
    - Stakeholders are involved throughout the development process.
    - Documentation requirements are lightweight, and documentation should evolve along with the software.
    - Testing is planned and executed early.

## 4.1 Requirements Definition
- Best practices of Agile Development:
    1. Encourage active stakeholder participation by matching their availability and valuing their input.
    2. Use simple models to reduce barriers to participation.
    3. Take time to explain your requirement representation techniques before using them.
    4. Adopt stakeholder terminology and avoid technical jargon.
    5. Think about the big picture of the project then narrow down the details.
    6. Refine requirement details as they are worked on.
    7. Treat the list of features as a prioritized list and work from the top down
    8. Collaborate with stakeholders in a way that is benefial to the next prototype.
    9. Question the need to maintain models and documents that will not be needed in the future.
    10. Make sure you have a management support to ensure stakeholder and resource availability.
- It is important to recognize that:
    1. It is impossible for stakeholders to describe an entire system before seeing the working software.
    2. It is difficult for stakeholders to describe quality requirements before seeing it in action.
    3. Requirements will be added/removed/changed during the development process.
- Prototypes are tangible realizations of project plans for stakeholders to describe their desired changes. 
- Prototypes add volatility to the project requirements to achieve a better aligned project at the cost of the potential to waste time with discarded prototypes.

## 4.2 Preliminary Architectural Design
- Key elements to agile architectural design:
    1. Focus on key quality attributes and incorporate them into prototypes as they are constructed.
    2. When planning prototypes, remember that successful software products combine customer-viable features and the infrasture to enable them.
    3. Recognize that agile architecture enabled code maintainability and evolvability if sufficient attention is paid to architectural decisions and related quality issues.
    4. Continuously managing and synchronizing dependencies between functional and architectural requirements is needed to ensure the evolving project is ready for future increments.

## 4.3 Resource Estimation
- Early estimates run the risk of being incorrect due to evolving project requirements and pitfalls. Early estimates should be changed frequently as development eases out of the early phase.
- Methods to plan better estimates:
    1. Use historic data and work more as a team to develop an estimate of how many days it will take to complete a task in the early phases.
    2. Loosely organize tasks into set for each sprint to complete a prototype.
    3. Sum the number of days to complete each sprint to estimate the duration of the total project.
    4. Revise the estimate as requirements are added and prototypes are delivered and accepted by the stakeholders.
- Doubling the number of developers almost never cuts development time in half.

## 4.4 First Prototype Construction
1. Transition from paper prototype to software design:
    - _paper prototype_: inexpensive prototype to get ideas across properly
2. Prototype a user interface:
    - Good to get early feedback from stakeholders
3. Create a virtual prototype
4. Add input and output to your prototype
    - Beginning of algorithms are implemented.
    - Provided feedback source for UX
5. Engineer your algorithms
    - Beginning of coding
6. Test your prototype
7. Prototype with deployment in mind

## 4.5 Prototype Evaluation
1. Provide scaffolding when asking for prototype feedback
    - Users are often reluctant to tell developers they hate the product
    - Useful to ask "I like, I wish, What if" for feedback
2. Test your prototype on the right people
    - Only testing with developers is a bad idea
    - Try to test on the user demographic
3. Ask the right questions
    - Feedback drives the prototype process
4. Be neutral when presenting alternatives to users
    - _Egoless Programming_: Philosophy to get the best version of a product to the user by determining whether to fix or adbandon aspects that are not working.
5. Adapt while testing
    - Be flexible by being willing to alter plans, make quick changes to the prototype, or restarting the testing.
6. Allow the user to contribute ideas
    - Allow the user's feedback to be integrated into the product

## 4.6 Go, No-Go Decision
- After the prototype is evaluated, the project stakeholders will determine whether to continue with the product's development.

## 4.7 Prototype Evolution
- After the prototype is developed, feedback and data from the evaluation is considered for the next prototype.
### 4.7.1 New Prototype Scope
- Scope should be determined through either:
    1. Selecting features to develop within the time allocated to a sprint
    2. Allocating sufficient time to implement the features needed to satisfy the goals set by the developers with stakeholder input.

### 4.7.2 Constructing New Prototypes
- Developers must make design decisions that will make software prototypes more easily extensible in the future.
- Documentation must also be made to quickly understand the product.

### 4.7.3 Testing New Prototypes
- _Regression Testing_: Feature testing that previously developed software's functionality is resulting in the same output

## 4.8 Prototype Release
- When testing a release candidate, functional and nonfunctional tests should be repeated.
- Testing does not prove a product is bug free, but that it is only passing its test cases
- A bug reporting system is important to ensure an agile workflow from developer and customer feedback
- Fixing a bug should be organized from its level of impact on the feature and/or product as a whole

# 4.9 Maintain Release Software
- _Maintenance_: Activities needed to keep software operational after initial release
- _Corrective maintenance_: The reactive modification of software to repair problems discovered after the software has been delivered to a customer’s end user.
- _Adaptive Maintenance_: Reactive modification of software to the software usable in a changing end-user environment.
- _Perfective Maintenance_: Proactive modification to provide new user features, better program code structure, or improved documentation
- _Preventive Maintenance_: Proactive modification of the software after delivery to detect and correct product faults before they are discovered by users in the field
- Reactive maintenance is also referred to as _firefighting_