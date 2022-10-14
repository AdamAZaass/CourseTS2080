
USE CASE DIAGRAMS

--Descripton
    -Visualise functional requirements
    -frontend
    -non functional ---> colors, size etc.
-The purpose of a use case is to define a piece of coherent behavior without revealing ther internal structure of the subject.
-Help visualize the functional rquirements of a system, including the relationship of "actors" to the essential processes, 
    as well as the relationships among different use cases.
-Further interactions can be defined as statechart diagrams, sequence diagrams, communication diagrams, or informal text desriptions.
    Dont crowd this diagram.
    
The pieces of interactive functionality are called use cases.
    -A use case describes an interaction with actors as a sequence of messages betweeen the system and one or more actors.
    

Use case diagrams -- facts#1
    -System boundary: A system boundary defines the scope and limits of the system. It is shown as rectangle that spans all use cases of the system.
    -An actor is something that interacts with the system.
        -An actor is an idealization of a role played by and external person, process, or thing interacting with a system, subsystem, class.
    -The use cases are whats inside the system boundary.
        -Use case: every business functionality is a potenial use case.
        -The use case should list the discrete business functionality specified in the problem statemant.
        -Generalization: of an actor means that one actor can inherit the role of the other actor.
                        The descandant has one or more use cases that are specific to that role.
Use case diagrams -- Facts#2

    -Associations: A-line between actors and use cases. in complex diagrams, it is important to know which actors are associated with which use cases. 
    - include: relationship represents an invocation of one use case by another use case. from coding perspectiv, it is like one function being called by another function.
    ------> include
    <------ extend
Extend: example
            
         -The extending use case is usually optional and can be triggered conditionally.
         -The extended (base) use case must be meaningful on its own. this means it should be independent and must not rely on the behaviour of the extending use case. 

Include: example
    - Include relationship represents an invocation of one use case by antoher use case.
    - the base use case is incomplete without the included use case 
    - The included use case is mandatory and not optional 
        
login to ------> verify password --- include ------>
login <------- (show error message) ---- extend  <-------
    
        
      
                    
                