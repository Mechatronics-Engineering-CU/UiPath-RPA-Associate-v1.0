## Dated: 22-08-2021"
To begin our journey towards becoming a RPA (robotics process automation) developer, let us begin with **Getting Started Course"
### At the end one will be able to : 
Describe how the UiPath core RPA components (Studio, Orchestrator and Robot with Assistant) work together.
Differentiate between the two types of UiPath robots - attended and unattended.
Set up an attended environment with Studio and Assistant, connected to Orchestrator.
List the key skills required to become an Associate level developer.
Build an automation project following instructions. 
Access the UiPath Community ecosystem. 

## Pre-Reuisites To Start

- Set up a UiPath Automation Cloud account
    - You will need the account to be able to:
    - install Studio, Assistant and Robot.
    - distribute attended and unattended licenses.
    - provision robots and run jobs.


## Define RPA and automation and explain their impact on digital transformation

**Here I understood about the Challenge common biases about RPA, automation, and digital transformation in general.**
- Two overused expressions that describe today’s context are 
    - VUCA (Volatility, Uncertainty, Complexity, Ambiguity) and 
    - digital transformation.

    - But what do they really mean? 
    - Change, transformation, ambiguity - these are anxiety feeding words. 
    - The result? Myths and misconceptions. 
    - **Implementing RPA is a business transformation, a change in the processes, and an ambiguous affair. Naturally, myths have followed.**
- Let us understand some of the most common myths about RPA and digital transformation. 
    - By establishing a common language. 
    - Just to make sure that when you read RPA you don't think of the Rise of the Planet of Apes movie.
### what RPA is.? 
- RPA (Robotic Process Automation) is the technology that enables software 'robots' to carry out repetitive, rule-based digital tasks.
- Humans typically perform these tasks through the user interface, using the mouse and keyboard. 
- RPA robots are capable of mimicking the human actions, and they are typically more accurate, faster, and more consistent at it.
- Combined with Artificial Intelligence (AI), RPA can target more sophisticated work. 
- This opens up endless possibilities on the path towards the fully automated enterprise™️.
- **Automation** is a term that describes more accurately these possibilities that exceed the sphere of basic RPA. 
- Sometimes we use these two terms interchangeably, given that RPA is still at the core of automation.

**Myth 1: Automation will replace humans in the workforce. **
- It’s true that many business tasks previously performed by human employees can now be automated with RPA.
- Yet, even with the rise of artificial intelligence (AI), these technologies are not entirely independent from humans, nor are they currently able to reproduce the higher-level thinking of which humans are capable.
- At the same time, the human workforce will certainly be augmented by RPA. Companies and their employees will benefit from it. For example:
- RPA allows employees to increase their efficiency and productivity, and employees will be able to focus on higher-level activities, such as sales or marketing. 
- These activities create business value and foster deeper engagement with customers.
- Employee roles are redefined, and talent is reallocated to focus on customer facing tasks in the front office. 
- There will no longer be a need to focus on tedious, back-office tasks.
**Myth 2: RPA software robots are 100% accurate.**
- RPA software robots can make mistakes. The robots will follow to the letter the instructions given. If the process is flawed, since the RPA robot cannot improve any defects, the automation will be flawed. 
- It is up for the human employees to spot early in the automation process any mistakes present in the instructions. Unless detected, these errors might mean the work will need to be redone, either manually or by re-automating tasks after the mistakes have been fixed. 

**Myth 3: Any process that can be automated with RPA can also be automated using APIs and programming languages.**
- It is true, but automation done by APIs and programming languages consumes more resources. 
- Typically, the processes need to be first redesigned, and only then automated. RPA, on the other hand, is non-invasive, because it aims to automate the processes as they are carried out by the human users. 
- This makes it a scalable approach.
**Their CEO, Daniel Dines says it best: "When people build business processes, they work with different systems. And they always touch the system by looking at the user interface, by looking at the human readable interfaces of these systems. And when you go and automate them, it's difficult to translate into APIs. So, our approach is just to replicate humans, using the same tools, the same technologies that are familiar to business people. Of course, you can take one process, build an IT project, throw developers to it and be successful. But you cannot do it at the scale that an enterprise has. RPA is the only technology that can work at the large scale."**

