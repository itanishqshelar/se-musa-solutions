The development process starts with the analysis phase. This phase results in a specification document that shows what the software will do without specifying how it will be done. The analysis phase can use two separate approaches, depending on whether the implementation phase is done using a procedural programming language or an object-oriented language.

![alt text](images/image-10.png)

**Data Dictionary**:

It is a repository that consists of a description of all data objects used or produced by the software. It stores the collection of data present in the software. It is a very crucial element of the analysis model. It acts as a centralized repository and also helps in modelling data objects defined during software requirements.

**Features of Data Dictionary**:

- Data dictionary is a set of meta-data which contains the definition and representation of data elements.
- It gives a single point of reference of data repository of an organization. Data dictionary lists all data elements but does not say anything about relationships between data elements.
- A data dictionary or database dictionary is a file that defines the basic organization of a database.
- A database dictionary contains a list of all files in the database, the number of records in each file, and the names and types of each data field.
- Most database management systems keep the data dictionary hidden from users to prevent them from accidentally destroying its contents.
- Data dictionaries do not contain any actual data from the database, only bookkeeping information for managing it.
- Without a data dictionary, however, a database management system cannot access data from the database.

**Entity Relationship Diagram (ERD)**:

It depicts the relationship between data objects and is used in conducting data modelling activities. The attributes of each object in the Entity-Relationship Diagram can be described using Data object description. It provides the basis for activity related to data design.

**Data Flow Diagram (DFD)**:

It depicts the functions that transform data flow and it also shows how data is transformed when moving from input to output. It provides the additional information which is used during the analysis of the information domain and serves as a basis for the modelling of function. It also enables the engineer to develop models of functional and information domains at the same time.

**State Transition Diagram**:

It shows various modes of behaviour (states) of the system and also shows the transitions from one state to another state in the system. It also provides the details of how the system behaves due to the consequences of external events. It represents the behaviour of a system by presenting its states and the events that cause the system to change state. It also describes what actions are taken due to the occurrence of a particular event.

**Process Specification**:

It stores the description of each function present in the data flow diagram. It describes the input to a function, the algorithm that is applied for the transformation of input, and the output that is produced. It also shows regulations and barriers imposed on the performance characteristics that are applicable to the process and layout constraints that could influence the way in which the process will be implemented.

**Control Specification**:

It stores additional information about the control aspects of the software. It is used to indicate how the software behaves when an event occurs and which processes are invoked due to the occurrence of the event. It also provides the details of the processes which are executed to manage events.

**Data Object Description**:

It stores and provides complete knowledge about a data object present and used in the software. It also gives us the details of attributes of the data object present in the Entity Relationship Diagram. Hence, it incorporates all the data objects and their attributes.
