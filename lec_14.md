# Lecture 14

## Recap

* Low Coupling - degree of interdependence between subsystems within a system
* Cohesion - degree of interdependence within a system

### Interface Segregation Principle

* Keep interfaces focused and specific to the customer’s needs
* Free Parking example
  * A function for free parking would not need methods such as calculateFee(), chargeUser(), etc...
 
### Diversion Inversion principle

* High-level subsystems should not depend on low-level subsystems; both should depend on welldefined subsystem interfaces
* Subsystem interfaces should not depend on implementation details; implementation details should
depend on subsystem interfaces

## Subsystem Decomposition

* Purpose: Reduce complexity

* Architectural design questions
  * Is there a generic template for the system that is being designed?
 
## Architectural Styles

* Monolithic
* Layered
* Pipes and filters
* etc...

### UML component diagram

* Model a high-level view of the system's design using components and depenencies
* UML component diagrams ar eused for:
  * Architectural design and planning
  * Identifying system components
 
### UML interfaces

* Define how components interact with each other or with external entites
* Specify the required and provided services
  * Lolipop: Provided interface -O
  * Socket: Required interface -(
  * Dependency: a component depends on the implementation on another component --->
  * A port specifies a distinct interaction point between the component and it's environment □
