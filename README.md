<h1 align="center">Midterm Review</h1>
<p align="center">Review and summary of course material covered by the midterm</p>

<h3 align="center">In class - February 26</h3>

<br><br>

| Format |
| ------ |
| <ul><li><b>80 minutes</b></li><li><b>Open book</b> - paper only (photocopy or hard copy of book).</li><li><b>Coverage:</b> All [lecture notes and listed readings](https://github.com/SENG480-18/course) up to February 5<sup>th</sup> inclusive.</li><li><b>Four long answer questions, choose one from each:</b></li><ol><li><b>Read code (Java or Python) and interpret diagrams (UML with key)</b></li><li><b>Business cases</b> - "This is company X, these are their business goals" - produce QA and QAS's that demonstrate how the software meets the business goals.</li></ol><li><b>You should know:</b><ul><li>Business rules</li><li>Architecture drivers</li><li>Quality attributes and scenarios</li><li>Views: Module & Component-and-Connector</li><li>Behaviour Models</li></li></ul>|

---

<br><br>
  

## Table of Contents
<sup>(in order of appearance)</sup>

### Lecture Notes
* [Introduction: What is Software Architecture?](#introduction-what-is-software-architecture)
* [Software Architecture Overview](#software-architecture-overview)
* [Reading Code](#reading-code)
* [Architecture Stakeholders and Requirements](#architecture-stakeholders-and-requirements)
* [Views on Architecture - Modules](#views-on-architecture---modules)
* [Views on Architecture - Component and Connector](#views-on-architecture---component-and-connector)
* [Architecture and Design](#architecture-and-design)
* [Documenting Behaviour](#documenting-behaviour)

### Readings
* [Textbook Chapter 1](#textbook-chapter-1)
* [Textbook Chapter 2](#textbook-chapter-2)
* [Textbook Chapter 3](#textbook-chapter-3)
* [Textbook Chapter 16](#textbook-chapter-16)
* [Textbook Chapter 18](#textbook-chapter-18)
* [Textbook Chapter 4](#textbook-chapter-4)
* [Textbook Chapter 17](#textbook-chapter-17)

### Other Resources
* [SEI View Example](#sei-view-example)
* [What is Architectural Design?](#what-is-architectural-design)
* [SEI Behaviour Tech Report](#sei-behaviour-tech-report)

---

<!-- Begin skeleton -->

### Textbook Chapter 1

<sup>(notes go here)</sup>


### Introduction: What is Software Architecture?
[Lecture 1](https://github.com/SENG480-18/course/blob/master/lectures/1-intro.md)

**Every system has an architecture.**

"The software architecture of a system is the set of structures needed to reason about the system, which comprise the software elements, relations among them, and properties of both."

**Why do we care?**

We identify 7 main benefits of a clearly defined software architecture:

1. **Divide and conquer the problem** - Architecture shows us how to transition up and down the abstraction hierarchy (system purposes down to individual lines of code).
2. **Help manage tasks and facilitate collaboration** - The architecture helps us figure out who does what.
3. **A common language for the system** - We establish and reuse styles, patterns, and syntax (like UML)
4. **Force us to look beyond "function" and into qualities**.
5. **Connect business goals to actual software implementation**.
6. **Avoid high-cost mistakes** - by focusing on the "difficult" decisions.
7. **The best architectures create options** - The "Architectural Runway" consists of the existing code, components, and technical infrastructure needed to implement near-term features without excessive redesign and delay. It provides the necessary technical foundation for developing business initiatives and implementing new Features and/or Capabilities.

### Textbook Chapter 2

<sup>(notes go here)</sup>


### Software Architecture Overview
[Lecture 2](https://github.com/SENG480-18/course/blob/master/lectures/2-arch.md)

#### Why We Document

* Software models are useful abstractions for reasoning about the system when the real world system is too complex to be easily reasoned with.

* **Implications of documentation:**

    * Systems have many (many) structures. We need to filter the ones we really care about.
    * No *single* structure is the architecture.
    * Every system has an architecture, which may be more or less visible in the documentation.
    * We can only define whether an architecture (i.e. set of structures) is "good" or not by understanding how well it meets its quality requirements and ultimate business goals.


#### Software Models

There are three main modes for creating a software model:

1. **Diagram as Sketch** - Sketches are usually only useful in a specific context.  Often, sketches alone will not contain enough information/context to accurately and meaningfully portray a system or some aspect thereof.  Sketches are typically short-term communication tools.

2. **Diagram as Blueprint** - Blueprints are built specifically to be **handed off** to downstream users (analogous with civil engineer handing off building blueprints to general contractor).  Blueprints are meant to be precise and unambiguous.

3. **Diagram as Executable** - This is most common where there are tight constraints on safety or security, such as in automotive software.  In this mode we may use a **code-generation** tool like [Simulink](https://www.mathworks.com/products/simulink.html) to draw block diagrams which a built-in compiler can then translate into **C** code.


### Textbook Chapter 3

<sup>(notes go here)</sup>


### Reading Code
[Lecture 3](https://github.com/SENG480-18/course/blob/master/lectures/3-reading.md)

<sup>(notes go here)</sup>


### Textbook Chapter 16

<sup>(notes go here)</sup>


### Architecture Stakeholders and Requirements
[Lecture 4](https://github.com/SENG480-18/course/blob/master/lectures/4-req.md)

Software in itself is not important, and cannot be measured for quality/satisfiability without recognizing **who the system is *for*** - these are the stakeholders.

The following table will serve as our template for identifying and describing stakeholders:

| Role | Concerns | Instances |
|-----|----------|-----------|
| Acquirers |   Oversee the procurement of the system or product | |
| Assessors |   Oversee the system’s conformance to standards and legal regulation | |
| Communicators |   Explain the system to other stakeholders via its documentation and training materials | |
| Developers |  Construct and deploy the system from specifications (or lead the teams that do this) | |
| Maintainers | Manage the evolution of the system once it is operational | |
| Production  Engineers |   Design, deploy, and manage the hardware and software environments in which the system will be built, tested,  and run | |
| Suppliers |   Build and/or supply the hardware, software, or infrastructure on which the system will run | |
| Support  Staff |  Provide support to users for the product or system when it is running | |
| System | Administrators   Run the system once it has been deployed | |
| Testers | Test the system to ensure that it is suitable for use | |
| Users |   Define the system’s functionality and ultimately make use of it | |




### Textbook Chapter 18

<sup>(notes go here)</sup>


### Views on Architecture - Modules
[Lecture 5](https://github.com/SENG480-18/course/blob/master/lectures/5-modules.md)

<sup>(notes go here)</sup>


### Textbook Chapter 4

<sup>(notes go here)</sup>


### [SEI View Example](https://wiki.sei.cmu.edu/sad/index.php/OPC_Module_Uses_View)

<sup>(notes go here)</sup>


### Views on Architecture - Component and Connector
[Lecture 6](https://github.com/SENG480-18/course/blob/master/lectures/6-cc.md)

<sup>(notes go here)</sup>


### Textbook Chapter 17

<sup>(notes go here)</sup>


### [What is Architectural Design?](http://www.informit.com/articles/article.aspx?p=2738304&seqNum=2)

<sup>(notes go here)</sup>


### Architecture and Design
[Lecture 7](https://github.com/SENG480-18/course/blob/master/lectures/7-design.md)

<sup>(notes go here)</sup>


### [SEI Behaviour Tech Report](http://repository.cmu.edu/cgi/viewcontent.cgi?article=1680&context=compsci)

<sup>(notes go here)</sup>


### Documenting Behaviour
[Lecture 8](https://github.com/SENG480-18/course/blob/master/lectures/8-behavior.md)

<sup>(notes go here)</sup>

<!-- End skeleton -->


### Notes:

#### Business rules

<sup>(notes go here)</sup>

#### Architecture drivers

<sup>(notes go here)</sup>


#### Quality attributes and scenarios

<sup>(notes go here)</sup>

#### Views: Module & Component-and-Connector

<sup>(notes go here)</sup>

#### Behaviour Models

<sup>(notes go here)</sup>


