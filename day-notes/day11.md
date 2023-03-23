# Code Review Day
- Objects should have multiple constructors with one of them having an ID
    - Saving an object should return back an object so that the 
- Professor needs a toString() override
- Person super class needs a constructor 
- ids for mySQL cannot be added manually, database should handle their generation
- derived classes shouldn't reimplement their super classes
    - ex: Remove getFirstName() etc from professor
- Change RoomData to the (?,?,?,?) format for preparedStatement
- 