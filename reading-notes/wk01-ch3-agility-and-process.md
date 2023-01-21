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