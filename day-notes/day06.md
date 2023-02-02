# Start of Day
- Meet the Geeks
- Ask Prof Mixon about full stack books

# Database CodeReview
- Department table needed
- Might need to look into 
- A course can be in multiple departments
    - Edgecases: Numerical Analysis is two seperate departments, MATH and CSCI, and uses the same room and professor
- Time and Scheduling
    - Required Objects
        - Days of the Week
        - Classroom, Course, Professors, Students 
        - Something matrix based
    - Preselected time slots to avoid too much manual entry
        - Easier to automate scheduling
    - Schedule object in memory. Persist into database?

# How to do CRUD operations with 
- Need Java SQL stuff
- Use DriverManager to get connection to the SQL
    - Does java have environment files?
- Data class per object type
    - Used for handling the CRUD operations
- Spring is annotation based with Reflection like C#
- Java doesn't have annotation by default
- preparedStatement()
    - avoid SQLInjection
- 