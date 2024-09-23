# Lecture 8 (9/23/24)

## Review - Use Cases

* Use cases describe the system's behavior from the **actor's point of view**
* If a use case has a flow of events that is non-trivial, a textual description helps to identify and document these events

## User Stories - Overview

* An informal, general explanation of a single functional reuqirement that describes the system from the **(end)user's perspective**
* Communicate how a piece of work will deliver a particular value back to the customer
* Written as
  * **"As a [user type/actor] I want [goal] so that [reason]**
 
### Object Types

* Entity objects
  * Represent the persistent information tracked by the system
  * Have attributes and methods that operate on those attributes
  * Often represent the real-world concepts or data that the system manages
 
* Boundary Objects
  * Represent the interaction between the user and the system
  * Responsible for input validation, user interface rendering, and communication with external systems
 
* Control objects
  * Represent the control tasks to be performed by the system
  * Encapsulates the logic that processes input, coordinates actions, and manages the overall behavior of the system
 
![image](https://github.com/user-attachments/assets/e0075e10-1804-4cd6-8990-ef33ca772f28)

#### Best Practices

* Aim for high cohesion - each obj should have a well-defined purpose and responsibility
* Low coupling - aim for modularity
* Iterative process
* Documentation
* Review and validation

### Analysis - First step towards system architecture

* Goal - createa a model of the system that is correct, complete, consistent, and unambiguous
* Transform requirements from requirements elicitation and focus on boundary conditions and exceptions
* Validate, correct, and clarify specifications
 
  *   
