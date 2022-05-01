<!-----

Yay, no errors, warnings, or alerts!

Conversion time: 0.225 seconds.


Using this Markdown file:

1. Paste this output into your source file.
2. See the notes and action items below regarding this conversion run.
3. Check the rendered output (headings, lists, code blocks, tables) for proper
   formatting and use a linkchecker before you publish this page.

Conversion notes:

* Docs to Markdown version 1.0β33
* Thu Apr 14 2022 03:55:53 GMT-0700 (PDT)
* Source doc: Untitled document
----->


# Change report:

# Requirements

**<span style="text-decoration:underline;">8948b74: Removed Unnecessary requirements</span>**

We felt that some of the requirements the team had previously implemented did not appear in any brief, weren’t asked for by the customer or were just deemed to be redundant. For example the requirements ‘FR_BOSS_UNLOCK_TRACKING’ and ‘FR_BOSS_SPAWN’ involved the use of a boss that was not mentioned in the brief nor customer interviews and therefore had no justification to appear in requirements. This will change R14 as the estimation of the scope of the project would be significantly increased if these requirements were left in.

**<span style="text-decoration:underline;">ef9f295: Added requirements relevant to the second stage of the assessment</span>**

Updated the requirements page to include the new requirements that we received in the brief. 

**<span style="text-decoration:underline;">9845cef: Fixed Formatting</span>**

Fixed formatting mistakes made when editing the markdown table for requirements.

**<span style="text-decoration:underline;">E1a2386 & 396806d: Changes to priority for requirements</span>**

We felt that the use of ‘shall’ and ‘May’ were redundant measures of a requirement’s priority and didn't help management of requirements. For this reason, we changed the priorities of the requirements to high/medium/low which we feel is a clearer measure for anyone reading and helps justify why we went in specific directions with our implementation.

**<span style="text-decoration:underline;">  </span>**

**<span style="text-decoration:underline;">6ec20bc: Changed word ‘money’ to ‘plunder’ to match wording in the code</span>**

We noticed some inconsistencies in wording between the documentation and implementation sides of this project. Most notably, in the documentation section the word ‘money’ is consistently used while in the code this same thing is referred to as ‘plunder’. Not only did we feel that ‘plunder’ fit the theme but it was also the word used in the brief which led us to change the documentation in favour of keeping consistency. 

**<span style="text-decoration:underline;">9917596: Cleared up points/XP confusion</span>**

A further inconsistency we noted was the lack of clarity between ‘points’ and ‘XP’ which was pointed out in the feedback as an issue. The team felt it was best to merge the two so we ended up merging the two and using ‘XP’ for both.

# Method Selection and PLanning

**<span style="text-decoration:underline;">05e5339: Changed Software Engineering method</span>**

We decided to change the engineering method from Plan-based to Agile as we divided the team into two parts, Implementation and Documentation, so that we could work on all parts of the assessments simultaneously. We also discussed about using the Scrum framework instead of Plan based and had sprints that were 1 weeklong.

**<span style="text-decoration:underline;">bbe4ad3: Added another key point of discussion for weekly meetings</span>**

Instead of just discussing about game design as the purpose of our weekly meetings, we changed it and added “documentation” as well, as it was necessary to be up to date with both aspects of the assessment as they go hand-in-hand with one another.

**<span style="text-decoration:underline;">e9c1a4e: Changed Communication and Collaboration Tools</span>**

We decided to change the Team Meeting tool from Zoom to Discord and in-person meetings as in-person meetings allowed us to separate into smaller teams and work together while allowing us to keep real-time progress of the project and Discord calls were more preferred as compared to zoom as it avoided the hassle of having a Meeting ID and Password to join a meeting and the screensharing capability provided on discord was much better than that provided by zoom, according to the groups point of view.

In addition to having a discord server for general project discussions, we decided to create a “To-Do List” channel, where a team member would post notes regarding what was discussed in the meeting and what needed to be done by the next scheduled meeting.

After some discussions, we changed our task progression tool from Trello to GitHub Issues as this was something new that we thought of trying and also the fact that using GitHub issues, we could keep track of all the commits and why something was changed from the previous project, which would later on help us when writing our change report.

**<span style="text-decoration:underline;">299e9c9: Changed tools used to create Architectures</span>**

Instead of using draw.io for Abstract architecture and plantuml for Concrete architecture, we used plantuml for both as well as for our Gantt Charts, as we had used this tool for the first assessment and found it relatively simple to use. 

**<span style="text-decoration:underline;">25d9e44: Added an explanation for our teams’ approach towards Quality Control</span>**

We added a paragraph explaining how we implemented a Quality Control Process to ensure that our work was of high-quality, and this also helped with mitigating the risk of a team member being unable to complete their tasks due to any justifiable reason, as others would know where to pick-up from.

**<span style="text-decoration:underline;">28638b3: Added a Testing tool</span>**

We added a small paragraph where we discussed the testing tool we used (gdx-testing) and why we used it.

**<span style="text-decoration:underline;">44fbf5d: Updated Team Management and Changed how Tasks were assigned</span>**

We combined all the roles discussed by the previous team into one role (Team leader) as they seemed largely interdependent and we added two additional roles, Implementation leader and Documentation leader, where 2 additional members were assigned to each role after a group discussion.

We also changed how tasks were assigned (assigning tasks as the project progressed) to how our team seemed fit, which was by calculating the marks of each section required and evenly distributing tasks to team members based on the calculated marks, ensuring everyone had more/less a similar amount of contribution towards the project and nothing will be left/forgotten till the last minute.

**<span style="text-decoration:underline;">ff9ba36: Changed all of Part C (Systematic Project Plan)</span>**

Instead of continuing with the previous teams’ approach of having a task breakdown table followed by an initial Gantt chart showing a theoretical schedule for when each task should be completed, we decided to design an initial roadmap of all the major tasks that needed to be done (as a Gantt chart) which also showed a theoretical schedule of when each of these tasks needed to be completed. We then justified how we went about creating this chart and why we scheduled the tasks the way we did. We then decided to update this initial Gantt chart every week based on task progression/completion in that week, depicting the evolution of our plan throughout the project. We then added the final Gantt chart to the document so that it would be easy to compare the changes made with regards to the initial plan and all the intermediate Gantt charts can be found on our website.

Furthermore, instead of creating snapshots by condensing the roadmap to keep track of our progress and using a colour-coding scheme to highlight tasks that were due, we decided to use a colour-coding scheme to assign tasks to individuals/teams in the form of a Gantt chart.

