# Opening
## Code Review session
## Loose Coupling
- Observer (Event/Delegate) pattern - Notify other objects on changes
- Interface IStudent
- How to organize the project 
- Static method on the Student class
- C# uses delegates but Java does not have anything

### Changes
- public interface IStudentRegisteredForClassListener
    - public void studentRegisteredForClass(Student, CourseInstance)
        - // Calling this method will broadcast the change of state to objects that are listening
- public class Professor implements IStudentReg...
- public class Student
    - List<Student> listener
    - public static AddStudentBy...Listener(<IStudentRegistererdForClassListener>) 

- In the context of Observer Pattern, Professor is the subscriber and the Student is the publisher  

- Java/C# only allow one base class, C++ can inherit from multiple
- Within our objects, avoid circular references
    - Circular references prevents garbage collection
    - Managed languages handle memory by counting references on a seperate thread
- Good to declare arrays as the generic form (ie: List, ArrayList<>)

- If the system gets split up into microservices, the mySQL id becomes the new "memory address"
