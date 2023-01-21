# Chapter 7: Understanding Requirements
## Quicklook
- Before starting technical work, its good to create a set of requirements for engineering tasks.
- Through the requirements, you may a better understanding of the product's impact, the customer wants/needs, and how the users will interact with the software.
- The stakeholders may not know exactly what they want at the project's inception

## 7.1 Requirements Engineering
- _Requirements Engineering_: The spectrum of tasks and techniques involved that lead to an understanding of requirements.
- Begins during the communication activity and extends to the modeling activity
- Builds a bridge to design and construction
- Encompassing seven tasks that somewhat overlap each other
    - Inception:
        - The initial basic understanding of the project
        - Communication between all stakeholders and the development team needs to be established
    - Elicitation
        - Establishment of long-term business goals
        - Goals may address functional or nonfunctional concerns
        - Goals may be used to manage conflicts among stakeholders
        - A software engineer must engage stakeholders to have them share their goals honestly and in detail
    - Elaboration
        - Refinement of requirements from Inception and Elicitation
        - Goal of this step is to be able to establish a firm base for design and move on in the development process.
        - It is still alright to gloss over unnecessary details
    - Negotiation
        - All actions have pros or cons, whether directly through implementation or through cost of time.
        - Requirements are eliminated, combined, and/or modified so that each party achieves some measure of satisfaction.
    - Specification
        - Specs can describe multiple things and vary from project and needs
            - ie: written document, graphical models, usage scenarios, a prototype or a combination of these
            - ie: large system -> specs: a written document of descriptions and graphical models
        - Used to communicate requirements in a more specific, standardized form
    - Validation
        - Analysis of the current or previous development states
    - Management
        - Set of activity that help the project team identify, control, and track requirements as the project proceeds

## 7.2 Establishing the Groundwork
### 7.2.1 Identifying Stakeholders
- _Stakeholders_: Anyone who benefits in a direct or indirect way from the system which is being developed
- At inception, it is ideal to compile a list of people to consult to gain input

### 7.2.2 Recognizing Multiple Viewpoints
- Several things can cause variation and uncertainty:
    - Unclear project goals
    - Inconsistent or conflicting requirements between stakeholders
    - Stakeholders will likely not be aware of the invisible innerworkings
    - Unspoken assumptions and misintepretations
- Effective requirements engineering should eliminate or at least reduce these problems

### 7.2.3 Working Toward Collaboration
- Requirement engineering should find commonalities and opposing opinions between differing stakeholders

### 7.2.4 Asking the First Questions
- Questions asked at the beginning of the project should be context free to gauge interest and who the target demographic is.
    - Who is behind the request for this work?
    - Who will use the solution?
    - What will be the economic benefit of a succussful solution?
    - Is there another source for the solution that you need?
- Questions to gain a better understanding of the problem and to hear the customer's ideal vision of a solution
    - How would you characterize "good" output that would be generated by a succussful solution?
    - What problem(s) will this solution address?
    - Can you show (or describe) the business environment in which the solution will be used?
    - Will special performance issues or constraints affect the way the solution is approached?
- Questions to focus on the effectiveness of the communication activity itself
    - Are you the right person to answer these questions? Are your answers "official"?
    - Are my questions relevant to the problem that you have?
    - Am I asked too many questions?
    - Can anyone else provide additional information?
    - Should I be asking you anything else?

### 7.2.5 Nonfunctional Requirements
- _Nonfunctional Requirement (NFR)_: a quality attribute, a performance attribute, a security attribute, or a general constraint on a system that are often not easy for stakeholders to articulat
    - ie: Transmitting data from a user to a server should be encrypted (NFR)

### 7.2.6 Traceability
- A dependency graph of requirements used for planning and analysis

## 7.3 Requirements Gathering
### 7.3.1 Collaborative Requirements Gathering
- Guidelines for a collaborate gathering:
    - Meetings (IRL or virtual) are conducted and attended by both software engineers and stakeholders
    - Rules for preparation and participation are established
    - An agenda that is formal enough to cover all important point but informal enough to encourage the free flow of ideas
    - A _facilator_ controlling the meeting
    - A _definition mechanism_ is used. (Worksheets, flip charts, wall stickers, whiteboard, chatroom)
- Encourage the collaboration of everyone but not to an excessive amount that people become uncomfortable
- Common Stakeholder concerns:
    - Can we build the system?
    - Will this development process allow us to beat our competitors to market?
    - Do adequate resources exist to build and maintain the proposed system?
    - Will the system performance meet the needs of our customers?

### 7.3.2 Usage Scenarios
- Software engineers should be aware that users may use the product in multiple and/or unexpected ways

### 7.3.3 Elicitation Work Products
- For large systems, the work products may include:
    - A statement of need and feasibility
    - A bounded statement of scope for the system or product
    - A list of customers, users, and other stakeholders who participated in requirements elicitation
    - A description of the system's technical environment
    - A list of requirements and domain constraints that apply to each
    - A set of usage scenarios that provide insight into the use of the system/product under different operating conditions

## 7.4 Developing Use Cases
- What will the process of a user's use of a system/product be like?
- How does the system/product benefit a category of user?

## 7.5 Building the Analysis Model
- Intent of an analysis model is to provide a description of the required information, functional, and behavioral domains for a computer based system.
- An analysis model is a snapshot of the requirements at any given time.

### 7.5.1 Elements of the Analysis Model
- Scenario-Based Elements: Describes the system from the user's point of view
- Class-Based Elements: Describes an object (think Object Oriented Programming)
- Behavioral Elements: Behavior/state of the computer based systems
    - ie: A toggle can be on or off

### 7.5.2 Analysis Patterns
- Some problems can reoccur across other projects and their solutions may be reused as well
- It is ideal to categorize previous problems and solutions

# 7.6 Negotiating Requirements
- Requirements are determined to be _good enough_ if the parties accept the negotiations

# 7.7 Requirements Monitoring
- As requirements are incremental developed, requirement monitoring is used:
- _Requirement Monitoring_ consists of:
    1. Distributd Debugging: uncovers errors and determines their cause
    2. Run-Time Verification: determines whether product matches its specifications
    3. Run-Time Validation assesses whether the evolving product aligns with the project goals
    4. Business Activity Monitoring: evaluates whether a system satisfies business goals
    5. Evolution and Codesign: provides information to stakeholders as the system evolve

# 7.8 Validating Requirements
- As a requirement is added, it should be examined if it is really needed, and if so categorized 
    1. Is each requirement consistent with the overall objectives for the system or product?
    2. Have all requirements been specified at the proper level of abstraction? That is, do some requirements provide a level of technical detail that is inappropriate at this stage?
    3. Is the requirement really necessary or does it represent an add-on feature that may not be essential to the objective of the system?
    4. Is each requirement bounded and unambiguous?
    5. Does each requirement have attribution? That is, is a source (generally, a specific individual) noted for each requirement?
    6. Do any requirements conflict with other requirements?
    7. Is each requirement achievable in the technical environment that will house the system or product?
    8. Is each requirement testable, once implemented?
    9. Does the requirements model properly reflect the information, function, and behavior of the system to be built?
    10. Has the requirements model been “partitioned” in a way that exposes progressively more detailed information about the system?
    11. Have requirements patterns been used to simplify the requirements model? Have all patterns been properly validated? Are all patterns consistent with customer requirements?