Most of the people in the working world skip the UML step
Keep coding slightly behind the planning stage
Professor will setup the actual project repo
Good to build a module monolith then split it into microservices
The web is build on a Model-View-Controller (MVC)
    - Model <-> Controller <-> View
    - Model should not interact with View directly
Vocab to look up: Bounded-Context
Currently in the Model phase, View is the frontend
Controller is going to be JavaSpring (will cover later)
Vocab: POJO: Plain Old Java Object
Additional book available on Moodle: Software Engineering at Google

Final: Write a MVC with a console as the view
Use examples of tight/lose coupling
WIll be a take home exam

## Professor Requirements:
firstName: String
lastName: String
courses: []

## Building Requirements:
uuid
classrooms: [Int:Classroom]
### notes:
 - online aspect that has a 

## Classroom Requirements
uuid
maxCapacity: Int

Enum for classroom type
