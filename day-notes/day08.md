Scheduling Quirks:
- Availability times
- Professors staying in the same room if back-to-back classes
- Department schedule might have 

- Exam
    - Exam will be given Feb 16th
    - 2 weeks to complete the problem
    - Play the role of the department chair
    - Use as few rooms as possible
    - Information that the chair would have:
        - RoomIds: [Int]
        - Classes: [Object]
            - starttime
            - endtime
    - Look up time interval scheduling algorithms
    - Afterwards there will be a code review

- Scheduling System - Design Talk:
    - The human element is sorted out (ie: availability)
    - Scheduling System might make more sense as a service and not serialized to the database
    - Should it be instantiated or a singleton?

- Looking over the UNCA Courses Website
    - Should have all the data thats on each entry
        - Do we have seats availability in a course? CourseInstance has a registeredStudents: [Students] and the Rooms have the capacity: Int
    - More advance topic: Using a View in the database for a fast query of the data. Uses Stored Procedures
        - Pro: Useful for the UNCA website since it has to load bulk information constantly
        - Con: Unsure, maybe storage costs?
- Advice: Ubiqutious Terminology - Trying to use the same vocabulary across teams to minimize confusion
- Advice: Singleton as a concept: Encapsulation of the Object Creation Cycle
- Quick talk on Design Patterns:
    - Why can't you access instance variables from a Singleton? 
        - Static classes/methods can be used without an instance
    - Two links on the moodle page for Refactoring and Design Patterns
    - Advice: Have very long constructors with mandatory/optional parameters? A factory/builder pattern might be good

- Return to Schedule System - Design Talk:
    - Requirement lowered: Instead of working with a 5 day schedule, use a 1 day schedule for now
    - Unit Testing: Tests small to large components. Useful for business requirements too.
        - Would be nice if the project had the JUnit Testing Library already
    - Integration Testing: Tests to determine if connected pieces are working together
    - Likely to have the first version not be working at 100%

- Break

- Tangent on ChatGPT
    - Can use ChatGPT for the test if we want to
    - No rules for the university so its similar to how tech companies on the bleeding edge work
    - Theres a talk coming up about AI and ChatGPT

- Tuesday:
    - Thinking about the UI (Console)
    - Should mention my TimeUnit class that handles parsing