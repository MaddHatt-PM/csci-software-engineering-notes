# CHAPTER 1: Software and Software Engineering
## 1.1 The Nature of Software
- _Software_: 1) Instructions that provide desired features, function, and performance. 2) Data structures that enable the programs to manipulate information. 3) Information in both hard copy and virtual forms that describes the operation and use of programs.
- Software does not "wear out" physically over time in the way that hardware degrades over time. In theory, software should not fail in the long run. Software degrades due to change, either in the program itself or its environment.

### 1.2 Software Application Domains
- _System Software_: Programs that service other programs. ie: File management utilities, editors, OS, networking software
- _Application Software_: Stand-along programs that solve a business need
- _Engineering/Scientific Software_: Data science programs that process, simulate, and/or create data. ie:  Car crash simulators, consumer spending trackers
- _Embedded Software_: Software that runs in limited environments. IE: Fuel controllers for a car
- _Product-line Software_: Software composed of reusable components for limited or mass market purposes
- _Web/Mobile Applications_: Self explanatory
- _Artificial Intelligence Software_: Self explanatory

### 1.3 Legacy Software
- _Legacy Code_: Code that has declined in usage or must be re-architected to become relevant again.

## 1.2 Defining the Discipline
- _Software Engineering_: (IEEE) The application of a systematic, disciplined, quantifiable approach to the development, operation, and maintenance of software; that is, the application of engineering to software.
- Software engineering layer:
    4. Tools: Automated or semi-automated support for the process and methods.
    3. Methods: Technical how-to's for building software. Soft and Hard skills.
    2. Process: A framework that must be established for effective delivery of software engineering technology.
    1. A Quality Focus: Organization commitment to quality

## 1.3 The Software Process
- _process_: a collection of activities, actions, and tasks that are performed to create a product.
- _activity_: the striving of a broad objective
- _action_: a set of tasks to accomplish a major goal
- _task_: a small, well-defined objective that produces a tangible outcome

### 1.3.1 The Process Framework
- _Process Framework_: Project Management in a meta sense. The identification of tasks and issues
    - Generic Process Framework:
        1. Communication: Identification and collaboration to understand an objective
        2. Planning: Describing of the required technical tasks, risks, resources, products-to-be-created, and work schedule
        3. Modeling: Additional planning that involves the specific details and parts
        4. Construction: Includes the generation and the testing of code
        5. Deployment: The delivery of the software (as whole or in pieces) and the recieving of feedback based on the evaluation

### 1.3.2 Umbrella Activities
- Software project tracking and control
- Risk management
- Software quality assurance
- Technical reviews
- Measurement
- Software configuration management
- Reusability management
- Work product preparation and production

### 1.3.3 Process Adaption
- When transitioning from one project to another, similar processes should be adapted to benefit the new project

## 1.4 Software Engineering Practice
## 1.4.1 The Essence of Practice
- Typical Plan
    - Understand the problem
    - Plan the solution
    - Carry out the plan
    - Examine the results

## 1.4.2 General Principle
1. The Reason It All Exists - Bring value to its users
2. Keep It Simple Stupid
3. Maintain the Vision
4. What you Produce, Others Will Consume
5. Be open to the future
6. Pla the ahead for reuse
7. Think!

## 1.5 How It All Starts
- Software developments with figuring a solution to a program

### ------------------------------------------------------------------------------------

# Chapter 2: Process Models
## 2.1 A Generic Process Model
- Processes should flow from one step to another

## 2.2 Defining a Framework Activity
- Communicating with the stakeholder(s)

## 2.3 Identifying a Task Set
- Self explanatory

## 2.4 Process Assessment and Improvement
- The usage of metrics to refine future processes

## 2.5 Prescriptive Process Models
### 2.5.1 The Waterfall Model
- Linear approach to software development
- Once its released, it is difficult to fix any errors

### 2.5.2 Protyping Process Model
- Passing back of iterations of a product/feature to determine if it is sufficient
- Useful when the requirements are not fully realized at the start
- Cons:
    - Stakeholders may have incorrect ideas of the end product by seeing the inprogress version
    - The rush to a presentable state may cause bad short-term decisions to made
 
### 2.5.3 Evolutionary Process Model (Spiral Model)
- Sequential waterfall method
- Suitable for long-life products as it extends to after the product release
- May be difficult to convince customers of project stability

