# Class diagrams

Relationships between objects - interface class

<<interface>>
    name
    method1()

Interface: classes implement interfaces, denited by generalization.
    
    
<<interface>>
    search
    SearchMember(Name)
    SearchGroup(Name)
    SearchPage(Name)
    PostSearch(Word)
 
At high level, an interface acts as a blueprint for designing classes.
 An interface can contain only method declarations;
        interfaces; implement all the methods in the class thah extends the interface.
    
Interfaces support the hding
    
    A------------------------------B use interfaces: A uses interface B.
    

    
    
    Difference between abstract vs interface class;
    
    -Abstract classes are either partially implemented or not implemented at all.
    -An abstract class allows you to create functionality that subclasses can implement or override.
    -You should use an interface if you want
    
    
    Two more tricks - enumerations 
    - enumerations are model elements
    
    Datatypes; 
    
    
    
    