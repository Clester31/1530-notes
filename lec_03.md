# Recap

* Abstraction is key is designing and developing good software systems
* A software development life cycle (SDLC) describes the process of how software is developed
* Building well-designed and complex and system is a proess

* Application domain
  * Focus is the problem
  * Environment where the system is operating
 
*  Solution Domain
  * Docus is on design & Implementation
  * Technologies used to build the system

* SDLC
  * Set of activities and their relationships to each other to support the development of a software system
 
  ![image](https://github.com/user-attachments/assets/e74b0438-4b28-4095-8d8e-c25dcd97ae05)

# Defined vs empirical process control

* Defined
  * Planned, follows strict rules, avoids deviations
 
* Empirical process
  * not entirely plannet, inspect and adapt
 
## How to control software development

* Organizational maturity
  * Focus on structure and organization process
  * Capability Maturity Model Integration
 
* Agile example (scrum)

![image](https://github.com/user-attachments/assets/806c37a1-b2f8-4bb1-b684-26b5603ed33c)

# OOP Recap

## Encapsulation

* Purpse: Hide the internal details of an object from the outside world, and only expose the nceessary functionallity through public methods
* Java supports encapsuation by using classes with attributes for structuting and methods for describing functionality

## Inheritance

* Purpose: create new classes by inheriting attributes & behaviors from existing classes
* Establishes an inheritcane heirarchy (taxonomy)

![image](https://github.com/user-attachments/assets/8e65f53d-882d-43be-9d14-978b462fe929)

## Classes vs Abstract classes

* Class
  * An abstraction in the context of OOP
  * Encapsulates state and behavior
 
* Abstract Class
  * Cannot be instantiated
  * Define an abstract structure which holds common structure (state) or functionality (behavior)
  * Helps to create a blueprint for other classes without implementing all of the concrete methods and properties themselves
 
  ![image](https://github.com/user-attachments/assets/0579d23a-494d-41bc-8948-eac835a4c87b)

## Polymorphism

* Purpose: Ability of an object reference to take on many forms
* A super class reference (compile time)is used to refer to any specific subclass object (run time)
 
![image](https://github.com/user-attachments/assets/0af2c17d-2a7d-45f0-9b2c-e2832c8dfef7)

### Recap

* Encapsulation/resuability: Encapsulation data and behavior allows for efficient code reuse across the application
* Maintainability: OOP makes code modification and maintenance easier over time
* Scalability: OOP allows code to scale with increasing complexity and new features can be added without breaking new ones
* Abstraction, Communication & Collaboration

# UML (unified model language)

* Official standard, maintained by the Object Management Group
* UML diagrams provide a visual representation of an aspect of a system
* UML includes a variety of diagram types for modeling different aspects of software systems

![image](https://github.com/user-attachments/assets/60900dbe-7235-4285-80aa-1d171847e144)

## Purpse of Diagram types

* Case diagram
* Class diagram
* Activity diagram
* State chart
* Communication diagram
* Sequence diagram, etc

## Model Based Engineering

* emphasizes models to design, analyze, and document systems
* Relies on abstract representations (models) of systems
* Visual and standardized way of presenting complex systems
* Can be used as tool for communication between stakeholders

![image](https://github.com/user-attachments/assets/50e4e028-9d95-4852-9b79-c5ead0f4e8f8)

# System Requirements

* Requirements describe the purpose of the system
* They specify the functionality and constraints of a system
* Requirements elicitation describes the proess of identifying requirements
* The elicited requirements are then analyzed and a system model is created

## Requirements engineering

* Process of elicitng requirements and analyzing them

### Identifying Actors

* Actors represent the different users of a system
  * Note that a user is not necessarily just the enduser!
  * Users can also include: SYstem analysts, database admin, another system
 
* In UML, actors are represented as stick figures

![image](https://github.com/user-attachments/assets/0580d810-e2f3-42d2-a7dd-5c629e4708e3)


## User vs Enduser vs Customer

* User: anyone who interacts (uses) the product at any phase
* Enduser: anyone who uses the product at the end
* Customer: A person/ group who...
  * Comissions the product, defines the objective, provides requirements, or is responsible for the funding
 
![image](https://github.com/user-attachments/assets/319fca3a-f910-44f2-a0c9-6de5ee60c4e8)

## Problem Definition

* Typically documented as an informal problem statement
* Describes the purpose of the system
  * Doesn't mean something is wrong, maybe it's describing the gap between an existing and desired state
 
### Separation of the problem from the (concrete) solution

* Clarity and understading - avoid premature solution
* Flexibility - Encourage creativity and innovation
* Foster better collaboration

## Application vs Solution domain

![image](https://github.com/user-attachments/assets/b3d07c81-3559-47c5-aed5-733b40f0736b)

* Requirements elicitation - defines the system from the view of the end user
* Reqruirements analysis - defines the system from the view of a developer

![image](https://github.com/user-attachments/assets/97a8bf2f-eadd-450f-a07c-75cdab05a2ee)

### Greenfield Engineering

* Developing a system from scratch (no prior system exists)
* Requirements: Extracted from stakeholders and end user input
* Initialtion: New market needs
* Starting Point: Clear problem statement based on user needs

### Re-engineering

* Redesign or re-implementation of an existing system
* Requirements: Driven by new technology
* Initiation: Responds to technological advancements
* Starting point: Problem statement rooted in technological evolution

### Interface Engineering 

* adapting an existing system to a new environment
* Initiation: Responds to technology shifts of emergin market demands
* Starting point: problem statement reflecting technological or market changes
