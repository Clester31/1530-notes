# Lecture 7 - (09/18/24)

## Recap - Scenarios

* How does/will the user interact with the system
* How does the system behave in response

## As-is scenario vs visionary scenario

* As-is scenario
  * Describes the current state or existing system
  * Reflects the current practices, processes, and limitaitons
  * Typically focuses on existing challenegs and inefficiencies
  * Serves as a baseline for evaluating improvements
* Visionary scenario
  * Describes the future system orideal state
  * Represents the desired outcome and goals
  * Often includes innovative features and improved efficiencies
  * Guides the firection of change and improvement efforts
 
## Purpose of scenarios

* Informal, narrative descriptions of sepecific user interactions
* Used for exploring detailed interactions and edge cases
* Make requirements more comprehensive and user-focused
* Basis for test cases & validation
  * Make sure that functionality and edge cases are tested
  * Describe a flow of events with multiple potential outcomes
    * Best, worst, and average case scenario
   
### Deriving Scenarios

* **Client conciseness** - Customers may not provide extensive details for non-extensive systems
* **Domain expertise** - Customers udnerstand the problem domain, not the solution domain
* **Avoid assumptions** - What is obvius to you may not be apparent to the customer
* **Dialectic engagement** - Engage in dialogue to help clients formulate scenarios
* **Dynamic requirements** - Requirements often evolve during scenario formulation
* **Observation** - For existing systems, insist on task observation, interface enginerring, or re-engineering
* **End-User engagement** - Speak to the end users for valuable insights

### How to write a scenario

* Starting point: being with the problem statement
* Answer the following:
  * Actors involved
  * Core functions of the system
  * Information the actors access, generate, store, modify, delete, introduce
  * External changes
  * Events that trigger notifications to the user
 
* Decide on names, contextual circumstances if needed, etc.
  * Know your audience - familiarity with a situation may be relevant
 
### Deriving Functionalty

* Developers focus on actor identification and scenario identification
* Goal: Understand the application domain
* Outcome: Shared understanding of system scope and user workflows
* Next step: Based on the scenario(s) identify functions where an actor interacts with the system -> use cases

### Use Cases

* Goal: Define system functions through a serios of events, producing observable outcomes for actors
  * Use cases are descriptions of interactions between a system and actors (= its users or other systems)
  * Actors initiate use cases to access system functionality
 
![image](https://github.com/user-attachments/assets/cc0b6282-5a32-4136-8aaa-e09a940cf53f)

* Use cases describe the system's behavior from the actor's point of view
* Typically, functional requirements should be phrased in a way that their respective short title can be directly derived into a use case
  * ex: FR1: View Hazardous Area: PIttsburgh's residents can view hazardous areas where sinkholes are likely to occur
  * Use case - UML representation
 
#### Formalize use case template

![image](https://github.com/user-attachments/assets/2ff51b8f-bfa1-45fc-b1a0-e6488ce185ee)

### Use cases - textual description

* If a use case has a flow of events that is non-trivial, a textual description helps to identify and document these events
* Use cases are typically written from the POV of the user

![image](https://github.com/user-attachments/assets/ed5c1196-dc94-4071-b80d-ac850a36845e)

#### UML use case elements

![image](https://github.com/user-attachments/assets/04f1b1bc-23db-423d-985e-21c545345e9b)

#### UML use case elements - <<includes>>

* Goal: Reduce complexity by identifying commonalities in different use cases
  * Incorporates one use case (intended) within another (including use case)
  * Ensures that the included use case is always part of the main functionality of the including use case
  * Enhances modularity and reusability by breaking down complex use cases into simpler, reusable componenets
 
#### <<extends>>

* Goal: Reduce complexity by extending use cases with optional and conditional behavior that occurs within a use case
* Allows for the inclusion of additional functionality, often triggered by exceptional or rare cases
* Enhances flexibility and adaptability in system behavior without cluttering the primary use case with exceptional paths

![image](https://github.com/user-attachments/assets/ac4bb8ae-22e0-4ceb-ac86-61dce504a1c9)



