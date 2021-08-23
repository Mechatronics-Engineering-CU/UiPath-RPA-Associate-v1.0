# UiPath-RPA-Associate-v1.0

# DAY-0 Preparation 
As a part of bridging the gap between Academia and Industry, I was nominated and selected from Department of Mechatronics Engineering for this certification course on **The UiPath Certified RPA Associate (UiRPA)**
## Course Expectation
[1] to be able to independently design and develop simple RPA solutions or 
[2] be a productive member of an automation team led by an experienced RPA Developer responsible for developing complex solutions using UiPathtechnologies.

## Evaluation Criteria 
This exam assesses knowledge and skills related to 
- problem solving, 
- process identification, and 
- building simple automation solutions with UiPath platform components such as **UiPath Studio, Robots, and Orchestrator**. 

**UiRPA is the first step for professionals who want to build and assess their knowledge and skills towards their journey to become an Advanced RPA Developer, Solution Architect or RPA Architect.**

## Products that We will be learning:

- UiPath Studio version 2020.10
- UiPath Robots version 2020.10
- UiPath Orchestrator version 2020.10

## Examinations to Pass to qualify for being an RPA Associate

- Robotic Process Automation (RPA) Fundamentals
- UiPath Studio Overview
- UiPath Studio – Variables and Arguments
- UiPath Studio – Selectors
- UiPath Studio – Control Flow
- UiPath Studio – Data Manipulation
- UiPath Automation Concepts and Techniques
- UiPath Orchestrator Overview

## Topics Covered

### Robotic Process Automation (RPA) Fundamentals
- Describe the processes suitable for automation and the processes executed with thedifferent robot types; for example, attended versus unattended
- Explain the functionality and interactions of UiPath products; Studio, Orchestrator, and Robots/Assistant
- UiPath Studio **Overview**
      - Understand the debug functions and how they are used; for example, using Breakpoints
      - Identify how to use Manage Dependencies and understand the significance of connecting an automation project to a version control solution
- UiPath Studio – **Variables and Arguments**
      - Describe the different variable types, how they are used, managed, and the best practice for using the variable scope
      - Describe the functions and differences between variables and arguments; including how arguments are used, managed, and best practices
- UiPath Studio – **Selectors**
      - Identify and describe how dynamic versus static selectors are used
      - Identify and describe how partial versus full selectors are used
      - Identify and describe how and when to use Indicate Anchor in UI Explorer and the AnchorBase activity
      - Demonstrate and describe the use of a reliable selector and how to use UI Explorer to modify selectors
- UiPath Studio – **Control Flow**
      - Explain how to use Control Flow activities and workflow types such as sequences and flowcharts
      - Identify and describe the various Control Flow activities such as If, Switch, While, DoWhile, For Each, etc.
      - Explain the importance of error handling and how it can be implemented
- UiPath Studio – **Data Manipulation**
      - Describe the importance and reasons why data manipulation is used; for example, conversion from one data type to another data type
      - Explain how strings can be manipulated; for example, by using VB string methods and RegEx
      - Explain how to iterate and manipulate data on various collection types and data tables
- UiPath **Automation Concepts and Techniques**
      - Identify and explain how e-mail automation is used
      - Identify and describe Microsoft Excel and data table functions, and how Excel activities are used for data manipulation
      - Describe the functions used to extract data from a .pdf file; for example, reading native text or using OCR
- UiPath **Orchestrator Overview**
      - Identify and describe how UiPath Orchestrator queues and assets are used
      - Identify and explain how to publish projects to UiPath Orchestrator

## Pre-Requisite Working Environment

- Microsoft Windows
- UiPath Studio
- UiPath Orchestrator
- Virtual environments (VMs)
- Browser (IE, Chrome, etc.)
- Version Control
- MS Office and/or MS Office Suite
- Notepad++ (or any other text editor)

![Set UI Path Studio Environment](https://github.com/Mechatronics-Engineering-CU/UiPath-RPA-Associate-v1.0/blob/main/Getting_Started_With_RPA_development/Raw/UIPath%20Studio%20Setup.PNG)

# DAY-1

## Pre-Session Overview:  

- T0he Robotic Process Automation (RPA) Design & Development course offers comprehensive knowledge and professional-level skills focused on developing and deploying software robots. 
- The course assumes no prior knowledge of RPA. 
- It starts with the basic concepts of Robotic Process Automation. 
- It further builds on these concepts and introduces key RPA Design and Development strategies and methodologies specifically in the context of UiPath products. 
- An individual undergoing the course shall develop the competence to design and develop a robot for a defined process. 
- The workshop also prepares you for - UiPath RPA Associate v1.0 Exam.

## Workshop Objective: Upon successful completion of this course, the individual should be able to:

- Learn the basic concepts of Robotic Process Automation.
- Develop familiarity and deep understanding of UiPath tools.
- Develop the ability to design and create robots for business processes independently.
- Develop skills required to pass UiPath RPA Associate v1.0 Exam.# 

# VARIABLES
This course covers two separate constructs that are fundamental in any software process:

**Variables and arguments**, or how data is collected, stored, processed and passed between various activities and workflows;
**Control flow**, or how the activities, instructions and function calls are executed throughout the process.

Here we learned :
- Differentiate between the most common types of variables and arguments used in UiPath;
- Create the variables needed in an automation project and configure their properties according to the specifications;
- Use the concept of Control Flow to build reliable and effective automation projects;
- Differentiate between the most common control flow statements used in UiPath (If statement, Loops and Switch) and configure them according to the specifications.

### Variables are containers that can hold multiple data entries (values) of the same data type. 
For example, emailAddress can be a variable that holds the value "rpadeveloper@uipath.com". The value of a variable can change through external input, data manipulation or passing from one activity to another. 
Variables are configured through their properties. You can set them in the Variables panel. 
The main properties in UiPath are:

- Name–
It should be as descriptive as possible to make your automation easy to read by other developers and to save time. 
- Type–
Defines what kind of data can be stored in the variable. In UiPath, the type is declared when the variable is created, however there are some specific types that are more generic and can accommodate different types of data. More about variables types right below.
- Default Value–
In general, variables have initial values that change throughout the process. If no initial value is assigned at the creation of the variable, there is generally a default rule that assigns a value.
- Scope–
The part of the workflow in which the variable can be used. Some variables can be global, others local. In real automation scenarios, there are many variables in use. Making multiple variables unnecessarily global can cause efficiency issues as well as possibility for confusion. 


### Creating Variables

There are 3 ways to create variables in UiPath:

- From the Variables panel – Open the Variables panel, select the ‘Create new Variable’ option, and fill in the fields as needed. When you need it, provide its name in the Designer panel or in the desired Properties field.
- From the Designer panel – Drag an activity with a variable field visible (i.e. ‘Assign’) and press Ctrl+K. Name it and then check its properties in the Variables panel.
- From the Properties panel – In the Properties panel of the activity, place the cursor in the field in which the variable is needed (i.e. Output) and press Ctrl+K. Name it and then check its properties in the Variables panel.

### [Demo - Creating Variables](https://github.com/Mechatronics-Engineering-CU/UiPath-RPA-Associate-v1.0/blob/main/Day-1/Creating%20Variables%20(Workflow).zip)
Creating variables using the Variables panel and the Designer panel
