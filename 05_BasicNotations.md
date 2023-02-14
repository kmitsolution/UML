# UML Basic Notations

UML is popular for its diagrammatic notations. We all know that UML is for visualizing, specifying, constructing and documenting the components of software and non-software systems. Hence, visualization is the most important part which needs to be understood and remembered.

UML notations are the most important elements in modeling. Efficient and appropriate use of notations is very important for making a complete and meaningful model. The model is useless, unless its purpose is depicted properly.

Hence, learning notations should be emphasized from the very beginning. Different notations are available for things and relationships. UML diagrams are made using the notations of things and relationships. Extensibility is another important feature which makes UML more powerful and flexible.

The chapter describes basic UML notations in detail. This is just an extension to the UML building block section discussed in Chapter Two.

## Structural Things
Graphical notations used in structural things are most widely used in UML. These are considered as the nouns of UML models. Following are the list of structural things.

1. Classes
2. Object
3. Interface
4. Collaboration
5. Use case
6. Active classes
7. Components
8. Nodes

## Class Notation
UML class is represented by the following figure. The diagram is divided into four parts.

![image](https://user-images.githubusercontent.com/84008107/218646565-9a486849-6b4c-44e6-bc7a-50a073314cc3.png)

<ul>
  <li> The top section is used to name the class.</li>
  <li> The second one is used to show the attributes of the class.</li>
  <li> The third section is used to describe the operations performed by the class.</li>
  <li> The fourth section is optional to show any additional components.</li>
</ul>
Classes are used to represent objects. Objects can be anything having properties and responsibility.

## Object Notation
The object is represented in the same way as the class. The only difference is the name which is underlined as shown in the following figure.

![image](https://user-images.githubusercontent.com/84008107/218648043-f593c3b4-85d6-467e-81c2-9fe7b3b71b20.png)

As the object is an actual implementation of a class, which is known as the instance of a class. Hence, it has the same usage as the class.

## Interface Notation
Interface is represented by a circle as shown in the following figure. It has a name which is generally written below the circle.

![image](https://user-images.githubusercontent.com/84008107/218648110-16a552e4-f906-4638-8e26-a55c68a75381.png)Interface is used to describe the functionality without implementation. Interface is just like a template where you define different functions, not the implementation. When a class implements the interface, it also implements the functionality as per requirement.

## Collaboration Notation
Collaboration is represented by a dotted eclipse as shown in the following figure. It has a name written inside the eclipse.

![image](https://user-images.githubusercontent.com/84008107/218648149-e3d2057f-be08-45de-be04-d52e95ab5c79.png)

Collaboration represents responsibilities. Generally, responsibilities are in a group.

## Use Case Notation
Use case is represented as an eclipse with a name inside it. It may contain additional responsibilities.

![image](https://user-images.githubusercontent.com/84008107/218648188-11e3b553-35af-4db7-bf4f-8e561952cf90.png)

Use case is used to capture high level functionalities of a system.

## Actor Notation
An actor can be defined as some internal or external entity that interacts with the system.

![image](https://user-images.githubusercontent.com/84008107/218648772-9610e920-3088-432b-88e0-1130b3a6c68a.png)

An actor is used in a use case diagram to describe the internal or external entities.

## Initial State Notation
Initial state is defined to show the start of a process. This notation is used in almost all diagrams.

![image](https://user-images.githubusercontent.com/84008107/218648844-969d7fc1-cb42-45b6-9253-9e6c0fe28dbd.png)

The usage of Initial State Notation is to show the starting point of a process.

## Final State Notation
Final state is used to show the end of a process. This notation is also used in almost all diagrams to describe the end.

![image](https://user-images.githubusercontent.com/84008107/218648909-9ddfee36-5e04-4827-ba89-73138fa7732a.png)

The usage of Final State Notation is to show the termination point of a process.

## Active Class Notation
Active class looks similar to a class with a solid border. Active class is generally used to describe the concurrent behavior of a system.

![image](https://user-images.githubusercontent.com/84008107/218648983-2075a2d3-1fae-4191-bccf-81419a9b6965.png)

Active class is used to represent the concurrency in a system.

## Component Notation
A component in UML is shown in the following figure with a name inside. Additional elements can be added wherever required.

![image](https://user-images.githubusercontent.com/84008107/218649048-a11ed7fc-ef33-43a9-99cb-a4c13ebf40b5.png)

Component is used to represent any part of a system for which UML diagrams are made.

## Node Notation
A node in UML is represented by a square box as shown in the following figure with a name. A node represents the physical component of the system.

![image](https://user-images.githubusercontent.com/84008107/218649100-8ce045ab-77d1-4562-814d-6a6fe8cf513b.png)
Node is used to represent the physical part of a system such as the server, network, etc.

# Behavioral Things
Dynamic parts are one of the most important elements in UML. UML has a set of powerful features to represent the dynamic part of software and non-software systems. These features include interactions and state machines.

Interactions can be of two types −

1. Sequential (Represented by sequence diagram)
2. Collaborative (Represented by collaboration diagram)

## Interaction Notation
Interaction is basically a message exchange between two UML components. The following diagram represents different notations used in an interaction.

![image](https://user-images.githubusercontent.com/84008107/218649267-337f73fd-052c-48b4-996a-aca83ea02797.png)

Interaction is used to represent the communication among the components of a system.

## State Machine Notation
State machine describes the different states of a component in its life cycle. The notations are described in the following diagram.

![image](https://user-images.githubusercontent.com/84008107/218649324-b477a743-940b-4b16-ab47-ad6b643e3ee1.png)

State machine is used to describe different states of a system component. The state can be active, idle, or any other depending upon the situation.

# Grouping Things
Organizing the UML models is one of the most important aspects of the design. In UML, there is only one element available for grouping and that is package.

# Package Notation
Package notation is shown in the following figure and is used to wrap the components of a system.

![image](https://user-images.githubusercontent.com/84008107/218649439-31db8478-de0d-4e3e-ada1-787e9f358cef.png)

## Annotational Things
In any diagram, explanation of different elements and their functionalities are very important. Hence, UML has notes notation to support this requirement.

## Note Notation
This notation is shown in the following figure. These notations are used to provide necessary information of a system.

![image](https://user-images.githubusercontent.com/84008107/218649593-fc3795d1-c1b8-4174-b431-962c67bd6393.png)

# Relationships
A model is not complete unless the relationships between elements are described properly. The Relationship gives a proper meaning to a UML model. Following are the different types of relationships available in UML.

1. Dependency
2. Association
3. Generalization
4. Extensibility

## Dependency Notation
Dependency is an important aspect in UML elements. It describes the dependent elements and the direction of dependency.

Dependency is represented by a dotted arrow as shown in the following figure. The arrow head represents the independent element and the other end represents the dependent element.

![image](https://user-images.githubusercontent.com/84008107/218649746-6a052da3-bd59-40d3-a9a0-d2244209ce7e.png)

Dependency is used to represent the dependency between two elements of a system

## Association Notation
Association describes how the elements in a UML diagram are associated. In simple words, it describes how many elements are taking part in an interaction.

Association is represented by a dotted line with (without) arrows on both sides. The two ends represent two associated elements as shown in the following figure. The multiplicity is also mentioned at the ends (1, *, etc.) to show how many objects are associated.

![image](https://user-images.githubusercontent.com/84008107/218649880-e3144fbc-1cc9-42f3-9a37-09c31f985bd8.png)

Association is used to represent the relationship between two elements of a system.

## Generalization Notation
Generalization describes the inheritance relationship of the object-oriented world. It is a parent and child relationship.

Generalization is represented by an arrow with a hollow arrow head as shown in the following figure. One end represents the parent element and the other end represents the child element.

![image](https://user-images.githubusercontent.com/84008107/218649953-054c6092-ed41-4782-bb29-ec8dcb315653.png)

Generalization is used to describe parent-child relationship of two elements of a system.

## Extensibility Notation
All the languages (programming or modeling) have some mechanism to extend its capabilities such as syntax, semantics, etc. UML also has the following mechanisms to provide extensibility features.

1. Stereotypes (Represents new elements)
2. Tagged values (Represents new attributes)
3. Constraints (Represents the boundaries)

![image](https://user-images.githubusercontent.com/84008107/218650017-105d59b7-dc2e-4cc3-a659-790e62aca824.png)

Extensibility notations are used to enhance the power of the language. It is basically additional elements used to represent some extra behavior of the system. These extra behaviors are not covered by the standard available notations.
