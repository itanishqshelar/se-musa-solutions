**Requirements Elicitation & Analysis**

It’s a process of interacting with customers and end-users to find out about the domain requirements, what services the system should provide, and the other constraints.

The requirements elicitation and analysis has 4 main process.

We typically start by gathering the requirements, this could be done through a general discussion or interviews with your stakeholders, also it may involve some graphical notation.

Then you organize the related requirements into sub-components and prioritize them, and finally, you refine them by removing any ambiguous requirements that may arise from some conflicts.

**Here are the 4 main processes of requirements elicitation and analysis.**

![alt text](images/image-9.png)

It shows that it’s an iterative process with feedback from one activity to another. The process cycle starts with requirements discovery and ends with the requirements document. The cycle ends when the requirements document is complete.

1.  **Requirements Discovery**:
    It’s the process of interacting with, and gathering the requirements from, the stakeholders about the required system and the existing system (if exists). It can be done using some techniques, like interviews, scenarios, prototypes, etc, which help the stockholders to understand what the system will be like.

    - **Interviews**: In Interviews, requirements engineering teams put the questions to the stakeholder about the system that’s currently used, and the system to be developed, and hence they can gather the requirements from the answers.
    - **Use Cases & Scenarios**: The use cases and scenarios are two different techniques, but, usually, they are used together. Use cases identify interactions between the system and its users or even other external systems (using graphical notations), while a scenario is a textual description of one or more of these interactions.

2.  **Requirements Classification & Organization**:
    It’s very important to organize the overall structure of the system. Putting related requirements together, and decomposing the system into sub components of related requirements. Then, we define the relationship between these components. What we do here will help us in the decision of identifying the most suitable architectural design patterns.

3.  **Requirements Prioritization & Negotiation**:
    This activity is concerned with prioritizing requirements and finding and resolving requirements conflicts through negotiations until you reach a situation where some of the stakeholders can compromise. Prioritizing your requirements will help you later to focus on the essentials and core features of the system, so you can meet the user expectations. It can be achieved by giving every piece of function a priority level. So, functions with higher priorities need higher attention and focus.

4.  **Requirements Specification**:
    Software requirement specification is a kind of document which is created by a software analyst after the requirements collected from the various sources - the requirement received by the customer written in ordinary language. It is the job of the analyst to write the requirement in technical language so that they can be understood and beneficial by the development team. The models used at this stage include ER diagrams, data flow diagrams (DFDs), function decomposition diagrams (FDDs), data dictionaries, etc.
    - **Data Flow Diagrams**: Data Flow Diagrams (DFDs) are used widely for modeling the requirements. DFD shows the flow of data through a system. The system may be a company, an organization, a set of procedures, a computer hardware system, a software system, or any combination of the preceding. The DFD is also known as a data flow graph or bubble chart.
    - **Data Dictionaries**: Data Dictionaries are simply repositories to store information about all data items defined in DFDs. At the requirements stage, the data dictionary should at least define customer data items, to ensure that the customer and developers use the same definition and terminologies.
    - **Entity-Relationship Diagrams**: Another tool for requirement specification is the entity-relationship diagram, often called an "E-R diagram." It is a detailed logical representation of the data for the organization and uses three main constructs i.e. data entities, relationships, and their associated attributes.