### 2.5.4 Unified Process Model
- Modern approach to software developments
- More incremental like the Spiral Model
- Highlights customer feedback more
- _UML_: Unified Modeling Language: Notation to quickly diagram software processes
- Steps (Multiple steps can be conducted at the same time (the core benefit of UP)):
    - Inception: communication and planning
    - Elaboration: modification of plans and modeling
    - Construction: most construction and testing
    - Transition: later construction and deployment
    - Release: release and software increment

## 2.6 Product and Process
- "If the process is bad, the product will be bad"
- Waterfall Method:
    - Pros:
        - Easy to understand and plan
        - Works for well-understood small projects
        - Analysis and testing are straightforward
    - Cons:
        - Does not accommodate change well
        - Testing occurs late in the process
        - Customer approval is at the end
- Prototyping Method:
    - Pros:
        - There is a reduced impact of requirement changes
        - The customer is involved early and often
        - It works well for small projects
        - There is a reduced likelihood of product rejection
    - Cons:
        - Customer involvement may cause delays
        - There may be temptation to release a prototype
        - Work is lost in a throwawy prototype
        - It is hard to plan and manage
- Spiral Pros
    - Pros:
        - There is continuous customer involvement
        - Development risks are managed
        - It is suitable for large, complex projects
        - It works well for extensible products
    - Cons: 
        - Risk analysis failures can doom the project
        - The project may be hard to manage
        - It requires an expert development team
- Unified Process:
    - Pros:
        - Quality documentation is emphasized
        - There is continuous customer involvement
        - It accommodates requirement changes
        - It works well for maintenance projects
    - Cons:
        - Use cases are not always precise
        - It has tricky software increment integration
        - Overlapping phases can cause problems
        - It requires an expert development team.

# Chapter 3: Agility and Process (Agile Development)
## Quick Look:
- Agile software engineering is a combination of philosophy and development guidelnes
- Encourages customer satisfaction and early incremental delivery of software
- Emphasizes small motivated project teams, informal methods, simplicity
- Guidelines value delivery over analysis and design

## 3.1 What is Agility?
- A response to change and the encouragement of simple, to-the-point communication between groupmembers and stakeholders
- For agile development to work, it is required that the process be designed to adapt and streamline taks, plan with an understanding the fluidity of the process, eliminate all but the most essential work products, keep the work products simple, and to emphasize rapid incremental delivery to the customer in regards to it's product category and environment

## 3.2 Agility and the Cost of Change
- Typically factoring in change farther along the product's development period, results in a nonlinear increase in cost
- It is argued that Agile development flattens this cost curve, at least to a degree

## 3.3 What is the Agile Process
- Agile development attempts to address the following concerns:
    1. The difficulty of which software requirements will emerge, persist, or change during the development process
    2. Design and construction are an linked iterative activity. It is difficult to predict how much design is necessary before construction is ready to begin
    3. Analysis, design, construction, and testing are not as predictable from a planning point of view
- How do we create a process that can manage _unpredictablity_?
- Software increments must be delivery in short time periods to allow rapid feedback and enable an iterative approach
### 3.3.1 Agility Principles
1. Our highest priority is to satisfy the customer through early and continous delivery of software.
2. Welcome changing requirements as a positive.
3. Delivery software frequently.
4. Business people and developers must work together daily throughout the project.
5. Build projects around motivated individuals. Provide an environment that facilitates that feeling.
6. The most efficient and effective method communicating information is face-to-face conversation.
7. Working software is the primary measure of progress.
8. Sponsor, developers, and users should be able to maintain a constant pace indefinitely.
9. Continous attention to technical excellence and good design enhances agility.
10. Simplicty is essential. The art of maximizing the amount of work not done.
11. The best architectures, requirements, and designes emerge from self-organizing teams.
12. At regular intervals, the team should reflect on how to become more effective. This reflection should be used to tune and adjust the process.

### 3.3.2 The Politics of Agile Development
- The disagreement over Agile Development, stems from how to best accomplish agility in software development.
- The is no single defined strategy that can be applied to the uniqueness of each development team without adjustment.

## 3.4 Scrum
- _Scrum_: A popular agile development method that focuses on short _sprints_ of work
- _Sprint_: A short burst of work in a restricted length of time with defined goals. Time limit varies on the difficulty of the task. Typically 3-4 weeks.

