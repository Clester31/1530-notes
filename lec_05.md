# Lecture 5 (9-11-24)

## What is functionality?

* Describes specific tasks the system performs to achieve an intended goal (processing data, user interactions, system operations)
* Focuses on how the system responds to inputs and delivers outputs
* Defines **how features and services the user can invoke**
  * EX: "The user can upload files"
 
* **Single Purpose** - each functional requirement should represent one logical unit of work
* **Low Complexity** - Complex requirements should be split into seperate requirements
* **Unified testing & maintenance** - each functional requirement should be treated as one unit during testing an maintainence
* **Atomic requirement** is a requirement that can be further broken down into individual tests

## Abbot's Technique Refresher

1. **Identify nouns**: actors/objects
2. **Group and categorize** the nouns: define the objects' tasks and services
3. Determine the relationship between the identified objects

### Defining Requirements Example

* FR2 Create Report: The user can login to the system using their email address and password
  
  ![image](https://github.com/user-attachments/assets/e75a251b-c628-4376-93dd-cbf326bf5db4)

## Non Functional Requirements

* Describe quality attributes that are important for the system (but do not describe functionality)
* Constraints describe limitations or conditions that restrict the solution space
  * budgetary constraints, time constraints, technical constraints
 
### Defining non-functional requirements

* Usability: how easy is the system to use
* RObustnessL How stable and reliable is the system
* Performance: How fast and efficient is the system
* Security: How secure is the system

![image](https://github.com/user-attachments/assets/99319774-15f8-446b-a95d-6148f3f595e0)

### Defining ono-functional requirements

* NFRs are observed during the testing, validation & verification phase
* Focus on measurable, testable, and specific (enough) criteria
  * Is often up t the requirements engineer to define measurable NFRs
 
* Peoblem statements hint at NFRs

#### Usability

* Learnability: How quickly can users grasp the user interface
* Efficiency: One mastered, does the interface enable swift and efficient usage
* Memorability: Can users easily recall how to navigate and use the interface? Is the design memorable and user-friendly over time?
* Error Handling & Robustness - How well does the system handle errors or unexpected user actions?
* (optiona) Satisfaction & User Experience
* Consistency: Is the interface design uniform across different sections
* Flexibility: Can users customize the interface to better suit their individual preferences and needs
* Task Completion: How effectively does the interface support users in accomplishing their intended tasks without unecessary complications
* Feedback: Does the interface provide users with helpful feedback after performing an action or guidance when they encounter difficulty or make errors

##### Example Usability Requirements

* NFR1 Student Leanability [Usability]: Students must be able to use the system without needing a manual
* NFR2 Instructor Learnability [Usability]: Instructors must be able to learna and recall the main functionality of the system after following a user tutorial

![image](https://github.com/user-attachments/assets/ec06b3f3-cc6b-4f2a-b1a2-103b14c1be90)

#### Accessibility

* How easily and efficiently can a user (regardless of ability) use a system to achieve their goals
* Usability vs Accessibility
  * Usability typically applies to the general user population
  * Accesibility specifically addresses how easily users with the widest range of capabilities can use the system
 
* Accesibility typically encompasses all usability sibcategorical

##### Accesibility Example

NFR1: Compatibility with screen readers [Accessibility]: The system must be fully compatible with screen readers, allowing users with visual impariments to navigate and interact with all functional elements

NFR2 Alternative Text [Accessibility]: All non-text content (e.g., images, chart, icons) must include meaningful alternative alternative text that can be read by assistive technologies to provide context for users with visual impairments

#### Reliability

* Does the system consistenyl perform its functions without failure?
  * Robustness: How well does the system handle unexpected inputs or adverse conditions
  * Safety: What measures are in place to ensure user and system safety?
  * Secutity: Are there safeguards to protect aainst unauthorized access and data breaches 

#### Performance

* How efficiently does the system execute its tasks?
  * Throughput: What is the system's capacity for handling simultaneous tasks or transactions?
  * Availability: How ften is the system operations and accessible to users?
  * Accuracy: How precise are the system's calculations or data processing

#### Supportability

* What resources and mechanisms are available for ongoing support and maintainance
  * Adaptability: Can the system adapt to changing requirements or environments?
  * Maintainability: How easy is it to update and maintain the system over time?
  * Portability: Is the system compatible with different platforms or environments
 
### Constraints

* Also refered to as "pseudo-requirements"
* Constraints describe limitations or conditionas that restrict the solution space
* E.g. budgetary constraints, time constraints, technical constraints
* They typically set the scope of the projects

#### Defining Constraints

* Time
* Budget
* Resources
* Regulations
* Operations
* Implementation Requirements
  * Packagaing
  * Interface
  * Legal 
