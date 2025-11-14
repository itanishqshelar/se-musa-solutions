**Software Reengineering**

- It is the examination and alteration of a system to reconstitute it in a new form.
- The principles of Re-Engineering when applied to the software development process is called software re-engineering.
- It affects positively at software cost, quality, service to the customer and speed of delivery.
- It is done to improve the software to make it more efficient and effective.

**Software Re-Engineering Activities**:

1.  **Inventory Analysis**:

    - Every software organization should have an inventory of all the applications.
    - Inventory can be nothing more than a spreadsheet model containing information that provides a detailed description of every active application.
    - By sorting this information according to business criticality, longevity, current maintainability and other local important criteria, candidates for re-engineering appear.
    - The resource can then be allocated to a candidate application for re-engineering work.

2.  **Document Constructing**:

    - Documentation of a system either explains how it operates or how to use it.
    - **Documentation must be updated**: It may not be necessary to fully document an application. The system is business-critical and must be fully re-documented.

3.  **Reverse Engineering**:

    - Reverse engineering is a process of:
      - design recovery
    - Reverse engineering tools extract data, architectural, procedural design information from an existing program.

4.  **Code Reconstructing**:

    - To accomplish code reconstructing, the source code is analysed using a reconstructing tool.
    - Violations of structured programming construct are noted and code is then reconstructed.
    - The resultant restructured code is reviewed and tested to ensure that no anomalies have been introduced.

5.  **Data Restructuring**:

    - Data restructuring begins with a reverse engineering activity.
    - Current data architecture is dissected, and the necessary data models are defined.
    - Data objects and attributes are identified, and existing data structure are reviewed for quality.

6.  **Forward Engineering**:
    - Forward Engineering also called as renovation or reclamation not only for recovers design information from existing software but uses this information to alter or reconstitute the existing system in an effort to improve its overall quality.

**Software Reverse Engineering**

- It is a process of recovering the design, requirement specifications and functions of a product from an analysis of its code. It builds a program database and generates information from this.
- The purpose of reverse engineering is to facilitate the maintenance work by improving the understandability of a system and to produce the necessary documents for a legacy system.

**Steps of Software Reverse Engineering**:

- **Collection Information**:
  - This step focuses on collecting all possible information (i.e., source design documents etc.) about the software.
- **Examining the information**:
  - The information collected in step-1 as studied so as to get familiar with the system.
- **Extracting the structure**:
  - This step concerns with identification of program structure in the form of structure chart where each node corresponds to some routine.
- **Recording the functionality**:
  - During this step processing details of each module of the structure, charts are recorded using structured language like decision table, etc.
- **Recording data flow**:
  - From the information extracted in step-3 and step-4, set of data flow diagrams are derived to show the flow of data among the processes.
- **Recording control flow**:
  - High level control structure of the software is recorded.
- **Review extracted design**:
  - Design document extracted is reviewed several times to ensure consistency and correctness. It also ensures that the design represents the program.
- **Generate documentation**:
  - Finally, in this step, the complete documentation including SRS, design document, history, overview, etc. are recorded for future use.
