Notices:
- First exam will be a takehome exam on writing a small MVC application

# Database Lecture:
- Database: Normalized vs Denormalized (NoSQL)
- 5 or so tables in our databse
- By legal: Databases need to have a single source-of-truth
- Student Table: 4 columns
- Normalized databases are optimized for write speed while Denormalized databases for read speed
- Normalized databases minimize redundancy
- To get both benefits, take in data through Normalized database, then pushed to Denormalized databases later
    - Later is typically during low load times
    - Also called: ETL (Extract-Transform-Load)
- 3rd Normal Form:
    - Whenever an array is used, its a good sign to split it into another course
    - Join Table: Connects multiple tables since you don't want a table to be completely dependent on another table
    - Key types:
        - Primary: Autogenerate ID
        - Foreign: A key of another table
- More info on Database in Database Class, this is more of a quick runthrough
- Database for this class is structured data, unstructed databases for chatlogs, screenshots, etc

# Project Estimation
- Agile Development: Story Points to assign the difficulty of a project with Fibonacci Numbers
    1. Everyone, seperately, decides the difficulty of a task.
    2. Averaged (can be weighted by each person's experience years) for it's final difficulty point
- Lines of Code is not a good metric for value
- Be sure to Read: https://nealford.com/memeagora/2015/03/30/architecture_is_abstract_until_operationalized.html

# Architecture is the Big Picture
- Code Smell: Duplicated code that can be refactored out
- MVC: Model<->Controller<->View
- Thick Client:
    - Weather app on iPhone
    - Java Swing/FX
    - "Forms"
    - Has STATE and all the business logic
- Thin Client:
    - Weather website on iPhone
    - Browser based (HTML/CSS/JS)
    - Psuedo-STATE for UI but the business logic is on a server
    - Document-Object-Model (DOM)
    - One benefit allows the swapping out of UI while the business logic is in place
- Exam Notes:
    - View Layer: [System.out, .in]
        - .in will be wrapped into a Scanner or BufferedInputStream
    - Controller class will be between the View and Model and handle the interactions 
        - public ClassroomController(iView, model)
            - iView is an interface to allow for swapping out of the UI later on
            - ConsoleView implements iView { handleSystemOut(); handleSystemIn(); }

# Breakout Groups
- Git Guidelines: