### Software Engineering Methods


Our chosen software engineering method was Agile, with a project “road-map” being created early in the development process as illustrated below. Having all the requirements for the final game from the customer, our roadmap helped us efficiently plan the execution and completion of this project, with the aim of delivering a high-quality game and all its supporting documents on time.  

We organised frequent team meetings, on average twice a week. These meetings served two key purposes:



* Providing a platform to discuss and agree upon key development decisions, such as game design and documentation. 
* Allowing each  team member to communicate their progress on their assigned tasks, and for new tasks to be assigned when necessary.

After creating an initial “road-map”, we then broke down the tasks according to the marks and assigned each member ~15 marks worth of tasks based on their skillset and our experience from the first assessment, so that every member had an equal amount of contribution towards the project. The frequent team meetings alongside the bi-weekly review meetings, in which we discussed task progression, allowed us to keep each other accountable for our productivity and ensured that we stay on track.


### Tools Used

**Communication and Collaboration**



* For our team meetings we either organised a discord call or met in-person. Using discord was an intuitive choice as it is a platform that we all have lots of experience with and therefore avoided an unnecessary learning curve.
* We created a Discord server for general communications throughout the project. This was crucial in allowing team members to ask clarifying questions without having to wait for the next meeting, avoiding any unnecessary obstructions to task progression.
* We used GitHub Issues in order to organise and keep track of our tasks throughout the project. Alongside the team meetings, this was crucial in keeping us organised by providing a visual representation of tasks that were completed, in progress and yet to begin.

**Website**



* We used GitHub pages to develop our website considering the teams previous experience with using the tool. 

**Architecture**



* We used PlantUML in order to create the abstract and concrete architecture diagrams as the team had prior experience in using this tool.

**Implementation**



* We chose to use IntelliJ as our IDE. This was due to both the ease of use offered by the tool, along with the fact that several team members had previous experience with the tool: it felt like the ideal choice to avoid unnecessary and time-consuming learning curves.
* We utilised the libGDX game development framework during the implementation of our game. Similarly, to our choice of IDE, this was largely influenced by the previous experience of the team. We were also aware that LibGDX was a popular choice amongst other teams and therefore our use of this framework may make it easier for another team to take over and expand our code.


### Alternatives considered



* We considered using other IDEs such as Eclipse for software implementation, however as mentioned previously we chose to use IntelliJ due to team members having previous experience with this IDE
* We also considered game engines other than libGDX in order to enable software development:
    * We considered using Unity, however we were discouraged from this choice by factors such as Unity’s reputation for largely outdated/incomplete documentation and the fact that many useful features are behind a paywall.
    * We also considered using the Unreal game engine, but quickly decided against this as it seemed inappropriate for developing what is a relatively small game and would cause the resulting game to be unnecessarily bloated.




## Part B


### Team Roles

During our initial team meeting we discussed assigning the following team roles.



* Meeting Chair: Ensuring organised and efficient team meetings that covered all necessary updates and decisions
* Secretary: Recording team decisions and keeping notes of the content discussed in each team meeting
* Librarian: Keeping track of documents and other resources, particularly ensuring that in-progress documents were regularly uploaded to the team shared google drive
* Report Editor: Overseeing document production, in particular ensuring that documentation progress was largely in line with the initial working plan

During this discussion we decided to combine the roles of librarian and report editor as they seemed like largely interdependent tasks. We then discussed who would be most appropriate for each role and agreed on the following assignments:



* Meeting Chair – Stan 
* Secretary – Jarred 
* Librarian/Report Editor – Alex 

Assigning these roles enabled a smooth and efficient team working process and helped to keep track of team progress.


### Task Assignments

Task assignment took place throughout the assessment process as detailed in part a of this document. When the time came to assign new tasks, we tried to keep these assignments in line with each person’s particular skill set in order to ensure efficiency as such throughout the project members mainly focussed on the particular aspects which they felt most comfortable with, usually due to previous experience, for example Joe took responsibility for website development and Alex produced the bulk of our game’s code.




## Part C


### Intro

Our first step in planning this assessment was to create a task breakdown table, as shown below (note that time estimates were rounded up to the nearest week e.g., 1.a. which we believed would only need one team meeting are 1 week)


