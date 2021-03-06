# Project Title: Dungeon Crawler

### Statement
Describe your project. Why is it interesting? Why is it interesting to you personally? What do you hope to learn?  
The basic idea is to use AVL tree/regular tree to create a dungeon crawler in which we use the image libraries to display monsters to the player,and based on the level of the tree the user is on the difficulty of the monster the player will be able to obtain more epxerience to level up and go to higher difficulties.The reason this is interesting personally is because dungeon crawlers are simple but can be difficult and entertaining at the same time.We hope to learn how to use what we have previosly learned and apply it in different ways such as using lambda to create a way to calculate accuracy, create a random number generator for player stat gain such as health,mana.

### Analysis
Explain what approaches from class you will bring to bear on the project. Be explicit: e.g., will you use recursion? How? Will you use map/filter/reduce? How? Will you use data abstraction? Will you use object-orientation? Will you use functional approaches to processing your data? Will you use state-modification approaches? A combination?


We will use object orientation for the initial creation of the lower levels of the tree to control the beggining difficulty of the game and for the final boss of the game this way we can control the begging and end of the enviroment everything else is left to the player.



The idea here is to identify what ideas from the class you will use in carrying out your project. 

### Data set or other source materials

The data that we will be working on will be writen by ourselves.

How will you convert that data into a form usable for your project?  

Do your homework here: if you are pulling data from somewhere, actually go download it and look at it. Explain in some detail what your plan is for accomplishing the necessary processing.

If you are using some other starting materails, explain what they are. Basically: anything you plan to use that isn't code.

### Deliverable and Demonstration
Explain exactly what you'll have at the end. What will it be able to do at the live demo?

What exactly will you produce at the end of the project? A piece of software, yes, but what will it do? Here are some questions to think about (and answer depending on your application).

Will it run on some data, like batch mode? Will you present some analytical results of the processing? How can it be re-run on different source data?

Will it be interactive? Can you show it working? This project involves a live demo, so interactivity is good.

At the end we will have an interactive dungeon crawler that has the player move from level to level, and encounting monsters which they will battle with text based decisions such as fighting, running away,healing.If the are to choose fighting there are chances that  they will will miss the enemy but there is a chance that the enemmy will also miss, if they win the battle they gain experience and move up ,this will repeat until they reach the boss.

-Potential changes are being able to go up and down by choice but problems with this is that we will have to randomly generate the boss with higher parameters to increase difficulty.

### Evaluation of Results
How will you know if you are successful? 
The player will start at the bottom and be able to move their way through the levels of the dungeon gaining experience from killing monsters, leveling up and eveutally reach the final boss.

## Architecture Diagram
Upload the architecture diagram you made for your slide presentation to your repository, and include it in-line here.

Create several paragraphs of narrative to explain the pieces and how they interoperate.

## Schedule
Explain how you will go from proposal to finished product. 

There are three deliverable milestones to explicitly define, below.

The nature of deliverables depend on your project, but may include things like processed data ready for import, core algorithms implemented, interface design prototyped, etc. 

You will be expected to turn in code, documentation, and data (as appropriate) at each of these stages.

Write concrete steps for your schedule to move from concept to working system. 

### First Milestone (Fri Apr 15)  
What exactly will be turned in on this day?  

Traversing through the dungeon(tree)  
GUI for showing Monsters using Images library (optional)  

### Second Milestone (Fri Apr 22)  
What exactly will be turned in on this day?   

Create monster objects and their parameters  
Modification of Player object with lambda functions  

### Final Presentation (last week of semester)
What additionally will be done in the last chunk of time?  

Aplication of Encounter options  

## Group Responsibilities
Here each group member gets a section where they, as an individual, detail what they are responsible for in this project. Each group member writes their own Responsibility section. Include the milestones and final deliverable.  

**Additional instructions for teams of three:** 
* Remember that you must have prior written permission to work in groups of three (specifically, an approved `FP3` team declaration submission).
* The team must nominate a lead. This person is primarily responsible for code integration. This work may be shared, but the team lead has default responsibility.
* The team lead has full partner implementation responsibilities also.
* Identify who is team lead.

In the headings below, replace the silly names and GitHub handles with your actual ones.

### Susan Scheme @susanscheme
will write the....

### Leonard Lambda @lennylambda
will work on...

### Frank Functions @frankiefunk 
Frank is team lead. Additionally, Frank will work on...   
