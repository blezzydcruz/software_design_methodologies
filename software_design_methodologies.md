# Software Design Methodologies

1. *What does **coupling** and **cohesion** when discussiong structured design?*

    - Coupling and cohesion are measures of the quality of a software design.
    - Coupling indicates the degree of interdependence *between* two different modules. 
    - Cohesion indicates the degree of cooperation of each element *within* the same module 
    - For a good software design *high cohesion* and *low coupling* is needed. This allows code to be changed, read and tested easily.


2. *What is the difference between **top-down** and **bottom-up** design? Which best describes a function oriented design?*
    - Top-down design is the breaking down of complex algorithm into modules and these modules are further broken down into smaller fragments (this process is known as modularization).This approach minimises complications that comes with designing algorithms.
    - Bottom-up design is the designing of each and every module then combining them together to form a complete algorithmic design. This approach allows reusability of the code. 
    - Top-down best describes a function oriented design.


3. *In which design methodology would a **class diagram** be most useful?*
    - A class diagram would be most useful in Object-Oriented Design (OOD) as it shows the relationships and interactions between objects. This approach allows problems to be modelled to be more modular, maintainable and scalable.

4.  *What are the **four pillars of object oriented programming**? Give a single-sentence description of each.*
    - *Abstraction* involves presenting only the necessary features of an object while hiding the underlying details, this is often achieved through the use of classes.
    - *Encapsulation* is the principle of binding the data and methods that operate on the data into a class.
    - *Inheritance* allows a relationship between two classes to be defined, where one class (child class) can inherit attributes and methods from another class (parent class).
    - *Polymorphism* is a feature that provides a function or an operator with multiple definitions/implementations based on its context.

5. *What is the **strategy pattern**? How would its implementation differ between a functional and object oriented system?*
    - Strategy pattern encapsulates different algorithm/methods for a specific task allowing them to be selected interchangeably at runtime.
    - In a *functional system*, strategies are represented as first class functions or lambdas and are directly passed as to other functions as arguments.
    - In a *object-oriented system*, strategies are represented as an interface or an abstract class with multiple implementations, and the appropriate strategy is set at runtime using polymorphism.

6. Imagine your is creating a new online payment system. In order to gain maximum market share it can't be tied to a particular sector - it needs to work just as well when ordering a takeaway as when buying a new coat. Which design methodology would you suggest following? Give some justification for your decision.
    - For creating a new online payment system, I would use Object Oriented Design programming for its modularity, reusability and flexibility.
    - Modularity via encapsulation allows security of self-contained objects, easy integration across the sectors and safeguarding of sensitive data.
    - Reusability of code allows consistent behaviour across sectors.
    - Flexibility through inheritance and polymorphism enables the system to be tailored for specific sector needs i.e. ordering a takeaway or buying a new coat.
