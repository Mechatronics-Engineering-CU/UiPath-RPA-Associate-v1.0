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

### [Demo Files - Creating Variables](https://github.com/Mechatronics-Engineering-CU/UiPath-RPA-Associate-v1.0/blob/main/Day-1/Creating%20Variables%20(Workflow).zip)
Creating variables using the Variables panel and the Designer panel

#### RECAP
We have started the project as sequence and created the variable username of type String and global scope.
We have used an Input Dialog activity and entered the name of the variable (username) in the Result property field of the activity. This activity will store the user's input in the username variable.
We have defined a new String variable (named status) and populated it with the value " - is logged in" using the Assign activity.
We have used a Log Message activity to print the values of the 2 variables in the Output panel, using the expression username + status.

#### Good Case Practices - Creating Variables
Use clear and consistent naming conventions - one of the most common is Camel case (each word in the middle of the phrase is capitalized)
Make sure you define the scope of each variable correctly - remember that a variable defined on a limited scope cannot be used globally. At the same time, in real automation scenarios, it is crucial for variables to be defined only in the scope in which they are used. Making multiple variables unnecessarily global can cause efficiency issues as well as possibility for confusion.

### Arguments

In UiPath, the scope of a variable cannot exceed the workflow in which it was defined. Since business automation projects rarely consist of single workflows, arguments have to be used.

Arguments are very similar to variables – they store data dynamically, they have the same data types and they support the same methods. The difference is that they pass data between workflows, and they have an additional property for this – the direction from/to which the data is passed. The direction can be In, Out and In/Out.

### Data Types
With some exceptions that we will discuss separately, the data types in UiPath are borrowed from VB.Net. Below are some of the most common ones used:

#### Numeric (category)
Used to store numbers. There are different sub-types of numerical variables:

Int32 - System.Int32 (signed integers): 10, 299, -100, 0x69 
Long - System.Int64 (long integers): 5435435343O, -11332424D
Double - System.Double (allows decimals, 15-16 digits precision): 19.1234567891011

####  Boolean
System.Boolean: Used to store one of two values – true or false.


#### Date and Time (category)
DateTime - System.DateTime: Used to store specific time coordinates (mm/dd/yyyy hh:mm:ss). This kind of variable provides a series of specific processing methods (subtracting days, calculating time remaining vs. today, and so on). For example, to get the current time, assign the expression DateTime.Now to a variable of type DateTime.
TimeSpan - System.TimeSpan: Used to store information about a duration (dd:hh:mm:ss). You can use it to measure the duration between two variables of the type DateTime. For example, you can save the time at the start of the process in one variable (of type DateTime), the time at the end in another (of type DateTime) and store the difference in a variable of type TimeSpan.

#### String
System.String: Used to store text. This type of data comes with many specific methods of processing, and will be addressed in depth in another lesson, namely Data Manipulation.

#### Collection (category)
This category reunites all the collections of objects, with each object being identified through its index in the collection. Collections are largely used for handling and processing complex data. Some of the most encountered collections are:

#### Array - used to store multiple values of the same data type. The size (number of objects) is defined at creation; 
#### List - System.Collections.Generic.List<T>: used to store multiple values of the same data type, just like Arrays. Unlike Arrays, their size is dynamic;
Dictionary - System.Collections.Generic.Dictionary<TKey, TValue>: used to store objects in the form of (key, value) pairs, where each of the two can be of a separate data type.

#### GenericValue
This is a UiPath proprietary variable type that can store any kind of data, including text, numbers, dates, and arrays. This type is mainly used in activities in which we are not sure what type of data we will receive, yet in general the use of this is temporary.
      
#### [Demo Files - Creating Array Variables](https://github.com/Mechatronics-Engineering-CU/UiPath-RPA-Associate-v1.0/blob/main/Day-1/Arrays%20(Workflow).zip)
Most of the examples shown up to this point were simple variables, that can store a single value at a time. It’s time to look into the collection variables, starting with array variables.
**What is it?**
The array variable is a type of variable that enables storing multiple values of the same data type. Think of it as a group of elements with a size that is defined at creation, and each item can be identified by its index.
In UiPath Studio, you can create arrays of numbers, of strings, of Boolean values and so on.
#### What are some business scenarios in which I will use arrays?
When we want to save the names of the months to a variable
When a fixed collection of bank accounts has to be stored and used in the payment process
When all the invoices paid in the previous month have to be processed
When the names of the employees in a certain unit have to be verified in a database

