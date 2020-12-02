## Class Diagram

- Show different entities related to each other 
- Static structure 
- Describe attributes and operations
- Describe responsability of an system

### Types of Relationships

- #### Association
    - Communication between classes
        - Default: Bi-Directional
        - Contrast: Uni-Directional

- #### Multiplicity
    - How many instances of the class participate in the relationship
    - Example:
        - Zero-to-Many: 0...*
        - Two-to-Four: 2...4

- #### Aggregation
    - Relationship where the child can exist independently of the parent

- #### Composition
    - Child can not exist independent of the parent

- #### Generalization/Interface
    - Mechanism for combining similar classes of the object into a single, more general classes
    - Identifies commonalities among set of entities
    - Example: Flight Reservation
        - Person:
            - Crew 
            - Pilot
            - Admin

- #### Dependency
    - Class depends on another class

- #### Abstract
    - Identified by specifying the name in Italics