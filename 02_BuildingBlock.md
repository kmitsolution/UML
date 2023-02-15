As UML describes the real-time systems, it is very important to make a conceptual model and then proceed gradually. The conceptual model of UML can be mastered by learning the following three major elements −

1. UML building blocks
2. Rules to connect the building blocks
3. Common mechanisms of UML

## Building Blocks
The building blocks of UML can be defined as −

1. Things
2. Relationships
3. Diagrams

### Things
Things are the most important building blocks of UML. Things can be −
<ul>
  <li> Structural</li>
  <li> Behavioral</li>
  <li> Grouping </li>
  <li> Annotational</li>
</ul>

#### Structural Things
Structural things define the static part of the model. They represent the physical and conceptual elements. Following are the brief descriptions of the structural things.

#### Class − Class represents a set of objects having similar responsibilities.

<img width="65" alt="image" src="https://user-images.githubusercontent.com/84008107/218643824-0b21652b-d899-4645-a322-6e3e3a10974a.png">

#### Interface − Interface defines a set of operations, which specify the responsibility of a class.

![image](https://user-images.githubusercontent.com/84008107/218643933-32be5aa5-6734-4002-afe5-67f2ef4541e8.png)


#### Collaboration −Collaboration defines an interaction between elements.

![image](https://user-images.githubusercontent.com/84008107/218643950-3683408c-df8f-43cc-955f-b8741f63ab85.png)


#### Use case −Use case represents a set of actions performed by a system for a specific goal.

![image](https://user-images.githubusercontent.com/84008107/218644081-aa88d72c-9f96-43ed-8321-01cb2156c911.png)

#### Component −Component describes the physical part of a system.

![image](https://user-images.githubusercontent.com/84008107/218644162-9ba898e6-55b0-401c-8095-5852c42c4eeb.png)

#### Node − A node can be defined as a physical element that exists at run time.

![image](https://user-images.githubusercontent.com/84008107/218644217-7bbdc264-d716-4c60-8dc1-afd6861246bf.png)


## Behavioral Things
A behavioral thing consists of the dynamic parts of UML models. Following are the behavioral things −

#### Interaction − Interaction is defined as a behavior that consists of a group of messages exchanged among elements to accomplish a specific task.

![image](https://user-images.githubusercontent.com/84008107/218644357-b574d788-15f4-43bd-b9ad-e912994b0c22.png)

![image](https://user-images.githubusercontent.com/84008107/219029041-557fbac2-ee67-471d-8b82-c58216ea00ca.png)


#### State machine − State machine is useful when the state of an object in its life cycle is important. It defines the sequence of states an object goes through in response to events. Events are external factors responsible for state change

![image](https://user-images.githubusercontent.com/84008107/218644405-c7bbbf2c-6752-452c-a68d-8006227adee0.png)

##### Example

![image](https://user-images.githubusercontent.com/84008107/219029724-ac369a62-c701-435a-8cd7-282e4c3af95c.png)


## Grouping Things
Grouping things can be defined as a mechanism to group elements of a UML model together. There is only one grouping thing available −

#### Package − Package is the only one grouping thing available for gathering structural and behavioral things.

![image](https://user-images.githubusercontent.com/84008107/218644500-b8643f4a-c8d2-40f2-b7e6-d0947f3fb250.png)

## Annotational Things
Annotational things can be defined as a mechanism to capture remarks, descriptions, and comments of UML model elements. Note - It is the only one Annotational thing available. A note is used to render comments, constraints, etc. of an UML element.

![image](https://user-images.githubusercontent.com/84008107/218644668-d91b9f3f-98e1-40d7-bc01-e520c991d541.png)

## Relationship
Relationship is another most important building block of UML. It shows how the elements are associated with each other and this association describes the functionality of an application.

There are four kinds of relationships available.

#### Dependency
Dependency is a relationship between two things in which change in one element also affects the other.

![image](https://user-images.githubusercontent.com/84008107/218644786-49c96901-17c8-4631-b148-33aec1e5db47.png)

#### Association
Association is basically a set of links that connects the elements of a UML model. It also describes how many objects are taking part in that relationship.

![image](https://user-images.githubusercontent.com/84008107/218644854-9c6721b4-78f3-4467-be07-b9b18df6405f.png)

#### Generalization
Generalization can be defined as a relationship which connects a specialized element with a generalized element. It basically describes the inheritance relationship in the world of objects.

![image](https://user-images.githubusercontent.com/84008107/218644897-f01be41b-6b2b-4cbc-bef6-82a20a88f45b.png)

#### Realization
Realization can be defined as a relationship in which two elements are connected. One element describes some responsibility, which is not implemented and the other one implements them. This relationship exists in case of interfaces.

![image](https://user-images.githubusercontent.com/84008107/218644957-ab837c75-e51d-45f4-b0cf-d285d474d27a.png)

## UML Diagrams
UML diagrams are the ultimate output of the entire discussion. All the elements, relationships are used to make a complete UML diagram and the diagram represents a system.

The visual effect of the UML diagram is the most important part of the entire process. All the other elements are used to make it complete.

UML includes the following nine diagrams, the details of which are described in the subsequent chapters.

1. Class diagram
2. Object diagram
3. Use case diagram
4. Sequence diagram
5. Collaboration diagram
6. Activity diagram
7. Statechart diagram
8. Deployment diagram
9. Component diagram
