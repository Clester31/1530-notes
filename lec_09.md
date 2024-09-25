![image](https://github.com/user-attachments/assets/908ed5d9-a2bd-4459-b3fe-5723bbfd2803)![image](https://github.com/user-attachments/assets/aca7552b-0769-4f9a-be8d-7b91e833a4ca)![image](https://github.com/user-attachments/assets/1b696a6a-6d90-48b5-bd0e-907029f928c0)![image](https://github.com/user-attachments/assets/3a848e79-d692-4bad-89c4-ab34ebb32e7b)# Lecture 9 (09/25/24)

## Status in the SDLC

* Requirements are elicited
  * We have an understanding of the functionality required for the system
  * We have an understanding of the requried quality of out software
  * Understand some general points of interactions of actors with the system
  * We built (some) domain knowledge
 
* Next Steps
  * Further clarify expectations
  * Reduce ambiguities
  * Establish Scope
  * Laying design for system architecture
 
### System model overview

![image](https://github.com/user-attachments/assets/26ae7375-e1cb-4219-b9c2-d78ba5656fd2)

* Overview of models UML

![image](https://github.com/user-attachments/assets/ab4f71bb-3f2d-450c-8d6d-f5427e1379af)

## How to think in an abstract way

1. What are the main entities -> **Objects**
2. What characteristics/properties does the entity have -> **Attributes**
3. What functionality/behavior does the entity provide/need -> **Methods**
4. How do the entities communicate with each other -> **Associations

![image](https://github.com/user-attachments/assets/14d3910e-55e9-400c-8fb7-72d600907e22)

## Analysis Object Model (AOM)

* Defines the system's structure using objects, attributes, methods, and associations
* Often depicted using UML class diagram
  * Typically, visibility is not displayed
  * Focus on the most important elements ( 7 +- 2)
 
### UML Class Diagram - Elements

* UML Class Diagram - Elements
* Focus on the most important entities, their attributes and methods, and their relationships among each other

### UML Class Diagram - Associates & Multiplicities

![image](https://github.com/user-attachments/assets/b99dfea4-627c-410e-9821-b7e9394633c9)

* Associations
  * Inheritance
  * Aggregation
  * Composition
  * Dependency
  * Unidirectional Association
  * Bidirectional Association
 
![image](https://github.com/user-attachments/assets/117d86ad-a4a1-427a-9e67-d81f97c45b70)
 
### UML Class Diagram - Multiplicities

* Specifies more details about an association
* Indicates the number of objects that participate in an association
* Also indivates whether an association is mandatory

![image](https://github.com/user-attachments/assets/662f7cac-43e5-4433-be6d-2c25fb8e1ae3)

![image](https://github.com/user-attachments/assets/22ccbfd9-da96-455e-88bf-859ead999768)

#### Aggregation vs Composition

* Example: A car has four tires. Tires can exist without the car

![image](https://github.com/user-attachments/assets/a7bc5aa0-c00e-4300-a19f-abb390e80ab7)

* ClassB can survive if ClassA is disposed

* Example: A university has various programs. A program cannot exist without a university

![image](https://github.com/user-attachments/assets/77f50cd2-58df-4bc9-8882-bf8a3ab5418b)

* ClassB cannot exists without ClassA

* The whole is on the side with the diamond, the part is on the opposite side

### UML Class Diagram - Other Elements

![image](https://github.com/user-attachments/assets/cbdc2eab-48b1-48c7-9d9d-f656bef6883f)

#### UML Class Diagram Example

![image](https://github.com/user-attachments/assets/1aeb3e55-6bdd-4f25-88f6-a9378f96f7fc)

### Modeling a UML Class Diagram

* First, identify objects
* Identify important attributes (e.g. IDs are usually not important)
* Define their behavior and interaction (associations & methods)

![image](https://github.com/user-attachments/assets/b33b5b6e-5d3d-4cd5-9493-9cf726033610)

## Identifying Associations

* A person can have multiple bank accounts -> *
* A person can view the balance -> viewBalance()
* A person can withdraw from their bank account -> withdraw()

![image](https://github.com/user-attachments/assets/eb8f48e8-7a44-4b16-bf9c-a8acc620c4f4)

### Stereotypes

* Stereotypes allow to extend the vocabulary
* They facitate the creation of new elements based on existing ones
* Class Diagrams: <<Boundary>>, <<control>>, <<entity>>
