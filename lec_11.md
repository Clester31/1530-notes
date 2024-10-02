# Lecture 11 (10/02/24)

## Learning goals

* System design overview
* Design goals

## Designing software systems

* Design is a dynamic and creative problem solving activity
* Difficult - there is not concrete recipie
* Requires adaptability and tailoring to the specific context
* Quality of a system's design and its designer directly impact the system's performance, longevity, and overall success

### System Design

* For each feature, there are many ways to accomplish a desired behavior
  * What are the differences between variants
  * Which variant should be choose?
 
* How to implement a system?
  * System design bridges the gap between requirements analysis and implementation
  * Goal: Allocate the requirements to hardware and software components
* Three Main Steps
  * Choose a high level strategy for solving-problem
  * Decide how to organize the system into subsystems
  * Map subsystem to HW componenets and SW components
 
### Designing Software Systems

* Obejct oriented requirements analysis
  * Understand the problem
  * Identify key concepts and their relationships
  * BUild a visual vocabulary
  * Create an application domain model
* Object oriented design
  * Assign responsibilities
  * Explore behavior with interaction diagrams
  * Explore design alternatives
* Implementation
  * Map designes to code, implement classes and methods

### Important system design principles

* Separation of concerns
  * Divide system into seperate aspects or concerns
* Abstraction - hides complex implementation details
* Modularity - promotes code reusability and simplifies maintenance
* Encapsuilation - restricts direct access to adata (data integrity)
* Consistency - promotes readibility, maintainability, integrity
* Simplicity - reduces complexity

### From Analysis to System Design

![image](https://github.com/user-attachments/assets/7fcc3ed0-67c0-488d-a566-691f6c73d193)

* Designing for change
  * The biggest cost is typically not building the system but evolving the system
    * Reducing the cost of change is important when designing software systems  

![image](https://github.com/user-attachments/assets/168a316d-8110-4f96-b9f6-d40acbd4c541)

## Design Goals

* Design goals identify and describe the qualities the system should focus on
  * Often phrased as statements a team makes about the quality of experience they would like a system to attain
  * Design goals can be inferred from the non-functional requirements or from the application domain
    * Design goals are often generalized non-functional requirements
    * Active ElicitationL Some design goals must be actively elicitied through conversations with cliencts or stakeholders; metrics, design methodologies, and implementation goals are valuable sources
* Typically non-perscriptive and more abstract
* Focus on the concerns of designers, architects, and developers
* Often a prioritization of non-functional requirements: **Trade-offs** guide the development

### Types of Design goals - Customer

* **Development Cost** - Cost of developing the system
* **Deployment Cost** - Cost of installing the system
* **Upgrade Cost** - Expenses associated with data migration and backwards compatibility
* **Maintainence Cost** - Resources needed to handle future bug fixes and enhancements
* **Administration Cost** - Cost required for administering and managing the system
* **Extensibility** - How easiy is it to add functinoality ot new classes to the system
* **Modifyability** - How easy it is to change the functionality of the system
* **Adaptability** - How easy it is to port the system to different application domains
* **Portability** - How easy it is to port the system from reading the code

### Types of Design Goals - End User

* **Utility** - How well does the system support user takss and goals
* **Usability** - How easy is it for the user to interact with the system

### Types of Design Goals - Developer

* **Response Time** - How quickly does the system respond after receiving a user request
* **Throughput** - How many tasks can the system accomplish within a fixed time frame
* **Memory** - How much space is necessary for the system to operate efficiently
* **Robustness** - Ability to handle user input
* **Reliability** - Difference between specified and actual behavior
* **Availability** - Percentage of time the system is available for normal tasks without downtime
* **Fault Tolerance** - Ability to continue operating in the presence of errors or failures
* **Security** - Systems ability to precent malicious attacks, unauthorized access
* **Safety** - Better not hurt the user

![image](https://github.com/user-attachments/assets/a5af411c-898e-4abd-8d51-84460dfa342d)

### Requirements vs Design Goals

* Requirements - define what the system must do
* Design Goals - Identify and describe the qualities the system should focus on
