

### V-model



![V-Model](https://media.geeksforgeeks.org/wp-content/uploads/V-Model.png)



The V-model is a type of SDLC model where process executes in a sequential manner in V-shape. It is also known as Verification and  Validation model. It is based on the association of a testing phase for each corresponding development stage. Development of each step directly  associated with the testing phase. The next phase starts only after completion of the previous phase i.e. for each development activity,  there is a testing activity corresponding to it.

**Verification:** It involves static analysis technique  (review) done without executing code. It is the process of evaluation of the product development phase to find whether specified requirements meet.

**Validation:** It involves dynamic analysis  technique (functional, non-functional), testing done by executing code.  Validation is the process to evaluate the software after the completion of the development phase to determine whether software meets the customer expectations and requirements.

Why preferred?

* pro-active defect tracking
* so defects can be found in early stage

when to use:

* when requirements are clearly defined and fixed
* Used when ample technical resources are available with technical expertise

Pros:

* simple and easy to understand and use
* good for small projects when the requirements are clear
* building the error free and good quality product bcoz of verification and validation in early life cycle of SD
* higly disciplined model and each phases are completed one at a time

Cons:

* not good for complex projects, where requirements are unclear
* model does not support iteration of phases
* high risk and uncertainitY

#### Design Phase:

- **Requirement Analysis:** This phase contains  detailed communication with the customer to understand their  requirements and expectations. This stage is known as Requirement  Gathering.
- **System Design:** This phase contains the system design and the complete hardware and communication setup for developing product.
- **Architectural Design:** System design is broken down further into modules taking up different  functionalities. The data transfer and communication between the  internal modules and with the outside world (other systems) is clearly  understood.(high level design)
- **Module Design:** In this phase the  system breaks dowm into small modules. The detailed design of modules is specified, also known as Low-Level Design (LLD).

### Testing phase:

- **Unit Testing:** Unit Test Plans are developed  during module design phase. These Unit Test Plans are executed to  eliminate bugs at code or unit level.
- **Integration testing:** After completion of unit testing Integration testing is performed. In  integration testing, the modules are integrated and the system is  tested. Integration testing is performed on the Architecture design  phase. This test verifies the communication of modules among themselves.
- **System Testing:** System testing test the complete application with its functionality,  inter dependency, and communication.It tests the functional and  non-functional requirements of the developed application.
- **User Acceptance Testing (UAT):** UAT is performed in a user environment that resembles the production  environment. UAT verifies that the delivered system meets user’s  requirement and system is ready for use in real world.

### AUTOSAR:

Automotive open system architecture for creation of open and standardized software architecture for automotive electronic control units

#### About company:

is a sister company of continental since 2015, based in erlangen. 

Elektrobit is an AUTOSAR specialist, both classical and adaptive AUTOSAR

Provides services in connected car, Over the air update, and remote data collection

Development of driving scene, simulation for ADAS and validation of ADAS functionalities

Also build customizable user interfaces for infotainment 

Has different modules such as vehicle positioning with cm precisin, environment module and electronic module

develop products for automotive industries according to standards such as AUTOSAR and V-model, products includes ECU, development of UI for augmented reality, accurate positioning of vehicle  platfrom for next generation of HPC, and also provides services in security of embedded software, testing and validation of embedded software. 



### Agile:

* requirements are better understand bcoz of constant feedback
* product is delivered much faster

CI:

merging the working copies of all developers into a shared repo several times a day or week

#### Agile:

In agile developers and operation team work separatey, any error in the software while deploying, opetation team has to contact developers

### Devops:

in devops developers get the constant feedback from the operation team, 

direct inteaction between development and the operation team,so after delivery of product as compared to agile

Pros:

* time to create and deliver the product is reduced
* complexity of mainting the application is reduced
* improved collaboratio between developer and the operation team 
* CI/CD ensure faster time to market

What are arUco markers?

* An aruco marker is a  fiducial marker that is placed on the object or scene being imaged. It  is a binary square with black background and boundaries and a white  generated pattern within it that uniquely identifies it. The black  boundary helps making their detection **easier**. They can be generated in a variety of sizes.
* Checkerboard

Navigation:

* Used motion planning alogrithm to naviagte from point A to point B, using landmarks straight move planner.



### Functional Safety:

Functional safety means  protecting the user/surrounding environment from the system/technology, when th unacceptable behavior happens in the system due to the failure or fault in the system. So each domain has its own safety standards, in automotive, it is ISO 26262. 

ISO 26262 specifies:

1. An automotive safety life cycle in order to reduce the risk to acceptable level while developing a software

2. Classification of risk based on the severity of the damage bcoz of fault/failure
3. Providing a safety requirement for either an item or subsystem or components using
automotive safety integration level (ASIL)
4. Requirements for validation of item/subsystem/components to achieve a defined safety
goal.

SO basically, When developing any E/E components in automotive, each development phase should be comply with the ISO 26262 standards. 



### Why elektrobit?

SInce EB is a leading supplier of embbeded software for connected and autonomoius driving functionalites, I can get the opportunity to work with different technilogies, such as connectivity, autonomous driving depending upon the projects and also can directly interact with the leading automakers to get their requirements in developing and brining the safe autonomous vehicle onto the road.

Have products in positioning, connected vehicles, ECU, ADAS, security and remote data collection and simulation 





### UML:

##### structure diagram:

describe what must be included/present in the software system, mainly emphasis on software architecture of the software system

Class diagrams:

* describe the type of objects system consists of along with object attributes and opertions and relationships among the objects
* blue print of an object. 
* inheritance, association, composition, dependecny, aggregation
* Aggregration(collabaration/connection) is a part of class 1 is a part of class2 house and roo, room is part of house, storng dependcy (exist owership)   weak ownership
* empliyee and departments, destoyr one department, still employee exist 
* Inheritance, person, student, name, age, address, professor , generalization
* association has a relationship, weak realtionship, doctor has a patient,s patients has a doctors,  without patiend doct exist, without doctor pateien exist
* composition strong depnedcy like housw own a room, without house, roon does not exist
* Dependecy - object A depned on Object B to carry out it work, change in Object B directly reflect in ObJect A, 
* reduce code reuse,  Person and employee

Component diagram:

* shows how the system is dvided into components and dependencies among the components

Composite structure diagram

* internal structure of a system, and collaboration among the classes, car has engine

Deployment diagram:

* describes the hardware used for the implementation of the software and execution environment and artifacts deployed on the hardwar
* https://www.guru99.com/deployment-diagram-uml-example.html
* Artifact - exectuable file 
* Node used to execture the artifact
* 

Object diagram:

* Shows the complete or partial view of the modeled system at a specific time, instance of a class, how the set of objects are related to each others
* https://www.lucidchart.com/pages/uml-object-diagram

Package diagram:

* shows the structure of the designed system at the package level, 
* Describes how a system split into logical grouping by showing dependencies among the group
* 

Profile diagram:

* 

##### Behavior diagram:

describes what mus happen in the system being modeled.  which means functionality of the software system

Activity diagram:

* describe the busniess and step by step operational worfflow of components in a system 

State Machine diagram:

* describes state and state transitions of a system

Use case diagram:

* describes the functionality provided by the system in terms of actors,  goal represented as use cases and dependency among the use cases

Sequence diagram:

* shows how the objects communicate with each other in terms of a sequence of messages, also indicates life span of the objects relative to those messages.

Interaction diagram:

* 

TIming diagram

* 
