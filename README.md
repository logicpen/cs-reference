# High Level Design(HLD)
* The very first step of HLD is to understand the use case, limitations etc of the system.
* After the above step then need to dive into the entire architecture of the whole system. Normally we use diagram, flowcharts etc to layout the different components of the entire system and how they interact with each other.
* The important thing to understand is there might be multiple ways to design a given system.



# Low Level Design(LLD)
* LLD comes after once HLD is finalized, where we design each component individually in detail such as data model, classes and their methods etc for that particular component.
* Below are some common steps to approach LLD
    * Gathering requirements and use cases.
    * Creating type/class diagrams.
    * Model problem with types/classes(usage of Object Oriented Design).
    * Use different design patterns, coding principles etc to implement in code.
* Content described below are generally used in implementing LLD.
## Design Patterns
* Design patterns are common solutions to the recurring problems faced in software design. It results in maintainable, readable and robust code.
* **Creational Pattern:** As the name suggests these pattern provides mechanism to create objects effectively and efficiently such as class or object instantiation. Following are categorized under creational pattern,
    * Builder Pattern
    * [Singleton Pattern](low-level-design\design-patterns\singleton.md)
    * Factory Pattern
    * Abstract Factory Pattern
    * Prototype Pattern
* **Structural Pattern:** These patterns provides the way to combine smaller objects/classes to create larger objects/classes.
* **Behavioral pattern:**
