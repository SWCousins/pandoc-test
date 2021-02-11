### **1.2 Lesson Plan: Let's Go!**

### **Overview** 

Today, it is crucial to get acquainted with each other and to set
learners' expectations. Getting to know your team and their skills is
important to your (the learner) success everywhere. Remember we will be
working with each other for another 12 weeks! Also, today we get an initial
introduction to our new environment (and will be our new home!), Visual Studio. As a
developer, this is where learners spend 100% of their time.

### **Learning Objectives**

By the end of class, students will be able to:

-   Define Agile development

-   Construct C# hello world

### **Class at a Glance** 

Today's lesson is heavy in facilitated discussions and live
walkthroughs. Starts with self introduction & setting overall
expectations. Then you would ensure computer readiness with installed
proper IDE and its operability. Later, you introduce Agile development.
And lastly, you would take learners to build the classical "Hello
World!" application.

### **Preparing For Class** 

This section sets the lesson expectations for the instructor.

-   Most learners are new to Agile development and do not know software development. So be ready to help explain and show them its importance.

## Slides
Slide deck for lesson: [M01L2_Slides](https://docs.google.com/presentation/d/e/2PACX-1vSOPQRd-lXNFN6Da4F9ya5WqxT2j1QfFkcQqCOIPTn5D-iw8BYBjrQXa3GgEkITe_zpNt1tWIUco9Jp/pub?start=false&loop=false&delayms=3000)

### **1. Instructor Do: Agile Development (80 min)**

We want our learners to understand what Agile Development is, and (most importantly) how we will be applying Agile Development in this boot camp, through daily standup (aka Scrum meetings), project planning & tracking (sprints, epics, & features), and retrospective. Also we introduce MS
AzDO as the tools of choice in helping us to plan and execute Agile
projects.

### **2. Instructor Do: What is Agile Development? (20 min)** 

Through a lecture session, introduce learners to software development
and quickly present Agile Development as the methodology of choice for
its performance and agility (as the name suggests!), and most
importantly proven track record. 

In February 2001, the [Agile Manifesto](http://agilemanifesto.org/) states:
"We are uncovering better ways of developing software by doing it and helping others do it."

Agile development is about an incremental and quick delivery of a working product. Agile development follows an iterative approach to software development where a set of features are implemented, tested and delivered in a set amount of time. Therefore the Agile development is about doing the work, keeping what worked and improving what did not. 

Briefly compare to the Waterfall methodology that is over than century old and was derived from the manufacturing method of Henry Ford's 1913 assembly line. Waterfall's main pitfall is the widening gap between business needs and delivering a working system in many cases the gap was measured in year!

Agile frameworks translated the agile development concepts into set of tools and processes for teams. Scrum is an agile framework among many like Kanban & Extreme Programming (XP). Furthermore, these frameworks were the basis for widespread processes such as DevOps and Continuous Integration/Continuous Deployment (CI/CD).

In Scrum, agile teams are relatively small, dynamic and cross-functional that include stakeholders for immediate and continuous feedback. Also, **project** work is captured as one of collection of **epics** describing business needs (what users want) and possible area of improvement such as developing an inventory system. Significant business initiatives are labeled as epics. So an epic breaks down into **features**. A feature is what a system can do such as track inventory. These features are then translated into implementable items known as **user stories** such as develop item inventory lookup. User stories are captured in the **backlog**. 
![Agile work item types, conceptual image](https://docs.microsoft.com/en-us/azure/devops/boards/work-items/guidance/media/ALM_PT_Agile_WIT_Artifacts.png)
Scrum teams select a set of user stories to accomplish over a timeframe usually between to 2 to 4 weeks called Sprint. During a **sprint**, scrum teams track and update status of various user stories through the **board**. 
![User Story workflow states, Agile process](https://docs.microsoft.com/en-us/azure/devops/boards/work-items/guidance/media/ALM_PT_Agile_WF_UserStory.png)
At the end of each sprint, the scrum team reviews the leftover work and discusses what went well, what to improve, and change the working plan going forward. This review at the end of a sprint is what is called a Retrospective. In Scrum meeting, Scrum teams meet daily to update on work status and alert for potential issue.

References: 
* https://www.redhat.com/en/topics/devops/what-is-agile-methodology#
* https://www.redhat.com/en/topics/devops/what-is-ci-cd
* https://www.redhat.com/en/topics/devops/what-is-application-lifecycle-management-alm
* https://docs.microsoft.com/en-us/azure/devops/boards/get-started/what-is-azure-boards?view=azure-devops&tabs=agile-process
* https://docs.microsoft.com/en-us/azure/devops/boards/get-started/plan-track-work?view=azure-devops&tabs=agile-process
* https://docs.microsoft.com/en-us/azure/devops/boards/get-started/?view=azure-devops

Every Instructor Do should include the following four critical aspects
in addition to the actual content that will be delivered:

-   Define the purpose of Agile methodology. Identify the elements of the Agile methodology. Using AzDO (Azure DevOps https://azure.microsoft.com/en-us/), create the Agile elements.

-   With this skill, learners can plan the execution of projects using the MS AzDO tool following the Agile methodology.

-   Learners are exploring the critical tool of the trades so far.

-   It's OK for learners to follow along during the AzDO demo. Keep reminding learners that they will get their hands into this tool. Also make sure to emphasize the importance of understanding the concepts as well as using the AzDO tool because the tool is our "First GoTo" step before working on any project.

### **3. Student Do: A Taste of AzDO! (30 min)** 

In this activity learners work in pairs to create Agile components in
AzDO. The activity focuses on using AzDO to create Agile components
step-by-step. Learners work in a group of two.

Make sure to introduce the activity and as well as how paired activity
works.

The activity walks learners through the steps to create Agile components
that were demonstrated by the instructor. Therefore instructors and TAs
should be walking around clarifying concepts and steps.

Learners may require additional hand-holding to create an account.
(Accounts on AzDO require MS email address?)
* go to: https://azure.microsoft.com/en-us/services/devops/
* Sign In/Create AzDO account
* Select "Start free" button to get into the Azure DevOps
* Create a project using the link in the upper-right-hand corner of the page.
* Complete project details (Name, description, Visibility - Private)
* Checkout the "Advanced" options:
  * Version Control: select Git
  * Work Item process: select Agile
* Invite your partner to collaborate with you on this project.
* Add an Epic
* Add a Feature,  "Track Shipments", 
  * Link to Epic, "Inventory Management" and 
  * Assign to yourself.
* Add a User Story, "Create Shipment".
  * Link User Story to Feature, and
  * Assign to teammate
* Checkout the board
  * Filter view to Feature - should see the "Track Shipments" feature.
  * Select Feature to edit
  * Add two (2) User Stories for this feature:
    * Search Shipments, and
    * Update Shipment
  * Add another feature, "Track Items"
    * Link to Epic, "Inventory Management" and 
    * Assign to yourself.
    * Add three (3) User Stories:
      * Create Item
      * Search Items
      * Update Item
* Checkout the Backlog
  * view User Stories - should have 6 User Stories.
  * Assign "Create Item", "Search Item", and "Update Item" to "iteration 1" using drag and drop.
  * Assign the other User Stories to "iteration 2"
* Checkout the Sprint
  * Note pre-defined iterations
  * Note "Planner Effort"
  * Select "Iteration 1" to view planned work
  * Select "Set dates" in the upper right-hand corner
    * Change "Iteration 1" to "Sprint 1"
    * Set start and end dates to today and this coming Friday, respectively.
  * Select the "Taskboard" view
    * Add new tasks to each User Story that must be done to close the User Story.
    * Assign tasks to teammates
  * Select the "Backlog" view
    * Expand User Stories
    * Note where tasks are listed

In this paired activity you will use AzDO to plan the execution of a
project. You will add a new project, and relevant epics. Then add a stories fidentify the features, create
features, group features into Sprints, assign features to resources
(developers).


### **4. Instructor Do: Review Agile & AzDO (10 min)**

Reinforce what is Agile methodology, its components, AzOD..etc.
Emphasize on setting the execution plan using AzDO before the start of
any development. The execution plan includes:

-   Creating project, features, & sprint

-   Using the 'Board' to monitor and to update Sprint progress..

### **5. BREAK (15 min)**

### **1. Instructor Do: Hello C# World! (100 min)**

The last topic of today is a hands-on one into C#. At this point,
learners are eagerly ready to get into C# after a day of readiness
confirmation (the team, the platform, and the methodology). C# is the
language of choice and the catalyst for this boot camp. The "Hello
World" program is the traditional way of learning computer languages.

Then, include a link to the class slides.

### **2. Student Do: "Hello C#" (30 min)** 

Learners create their first project using the Console Application (Web and Console ...) template.
In this activity learners create the traditional "Hello C#"
application. This application writes to the terminal.

Instructors and TAs should be roaming and offering help.

* From the VS IDE, choose "File" menu and select “New Solution"
* Select "App" under the "Web and Console" of the left column
* Select "Console Application" template.
* Name your project "Hello_CSharp". 
* Leave default for other options 
* Click "Create"
* Run the project by right-clicking on the project
* Confirm it outputs "Hello World!"
* In the Solution Explorer, find and open "Program.cs"
* Change program to say "Hello C#!" as well. So the output looks:
  Hello World!
  Hello C#!
* Run again

### **3. Student Do: "Hi, Neighbor!" (30 min)** 

Learners create another project using the Console Application template. 

In this paired programming activity, you will create a new project in VS which displays information about your programming partner (or "pair").

* In the Solution Explorer, right-click on the solution "Hello_CSharp" and select "Add" > "New Project..."
* Select "App" under the "Web and Console" of the left column
* Select "Console Application" template.
* Name your project "Hello_Neighor". 
* Leave default for other options 
* Click "Create"
* Run the project by right-clicking on the project
* Confirm it outputs "Hello World!"
* In the Solution Explorer, find and open "Program.cs"
  * Interview your pair to figure out what code to add to your Main method in order to produce the following output about your pair:
      ```cs
      Hi Neighbor! 
      My name is PAIR NAME. 
      I'm from PAIR HOME TOWN. 
      I have NUMBER siblings. 
      COLOR is my favorite color. 
      I listen to MUSIC GENRE music. 
      My favorite hobby is HOBBY. 
      Nice to meet you! Good bye!!!
      ```
This activity supports your ability to create VS projects, and write to the terminal.

### **4. Student Do: "Hi, Neighbor!" The Sequel (30 min)** 

Learners create another project using the Console Project template. In this activity, you will create a new project in VS which prompts for the same information as in the previous activity, "Hi, Neighbor!" After collecting your neighbor's details, your program displays the information again. This activity will support your ability to create VS projects, and read & write from & to the terminal.

* In the Solution Explorer, right-click on the solution "Hello_CSharp" and select "Add" > "New Project..."
* Select "App" under the "Web and Console" of the left column
* Select "Console Application" template.
* Name your project "Hello_Neighor_II". 
* Leave default for other options 
* Click "Create"
* In the Solution Explorer, find and open "Program.cs"
* Interview your pair to figure out what code to add to your Main method in order to produce the following output about your pair:
  ```cs
    Hi Neighbor! 
    What is your name? John
    What is your home town? NYC
    How many sibling do you have? 4
    What is your favorite color? Blue
    What kind of music do you listen to? Elevator Music
    What is your hobby? tennis
    Nice to meet you!
  ```
    **Challenge**: Instead of the last line saying "Nice to meet you", change it to say "Nice to meet you John!"
    
Hint: Click [here](https://docs.microsoft.com/en-us/dotnet/api/system.console.readline?view=netcore-3.1)  for more information on how to prompt users for input.

**5. Instructor Do: Review "Hello C#" (10 min)**

Make sure to

-   Go over the project creation process covering the available options,

-   Discuss common pitfalls learners might have faced.

### **7. BREAK (15 min)**

### **6. Instructor Do: Connect to Homework (X min)**

On the first day of the week, instructors will assign the homework
assignment to students by explaining the following:

-   What the homework is

-   Where the homework is located

-   When the homework is due

-   [Instructor-facing] Explain where the Instructor solution is

On the other days, instructors will remind the students about the
homework or describe how the lesson ties into the homework they are
working on.

### **End Class/Reflect (15 min)**

Reflect on the lesson and congratulate the students on completing it.
Explain what is coming next. What do students need to know about the
next class, unit, etc.?
