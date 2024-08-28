# Lecture 2 - Software Systems

## Examples of software systems

* Simple embedded systems
* Complex search engines
* Graphics-intensive games

* There is no common denominator/universal software to build them

## Software Engineering

* More than writing code
* Is an **engineering discipline**
* A process conerned with all sapcets of producing software to solve real-world problmes
* Must define a set of engineering **principles** and **best practices**
* **Involves both technical and non-technical skills**

## Software Engineering Eras

* Early days (~1945-1950)
* Software Crisis( ~1960s - ~1980s)
  * Complexity of software systems
  * Increasing demand
  * Over budget & low quality projects
  * No standards/lack of formalization
  * Hard to manage
 
### Appraoches to ending the software crisis

* Reduce complexity
* Improve Communication
* Introduce Standards
* CASE tools (Computer-Aided Software Engineering(
* Define Processes (Model based / object oriented)

## What is a process

* A set of steps involving activites that take some input, constraints, and resources to produce an intended output
* Involves a set of techniques and tools

### Software development process

* Structered set of activites required to develop a software system
* Many different software processes

![image](https://github.com/user-attachments/assets/05d5e1c4-a407-42a0-b436-60313a83887b)

#### House Building Example

![image](https://github.com/user-attachments/assets/42cee5ec-d919-4575-a02a-01f5aa4cea3e)

### Problems with system integrations

* Communication issues
* Wrong usage of available tools
* Interface miscommunication
* Antipatterns (things that very often go wrong, but can be anticipated)
* Physical impossibility
* Data inconsistencies
* Dependency conflicts
* Performance bottlenecks
* Unforseen compatibility issues

#### Holistic Approach

* To solve problems, we need a holistic view of the entire system
  * Creative thinking
  * Cross-disciplinary
 
### Understanding the problem

* Engage with the customer about the problem scope and the requirements
* Identify specific components of the problm to ensure a comprehensive understanding
* Divide & Conquer
  * Break down complex problems into managable, smaller components/pieces
  * Formulate a structured approach to tackle each component/piece individually
* Problem descriptions aid in recognizing distinct entities and elements

* **Basic assumption of software projects: project outcome cannot be produced in a single monolithic activity**

## Managing complexity in a complex system - Abstraction

* Complex systems are hard/impossible to understand
* Millers law: "The magical number seven, plus or minus two"
  * Human brain constraint: Our immediate memory span covers 7 +- 2 pieces of information at the same time
 
### Abstraction is key

* Allows us to hide unessential details and focus on essential aspects

### Models are abstractions of a system

* An existing system
  * e.g., Canvas, TopHat
* A system to be built
  * e.g., Restaraunt picker app
* A system that no longer exists
  * Legacy systems (Netspace, MacDraw...)
 
### Types of models in software engineering

* Functional model: What are the functions of the system? (use cases)
* Object model: What is the structure of the system? (entities)
* Dynamic model: How does the system react to external events? (activities)

### Model Based Engineering

* Appraoch that emphasizes the use of models to design, analyze, and document systems
* Relies on abstract representation of systems
* Visual and standardized ways of presenting complex systems

![image](https://github.com/user-attachments/assets/167320f4-0887-4513-94f9-f091848e585e)

#### Problems with models

* The more stakeholders involved, the more "mental models" exist
  * Requires extensive communication
  * Prone to misunderstandings
* Solution: Use a common language to abstract and describe problems
  * Ensures a common understanding
 
#### Unified Modeling Language

* Created in late 1990s by a consortium of software companies
* Became an offical standard in 2005 by the Object Management Group (OMG)
* UML diagrams provide a visual representation of an aspect of a system

* Documentation
  * many companies use UML to document their systems
    * Ensures globl understanding
* Ideation & design thinking
  * Structured approach in defining ideas
* Programming
  * Allows to share ideas
  * Helps in defining complex algorithms
 
### Two abstraction Domains

* Application domain
  * Focus is on the problem
  * Environment where the system is operating
 
* Solution domain
  * Focus is on design & implementation
  * Technologies used to build the system
 
![image](https://github.com/user-attachments/assets/e6eee26e-802a-4afa-9168-9abdf5138c77)

### Overview of Model-based Software Engineering

![image](https://github.com/user-attachments/assets/2fef9ec8-f8b4-4cc0-8256-0b10c6076fde)

