# Lecture 12

## Identifying Design Goals

* Analyze requirements - Identify implicit design goals within these requirements
* Stakeholder input - Inishgts and expectations regarding system and quality and performance
* Benchmarking existing systems - Industry standards and best practices
* Risk assessment - Potential risks and hallenges associated with the project
* Technical feasability design goals need to align with the chosen technology stack and infrastructure
* Prioritize and refine design goals based on their importance to stakeholders
* Iterative and collaborative
  * Involve cross functional teams in goal derivation and validation
  * Iterative on design goals as the project progresses and new insights emerge
 
### Design Goal Tradeoffs

* Design goals are often confusing
* Typical trade-offs
  * Functionality vs usability
  * Cost vs robustness
  * Efficiency vs portability
  * Rapid development vs functionality
  * Cost vs reusability
 
#### Battery Example

* Design Goal 1: Battery Capacity (Range)
* Design Goal 2: Battery Weight and Size (Efficiency)
* Design Goal 3: Battery Lifespan (Longevity)

## Dynamic Modeling

* Describes the dynamic behavior of parts (components) of the system
* Typically we focus on interesting behavior

### Dynamic Modeling Tools

* Activity Diagram
* State Chart Diagram
* Communication Diagram

### UML Activity Diagram

* Used to organize and represent the flow of activities and actions, grouping them by the interacting system or actor

* Consist of nodes and edges
* Nodes describe activites and objects
  * Control nodes
  * executable nodes
  * object nodes
* An edge is a directed connection between nodes

![image](https://github.com/user-attachments/assets/4c59127d-243d-49d0-bd91-78217718784c)

### UML Activity Diagram Syntax

![image](https://github.com/user-attachments/assets/8e7bee67-65a3-4662-afc4-ee9dcef3afc8)

### Activity fiagrams can use swimlanes

* Purpose: Group actions by viewpoint/role to indicate responsibilities within a process or workflow
* Swimlanes within an activity diagram represents a boundary
  * Helps in separating responsibilities and interactions
* Swimlanes combine the system's high level logic with responsibilities and interactions

![image](https://github.com/user-attachments/assets/71cfc536-d9a8-4e2a-b3e1-3dade3da2a90)

#### How to model an activity diagram

* Activity diagram serves to illustrate various workflows, such as:
  * User specific workflows
  * System workflows
  * Logical workflows
 
* These workflows are frequently derived from
  * The flow of events within use cases
  * Associations found in the analysis object model 