#### GenericValue Variables

While developing an automation process, there are situations where you are not sure what type of data will be retrieved. In order to find out, you need to run a few tests using a variable with a broad enough spectrum that can catch any type of input. This is where we recommend temporarily using GenericValue Variables.
#### What is it?
The GenericValue (UiPath.Core.GenericValue) variable is a type of variable particular to UiPath that can store any kind of data, including text, numbers, dates, and arrays.

UiPath Studio has an automatic conversion mechanism of GenericValue variables, which you can guide towards the desired outcome by carefully defining their expressions. Please note that the first element in your expression is used as a guideline for what operation Studio performs. For example, when you try to add two GenericValue variables, if the first one in the expression is defined as a String, the result is the concatenation of the two. If it is defined as an Integer, the result is their sum.
#### What are some business scenarios in which I will use GenericValue variables?
Data is extracted from a UI field and forwarded to another workflow without processing
Two versions of the same Excel file are being compared column by column. The columns are different in terms of data type, the only relevant thing is which entries have changes 
      
      
# Contol Flow
It is the order in which individual statements, instructions or function calls are executed or evaluated in a software project.
#### There are 2 concepts through which the control flow is enacted:

The type of automation project
There are 4 predefined types of workflows – Sequence, Flowchart, State Machine and Global Exception Handler.

We are covering them in depth in the “Project Organization” course, for now let’s focus on the difference between sequences and flowcharts, as we will use both extensively in our examples throughout the entire course.

In sequences, the process steps flow in a clear succession. Decision trees are rarely used. Activities in sequences are easier to read and maintain, thus, they are highly recommended for simple, linear workflows.
In flowcharts, the individual activities are a bit more difficult to read and edit, but the flows between them are much clearer. Use flowcharts when decision points and branching are needed in order to accommodate complex scenarios, workarounds and decision mechanisms. 
#### The control flow statements
The activities and methods used to define the decisions to be made during the execution of a workflow. The most common control flow statements are the if/else decision, the loops and the switch. Let's focus on them one by one.
#### [Demo Files for IF](https://github.com/Mechatronics-Engineering-CU/UiPath-RPA-Associate-v1.0/blob/main/Day-1/If%20Statement%20in%20Sequence.zip) 
In UiPath, the If statement is exactly how you’d expect it to be: 

The condition that is verified (with 2 potential outcomes – true or false)
The set of actions to be executed when the condition is true (the Then branch)
The set of actions to be executed when the condition is false (the Else branch)
 

What is different is that, based on the chosen type of automation project, there are 2 corresponding activities that fulfill the If statement role:

The If Statement in sequences
The Flow Decision in flowcharts
Moreover, the If decision can be used as an operator inside activities.
#### What are some business scenarios in which I will use the If statement?
Whenever there are two courses of action that are not arbitrary, an If statement will most likely be used:

Checking the status of a payment (done/not done) and performing a set of operations in each case
Making sure that the outcome of the previous operation in the sequence is successful
Checking the balance of an account to ensure that there is enough money to pay an invoice
Checking if something has happened in a system, like if an element or an image exists and performing an action based on that.

#### Let's recap the Activities and Methods used

If statements in a Sequence

We used an 'Input Dialog' activity to get an input value from the user and store it in an Int32 variable.
We used an 'If Sequence' activity and defined the condition using the mod operator to check the remainder in a division: (year mod 4 = 0 and  year mod 100 <> 0) or (year mod 400 = 0). If the condition is true, the value is a leap year.
If Statements in a Flowchart

We used an 'Input Dialog' activity to get the input value from the user and stored it in an Int32 variable.
We added a 'Flow Decision' activity with the same condition as in the 'If Statement' activity above: (year mod 4 = 0 and  year mod 100 <> 0) or (year mod 400 = 0)
VB.Net If Operator

We defined the project as a sequence and used an 'Input Dialog' activity to get the input value from the user and store it in an Int32 variable.
We defined a String variable and used it as an output of an 'Assign' activity. In the value field of the 'Assign' activity, we used the same expression from the previous examples, followed by 2 pieces of text between quotation marks - the first to be assigned when the condition is true. The full expression looks like this: message = if ((year mod 4 = 0 and  year mod 100 <> 0) or (year mod 400 = 0) , “Leap Year”, “Not a leap Year”).
