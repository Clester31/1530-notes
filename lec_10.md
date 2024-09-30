# Lecture 10 (09/30/24)

### Learning Goals

* Understand the purpose of an analysis object model

## How to think in an abstract way

1. What are the main entitiers -> **objects**
2. What **characteristics/properties** does the entitiy have -> **Attributes**
3. What functionality/behavior does the enriry provide/need -> **Methods**'
4. How do the entitles communicate with eachother -> **Associations**

### Inheritance

* Inheritence in OOP lets new classes inherit properties and behaviors from existing classes
* Subclasses can extend or modify the functionality of the superclass

### Aggregation

* Establishes part of the heirarchy -> whole or container class
* Componenets are the parts or elements contained within the whole

### Composition

* Implies that the components (parts) are owned by the aggregate
  * Lifespan is controled by the aggregate
 
### Dependency

* Represents a relationship where one element (client) relies on another element (supplier) in some way to perform its functionality
* Categorized into various types: usage, realization, generalization, constraint dependencies

#### Unidirectional association

* Represents a relationship where one element (Client) relies on another element (supplier) in some way to perform its functionality
* Can be categorized into various types: usage, realization, generalization, and constraint dependencies

### Access Matrix

* Access Control: Defines access permissions for entities and objects
* Permissions: Provides detailed, fine-grained access control
* Security: Forms the basis for the system security analysis and policies
* The rows of the matrix represents the actors of the system
* The column represents classes whose access we want to control

![image](https://github.com/user-attachments/assets/b4d6f06b-220d-4e00-baad-c05f5c25729e)