### 3.4.1 Scrum Teams and Artifacts
- Scrum Team consists of the Product Owner, Scrum Master and a small development team (typically 3-6 people)
- Scrum Artifacts:
    - Product Backlog:
        - Prioritized List of product requirements or features that provide value for the customer.
        - Never complete while the product is evolving.
        - The backlog can persist even after the products initial release.
        - Multiple teams can work from the same Product Backlog.
    - Sprint backlog:
        - Subset of Product Backlog items to be worked on during the current active sprint and the completed items that need to be shown to the stakeholders.
    - Code Increment:
        - A collection of completed tasks from various teams and sprints that are shown to the stakeholders.

### 3.4.2 Sprint Planning Meeting:
- Prior to the beginning, development team works with the Product Owner and stakeholders to develop the items for the product backlog. [More information in Chapter 7]
- Scrum Master and development team rank the items by importance of the owner's business needs and the complexity of the software engineering tasks.
- Prior to each sprint:
    - The Product Owner states their development goal for the Code Increment.
    - The development team determines what is feasible during the time constraint
    - The Scrum Master and development team determind what work will be needed to deliver the increment
    - The development team decided which roles are needed and how they need to be filled.

### 3.4.3 Daily Scrum Meeting
- Short 15 minute meeting at the start to allow team members to synchronize their activities and plans
- Three key questions are asks and answers by all team members:
    - What did you do since the last team meeting?
    - What obstacles are you encountering?
    - What do you plan to accomplish by the next team meeting?
- Some teams use these meeting to declare finish items.
- When all sprint backlog items are completed, the team may decide to schedule a demo and review with the Product Owner

### 3.4.4 Sprint Review Meeting
- Typically a 4-hour meeting for a sprint to review the work from the spring.
- Primary activity is a demo of the Code Increments features
- It is alright if the demo shows unfinished features, if the sprint consisted of that being the end state. (Some tasks may take way longer than a single sprint, and that's alright)
- Product owner can reject the code increment which trigger another round of sprint based on the feedback.
- Features may be removed or added from the product backlog based on feedback

### 3.4.5 Sprint Retrospective:
- Typically a 3-hour meeting lead by the Scrum master after a Sprint Review to discuss:
    - What went well in the sprint?
    - What could be improved?
    - What the team will commit to improving in the next sprint?

## 3.5 Other Agile Frameworks
### 3.5.1 The XP Framework (Extreme Programming)
- Planning:
    - Begins with an activity called _listening_ that leads to the creation of _user stories_.
    - _User Stories_: Description of required output, features and functionality for the software to be built. Each is assigned a value that corresponds to the overall business value of the feature.
    - Customers and developers work together to group stories for the next release.
    - Stories can be ordered by:
        - All needing to be required (ie: bug fix patch)
        - Highest valued stories are prioritized and implemented first
        - Riskiest storeies are prioritized and implemented first
- Design:
    - Emphasizes Keep It Simple Stupid
    - Complex systems should be prototyped and then fleshed out
    - Design occurs both before and after coding commences. You may figure out a better approach after your first pass that may scrap a lot of previous work. However, it will be better in the long run! 
- Coding:
    - Pair programming is recommended for a story
    - Ensures real-time problem solving and quality-assurance
    - Code is integrated with the work of others
- Testing:
    - Unit tests are developed
    - Feedback is recieved from the customer

### 3.5.2 Kanban
- Think Trello
- Depends on six core practices:
    1. Visualization of the workflow through physical notecards
    2. Developers are encouraged to complete a current task before proceeding to the next task.
    3. Manageing workflow to reduce waste through:
        - Analysis of where things are stalled
        - Defining and implementing of changes
    4. Making process politices explicit and public for the team (Go up to the board to physically write "Done")
    5. Focusing on continous improvement by creating postive feedback loops
    6. Make process changes collaboratively and inclusively.
- Meetings are similar to Scrum Meetings

### 3.5.3 DevOps
- Combination of Development and Operation tasks.
- Emphasizes:
    - _Continuous Development_ through multiple sprints
    - _Continuous Testing_ through automated testing tools to ensure refined features prior to integration.
    - _Continuous Integration_ through added new functionality to the code and ensuring no errors are present *after* deployment.
    - _Continuous Deployment_ through installing the integration code to the production environment
    - _Continuous Monitoring_ through checking of the production environment health and performance and proactively looking for possibly problems before users encounter them.
- Rather than being a circular cycle, individual DevOp teams can be at different stages

# Chapter 4: Recommended Process Model