**Myth 4: RPA will not work in my industry.**
- There’s a common misconception that RPA is only productive in certain industries, such as finance. 
- However, automatable tasks exist in every industry. RPA can be applied to almost any repetitive, rules-based, high-volume business activity in any industry. 
- Here are a couple of scenarios in which RPA can be used: 
    - order processing in retail
    - claims processing in the insurance industry
    - fraud detection in banks
    - communication with customers in the manufacturing industry
    - patient scheduling in the healthcare industry
- And with the rise of citizen development through no-code software, even CEOs can personally automate some of their daily tasks.

**Myth 5: RPA is not worth the cost of investment.**
- RPA does have initial implementation costs, but the investment is not as significant as a business process management software (BPM) or enterprise resource planning (ERP) implementation.  
- At the same time, RPA provides rapid internal cost reduction and significant increases in ROI. 
- Some of the benefits are:
    - Operating costs cut down
    - Task efficiency increased
    - Reduced compliance errors and risks
    - Improved customer experience
    - Increased employee satisfaction and engagement
    - Accelerated digital transformation

**Myth 6: Digital transformation is a strategic, purely technological project, and has to be managed centrally.**
- Beyond the obvious technological focus, digital transformation is also about building the foundation of talent and a centralized function that will deliver the transformation to the organization.
- UiPath envisions enabling every customer to deliver ‘a robot for every person' in their organization.
-  A robot for every person allows all employees to work smarter by using software robots to assist with their everyday tasks. 
-  This could mean:
    - a shift in the organizational culture to include automation as a normal part of the working day.
    - employee upskilling to empower all employees to use or develop automation.

#### RPA is the technology that...
allows computer software to mimic actions typically performed by humans. 
These actions are mostly interactions with digital systems and are carried out within business processes. 

### Describe how humans and robots can work together.
- The computer software that executes the operations is called a Robot. 
- The RPA robots can:
  - Extract structured data from documents,
  - Log into and run applications,
  - Open emails and attachments,
  - Fill in forms,
  - Read and write to databases,
  - Make calculations,
  - Connect to other systems,
  - and much more. 
The robots interact with data and applications just as human workers do, using the mouse, the keyboard, and the User Interfaces.

**What do all the above examples have in common?**
- RPA primarily targets processes that are 
  - highly manual, 
  - repetitive, 
  - rule-based, and 
  - have a low exception rate and 
  - a standard electronic readable input.
- **The human** gets to keep the high-level activities for themselves: 
    - face-to-face interactions or 
    - coming up with complex strategies. 
    - They can be dedicated to the things that make them irreplaceable.
 **Depending on the automation scenario, the work done in tandem by humans and robots can be described as:**
 - On-demand - the human user manually triggers the robot when needed, to execute part or a full business process.
 - Side-by-side - robots work behind the scenes while the human user maintains control of the mouse and keyboard.
 - Interactive - the user engages with robots before, during and/or after the execution.
 - Always-on - robots start processes automatically as the user goes about their day.
 - Interconnected - a coordinated collection of processes run and react to each other, with humans and robots exchanging inputs.
 
 **let's find out how RPA can combine multiple technologies to be more powerful!**
## Automation Is Driving the Digital Transformation
### What is digital transformation?
- In the answers to the truth or myth quiz, we introduced some of the concepts of digital transformation and the facts that debunk the myths:
- Digital transformation is directly influenced by the people adopting it, not the technology.
- New skills, new roles, a culture of openness to change, and permanent external exploration make digital transformation more than a strategic and technological project.
- Digital transformation can be anything from IT infrastructure modernization to optimization or new digital business models. 
- Enter RPA, a new digital business model, which focuses on digital optimization. More specifically, on the digital workspace optimization.
- Digital transformation is also widely used in the public sector to describe initiatives such as putting services online or legacy modernization. 
- RPA can accelerate these processes, for example by moving data from scanned documents into digital applications, freeing the human in charge of this task to perform more high-value activities.

### Anticipation

- Companies that try out RPA as part of their digital transformation programs obtain value right away by automating simple tasks like processing and moving data between systems. 
- To reach the full potential of digital transformation, companies need to expand RPA with a combination of technologies enabling the fully automated enterprise, keeping RPA as the center of gravity. 
- This means adding to the existing RPA capabilities the possibility to:
    - scientifically identify the business processes most suited for automation.
    - have robots learn new skills and gradually improve their work.
    - automate basic to complex end-to-end business and enterprise process.
    - have a thorough and unbiased view on the impact of automation, next moves and what can be further improved.