<table>
  <tr>
   <td><strong><span style="text-decoration:underline;">Main Task No.</span></strong>
   </td>
   <td><strong><span style="text-decoration:underline;">Main Task</span></strong>
   </td>
   <td><strong><span style="text-decoration:underline;">Subtask letter.</span></strong>
   </td>
   <td><strong><span style="text-decoration:underline;">Subtask</span></strong>
   </td>
   <td><strong><span style="text-decoration:underline;">Dependencies</span></strong>
   </td>
   <td><strong><span style="text-decoration:underline;">Estimated time (weeks)</span></strong>
   </td>
   <td><strong><span style="text-decoration:underline;">Estimated Start and End Time (in Term Weeks)</span></strong>
   </td>
  </tr>
  <tr>
   <td>1
   </td>
   <td>Team Forming 
   </td>
   <td>a
   </td>
   <td>Team introductions and familiarisation
   </td>
   <td>-
   </td>
   <td>1
   </td>
   <td>Aut/3
   </td>
  </tr>
  <tr>
   <td>
   </td>
   <td>
   </td>
   <td>b
   </td>
   <td>Assigning team roles
   </td>
   <td>-
   </td>
   <td>1
   </td>
   <td>Aut/3
   </td>
  </tr>
  <tr>
   <td>2
   </td>
   <td>Identifying risks and requirements
   </td>
   <td>a
   </td>
   <td>Meeting to discuss initial ideas about requirements and risks, and compile a list of client questions
   </td>
   <td>-
   </td>
   <td>1
   </td>
   <td>Aut/4
   </td>
  </tr>
  <tr>
   <td>
   </td>
   <td>
   </td>
   <td>b
   </td>
   <td>Client meeting to discuss requirements and ask formulated questions
   </td>
   <td>2a
   </td>
   <td>1
   </td>
   <td>Aut/4
   </td>
  </tr>
  <tr>
   <td>
   </td>
   <td>
   </td>
   <td>c
   </td>
   <td>Team meeting to agree upon necessary requirements and relevant risks 
   </td>
   <td>2b
   </td>
   <td>1
   </td>
   <td>Aut/4
   </td>
  </tr>
  <tr>
   <td>
   </td>
   <td>
   </td>
   <td>d
   </td>
   <td>Creation of formal requirements representation (req1.b)
   </td>
   <td>2c
   </td>
   <td>1
   </td>
   <td>Aut/5
   </td>
  </tr>
  <tr>
   <td>
   </td>
   <td>
   </td>
   <td>e
   </td>
   <td>Creation of formal risk representation (risk1.b)
   </td>
   <td>2c
   </td>
   <td>1
   </td>
   <td>Aut/5
   </td>
  </tr>
  <tr>
   <td>
   </td>
   <td>
   </td>
   <td>f
   </td>
   <td>Written explanations of our requirement and risk process (req1.and risk1.a)
   </td>
   <td>2d
   </td>
   <td>1
   </td>
   <td>Aut/5
   </td>
  </tr>
  <tr>
   <td>3
   </td>
   <td>Website
   </td>
   <td>a
   </td>
   <td>Create initial website (not yet populated with necessary documents)
   </td>
   <td>-
   </td>
   <td>3
   </td>
   <td>Aut/6
   </td>
  </tr>
  <tr>
   <td>
   </td>
   <td>
   </td>
   <td>b
   </td>
   <td>Add all necessary documents to website
   </td>
   <td>5b, 3a
   </td>
   <td>1
   </td>
   <td>Spr/3
   </td>
  </tr>
  <tr>
   <td>4
   </td>
   <td>Game Design
   </td>
   <td>a
   </td>
   <td>Team meeting to discuss and agree upon game design ideas
   </td>
   <td>2c
   </td>
   <td>1
   </td>
   <td>Aut/6
   </td>
  </tr>
  <tr>
   <td>
   </td>
   <td>
   </td>
   <td>b
   </td>
   <td>Creation of abstract architecture diagrams
   </td>
   <td>4a
   </td>
   <td>2
   </td>
   <td>Aut/7
   </td>
  </tr>
  <tr>
   <td>5
   </td>
   <td>Implementation
   </td>
   <td>a
   </td>
   <td>Creation of functional, commented code
   </td>
   <td>4b
   </td>
   <td>5
   </td>
   <td>Spr/2
   </td>
  </tr>
  <tr>
   <td>
   </td>
   <td>
   </td>
   <td>b
   </td>
   <td>Explanation of non-implemented features (impl1)
   </td>
   <td>4a
   </td>
   <td>1
   </td>
   <td>Spr/2
   </td>
  </tr>
  <tr>
   <td>
   </td>
   <td>
   </td>
   <td>c
   </td>
   <td>Creation of reflective concrete architecture diagrams
   </td>
   <td>5a
   </td>
   <td>1
   </td>
   <td>Spr/3
   </td>
  </tr>
  <tr>
   <td>6
   </td>
   <td>Submission 
   </td>
   <td>a
   </td>
   <td>Completing outstanding reflective documentation
   </td>
   <td>5b
   </td>
   <td>1
   </td>
   <td>Spr/3
   </td>
  </tr>
  <tr>
   <td>
   </td>
   <td>
   </td>
   <td>b
   </td>
   <td>Compiling documentation into PDFs, and combining this with code and website into a submittable zip file
   </td>
   <td>6a
   </td>
   <td>1
   </td>
   <td>Spr/3
   </td>
  </tr>
  <tr>
   <td>
   </td>
   <td>
   </td>
   <td>c
   </td>
   <td>Completing self and peer assessment
   </td>
   <td>-
   </td>
   <td>1
   </td>
   <td>Spr/3
   </td>
  </tr>
</table>


We then used this table in order to create an initial Gantt chart to show a theoretical schedule for when each task would be completed  for assessment 1(as shown below;)




![alt_text](images/image1.png "image_tooltip")


At each team meeting our assigned secretary, Jarred, would create meeting notes which he would then upload to our shared google drive. At the end of each week, we then used these notes in order to create a ‘snapshot’ of our team progress (shown on website snapshot page).

These snap-shots would be created by taking a condensed version of the task breakdown table and colour coding the tasks which were due to be done at this point in the project. With the following colour connotations: 



* Red – Not started 
* Orange – In progress
* Green – Completed
