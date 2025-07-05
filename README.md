# Patterns

* [Architectural Styles vs. Architectural Patterns vs. Design Patterns by Herberto Graca](https://herbertograca.com/2017/07/28/architectural-styles-vs-architectural-patterns-vs-design-patterns/)

## Authorities

* [Kent Beck](https://www.linkedin.com/in/kentbeck/)
* [Martin Fowler](https://martinfowler.com/)
* [Robert C. Martin](http://blog.cleancoder.com)
  
## Architectural Styles

Clean Inspired
* [The Clean Architecture by Robert C. Martin](https://blog.cleancoder.com/uncle-bob/2012/08/13/the-clean-architecture.html)
* [Clean Architecture: A Craftsman's Guide to Software Structure and Design by Robert C. Martin](https://www.amazon.com/Clean-Architecture-Craftsmans-Software-Structure/dp/0134494164)
* [Hexagonal Architecture (a.k.a. Ports and Adapters) by Alistair Cockburn](https://web.archive.org/web/20060711221010/https://alistair.cockburn.us/index.php/Hexagonal_architecture)
* [Hexagonal Architecture Wikipedia](https://en.wikipedia.org/wiki/Hexagonal_architecture_(software))
* [Onion Architecture by Jeff Palermo](https://jeffreypalermo.com/2008/07/the-onion-architecture-part-1/)
* [Screaming Architecture by Robert C. Martin](https://blog.cleancoder.com/uncle-bob/2011/09/30/Screaming-Architecture.html)
* [Data, Context, and Integration (DCI) from James Coplien, and Trygve Reenskaug](https://www.amazon.com/Lean-Architecture-Agile-Software-Development/dp/0470684208/)
* [Data, Context, and Integration (DCI) Wikipedia (complimentary to Model-View-Controller (MVC)](https://en.wikipedia.org/wiki/Data,_context_and_interaction)
* [Boundary-Control-Entity (BCE) from Ivar Jacobson's book Object Oriented Software Engineering: A Use-Case Driven Approach](https://www.amazon.com/Object-Oriented-Software-Engineering-Approach/dp/0201544350)
* [Boundary-Control-Entity (BCE) Wikipedia](https://en.wikipedia.org/wiki/Entity%E2%80%93control%E2%80%93boundary)
* [Separation of Concerns Wikipedia](https://en.wikipedia.org/wiki/Separation_of_concerns)
* [Dependency Inversion Principle Wikipedia](https://en.wikipedia.org/wiki/Dependency_inversion_principle)

<!--
https://herbertograca.com/tag/software-architecture/

Robert C. Martin Series

https://docs.aws.amazon.com/prescriptive-guidance/latest/modernization-data-persistence/cqrs-pattern.html

https://en.wikipedia.org/wiki/Domain-driven_design
https://en.wikipedia.org/wiki/Command_Query_Responsibility_Segregation
https://herbertograca.com/2017/11/16/explicit-architecture-01-ddd-hexagonal-onion-clean-cqrs-how-i-put-it-all-together/

https://netflixtechblog.com/ready-for-changes-with-hexagonal-architecture-b315ec967749
https://docs.aws.amazon.com/prescriptive-guidance/latest/cloud-design-patterns/hexagonal-architecture.html
https://docs.aws.amazon.com/prescriptive-guidance/latest/hexagonal-architectures/overview.html
-->

Various
* [Client-server Model Wikipedia](https://en.wikipedia.org/wiki/Client%E2%80%93server_model)
* [Component-based Software Engineering Wikipedia](https://en.wikipedia.org/wiki/Component-based_software_engineering)
* [Event-driven Architecture Wikipedia](https://en.wikipedia.org/wiki/Event-driven_architecture)
* [Layered (Multitier) Architecture Wikipedia](https://en.wikipedia.org/wiki/Multitier_architecture)
* [Microservices Wikipedia](https://en.wikipedia.org/wiki/Microservices)
* [Monolith Application Wikipedia](https://en.wikipedia.org/wiki/Monolithic_application)
* [Pipeline (Pipes and Filters) Wikipedia](https://en.wikipedia.org/wiki/Pipeline_(software))
* [Plug-ins Wikipedia](https://en.wikipedia.org/wiki/Plug-in_(computing))
* [Publish-subscribe Pattern Wikipedia](https://en.wikipedia.org/wiki/Publish%E2%80%93subscribe_pattern)
* [Service-oriented Architecture](https://en.wikipedia.org/wiki/Service-oriented_architecture)
* [Space-based Architecture Wikipedia](https://en.wikipedia.org/wiki/Space-based_architecture)

### Architectural Characteristics and Design Principles

* [Separation of Concerns Wikipedia](https://en.wikipedia.org/wiki/Separation_of_concerns)
* [Dependency Inversion Principle Wikipedia](https://en.wikipedia.org/wiki/Dependency_inversion_principle)
* [Loose Coupling Wikipedia](https://en.wikipedia.org/wiki/Loose_coupling)

Software Principles (SOLID)
* [SOLID (Object Oriented Design) Wikipedia](https://en.wikipedia.org/wiki/SOLID_(object-oriented_design))
* [Single Responsibility Principle Wikipedia](https://en.wikipedia.org/wiki/Single_responsibility_principle)
* [Separation of Concerns Wikipedia](https://en.wikipedia.org/wiki/Separation_of_concerns)
* [Open-Closed Principle Wikipedia](https://en.wikipedia.org/wiki/Open%E2%80%93closed_principle)
* [Liskov Substitution Principle Wikipedia](https://en.wikipedia.org/wiki/Liskov_substitution_principle)
* [Interface Segregation Principle Wikipedia](https://en.wikipedia.org/wiki/Interface_segregation_principle)
* [Dependency Inversion Principle Wikipedia](https://en.wikipedia.org/wiki/Dependency_inversion_principle)

GRASP Principles
* [General Responsibility Assignment Software Patterns (or Principles) (GRASP) Wikipedia](https://en.wikipedia.org/wiki/GRASP_(object-oriented_design))

<!--
Controller, creator, indirection, information expert, low coupling, high cohesion, polymorphism, protected variations, and pure fabrication.
-->

## Architectural Patterns

### Patterns of Enterprise Application Architecture

* [Patterns of Enterprise Application Architecture by Martin Fowler](https://www.amazon.com/Patterns-Enterprise-Application-Architecture-Martin/dp/0321127420)
* [Catalog of Patterns of Enterprise Application Architecture](https://martinfowler.com/eaaCatalog/)

<!--
https://martinfowler.com/articles/enterprisePatterns.html | Enterprise Patterns
-->

Database
* Foreign Key Mapping
* Lazy Load

Web Presentation Patterns: 
* Model View Controller
* Template View
  
<!--
MVCs
* [Model View Controller Wikipedia](http://en.wikipedia.org/wiki/Model%E2%80%93view%E2%80%93controller)
* [Model View Controller Wikibook](http://en.wikibooks.org/wiki/Computer_Science_Design_Patterns/Model%E2%80%93view%E2%80%93controller)
* [Model–view–viewmodel Wikipedia](https://en.wikipedia.org/wiki/Model%E2%80%93view%E2%80%93viewmodel)
-->

Domain Logic Patterns: 
* Transaction Script
* Domain Model
* Table Module
* Service Layer

Data Source Architectural Patterns: 
* Table Data Gateway
* Row Data Gateway
* Active Record
* Data Mapper 

<!--
https://martinfowler.com/eaaCatalog/domainModel.html
https://www.martinfowler.com/eaaCatalog/activeRecord.html 

Django
https://en.wikipedia.org/wiki/Active_record_pattern | Active record pattern - Wikipedia
https://martinfowler.com/bliki/AnemicDomainModel.html | AnemicDomainModel
-->

Object-Relational Behavioral Patterns
* Unit of Work
* Identity Map

Object-Relational Structural Patterns: 
* Identity Field
* Association Table Mapping
* Dependent Mapping
* Embedded Value
* Serialized LOB
* Single Table Inheritance
* Class Table Inheritance
* Concrete Table Inheritance
* Inheritance Mappers

Object-Relational Metadata Mapping Patterns: 
* Metadata Mapping
* Query Object
* Repository

Web Presentation Patterns: 
* Page Controller
* Front Controller
* Transform View
* Two-Step View
* Application Controller

Distribution Patterns: 
* Remote Facade
* Data Transfer Object

Offline Concurrency Patterns: 
* Optimistic Offline Lock
* Pessimistic Offline Lock
* Coarse Grained Lock
* Implicit Lock
  
Session State Patterns: 
* Client Session State
* Server Session State
* Database Session State
  
Base Patterns: 
* Gateway
* Mapper
* Layer Supertype
* Separated Interface
* Registry
* Value Object
* Money
* Special Case
* Plugin
* Service Stub
* Record Set
  
### Enterprise Integration Patterns

<!--
https://www.amazon.ca/Enterprise-Integration-Patterns-Designing-Deploying/dp/0321200683
-->

## Design Patterns

### Python Design Patterns

Patterns Talks
* [Christopher Neugebauer "You Don't Need That"](https://www.youtube.com/watch?v=dg-Vm9W3Tlc&list=PL2k6bbM_wgjvY02EFUMhwHRyaSaEokT2B&index=37)

Brandon Rhodes
* [Brandon Rhodes: Python Patterns Guide](http://python-patterns.guide) and [Brandon Rhodes: Python Patterns Guide GitHub](https://github.com/brandon-rhodes/python-patterns)

### Design Patterns Built Into Python

Creational Patterns (object creation)
* Singleton Pattern is not needed due to module namespacing
* [Singleton Pattern Wikipedia](https://en.wikipedia.org/wiki/Singleton_pattern)

Behavioral Patterns
* [Iterator Pattern Wikipedia Article](https://en.wikipedia.org/wiki/Iterator_pattern)

### Gang of Four Design Patterns

Gang of Four (GoF) Book
* [Design Patterns: Elements of Reusable Object-Oriented Software](https://www.amazon.com/Design-Patterns-Elements-Reusable-Object-Oriented/dp/0201633612)
* [Design Patterns: Elements of Reusable Object-Oriented Software Wikipedia](https://en.wikipedia.org/wiki/Design_Patterns)

Types of Patterns
* [Creational Pattern Wikipedia](https://en.wikipedia.org/wiki/Creational_pattern)
* [Structural Pattern Wikipedia](https://en.wikipedia.org/wiki/Structural_pattern)
* [Behavioral Pattern Wikipedia](https://en.wikipedia.org/wiki/Behavioral_pattern)

Creational Patterns (object creation)
* [Factory Method Pattern Wikipedia](https://en.wikipedia.org/wiki/Factory_method_pattern)

Creational Patterns- Can use Singleton in Implementation
* [Abstract Factory Pattern Wikipedia](https://en.wikipedia.org/wiki/Abstract_factory_pattern)
* [Builder Pattern Wikipedia](https://en.wikipedia.org/wiki/Builder_pattern)
* [Prototype Pattern Wikipedia](https://en.wikipedia.org/wiki/Prototype_pattern)

Structural Patterns (relationships among entities)
* [Adapter Pattern Wikipedia](https://en.wikipedia.org/wiki/Adapter_pattern)
* [Bridge Pattern Wikipedia](https://en.wikipedia.org/wiki/Bridge_pattern)
* [Composite Pattern Wikipedia](https://en.wikipedia.org/wiki/Composite_pattern)
* [Facade Pattern Wikipedia](https://en.wikipedia.org/wiki/Facade_pattern)
* [Flyweight Pattern Wikipedia](https://en.wikipedia.org/wiki/Flyweight_pattern)
* [Proxy Pattern Wikipedia](https://en.wikipedia.org/wiki/Proxy_pattern)

Structural Patterns (relationships among entities)
* [Decorator Pattern (similar to Chain of Responsibility Pattern; implements Single Responsibility Principal) Wikipedia](https://en.wikipedia.org/wiki/Decorator_pattern)

Behavioral Patterns
* [Command Pattern Wikipedia](https://en.wikipedia.org/wiki/Command_pattern)
* [Mediator Pattern Wikipedia](https://en.wikipedia.org/wiki/Mediator_pattern)
* [Memento Pattern Wikipedia](https://en.wikipedia.org/wiki/Memento_pattern)
* [Strategy Pattern Wikipedia](https://en.wikipedia.org/wiki/Strategy_pattern)
* [Template Method Pattern Wikipedia](https://en.wikipedia.org/wiki/Template_method_pattern)
* [Visitor Pattern Wikipedia](https://en.wikipedia.org/wiki/Visitor_pattern)

Behavioral Patterns
* [Observer Pattern Wikipedia](https://en.wikipedia.org/wiki/Observer_pattern)
* [State Pattern Wikipedia](https://en.wikipedia.org/wiki/State_pattern)
* [Chain-of-Responsibility Pattern (handler, similar to Decorator Pattern) Wikipedia](https://en.wikipedia.org/wiki/Chain-of-responsibility_pattern)

## Code Patterns
