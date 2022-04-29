## Risk assessment and mitigation

This section will outline the risks that we have established will be possible to occur in this project along with some more detail about them. 

To create thes risks we will follow the process that Ian Somemrville details in his book *Software Engineering* [1]. Sommerville sums up the process of creating a risk assesment in 4 steps. 
  - The first step is to discuss the risks, listing them and tabulating them. To do this he suggests going through easch stage of the project you have planned and and identifying possible risks. 
  - The second stage is to analyse the risks you have identified. This involves creating a measurement of how likely the risk is to happen. In this project we chose to use the characters 'H' 'M' and 'L' to stand for High risk, Medium Risk and Low risk. This seems descriptive enough given the small scale of the project and the fact that the product has no safety issues in terms of damage to people or property if something goes wrong. 
  - Sommerville describes the next step as the mitigation step, where we created a plan and decided on how these risks will be prevented or alternatively how we will act if they do arrise. 
  - Step four is to monitor the risks and creating revisions to the risk assesment if the need arises. To do this we have assigned owners to each risk to ensure someone is monitoring it as we do not have a specifically assigned risk assessor.
  
The risks to the project are presented in the table below, with the following information about each one: 

* An ID- to identify individual risks
* Category type- helps to read the table quickly and find the specific risks
* Description- details what the risk is 
* Potential consequence- explains what could go wrong and why this risk needs solving
* Monitoring- shows whether the risk is happening, indicating if it is of immediate concern
* Likelihood and severity- allows the team to make a judgement about how much of a priority this risk is in solving or preventing
* Mitigation - details the steps that need to be, or are being taken to prevent the risk from happening. 
* Owner- shows who is responsible for either solving the problem or arranging for it to be solved and monitoring the likelihood

There is significant detail about the risks to the programming and game itself because each item can affect the overall game, and are distinct issues. The likelihood and severity of the risks are also included because this tells us which risk to prioritise in mitigating, and each item has an ‘owner’- without one, the responsibility can be unclear, causing the issue to not be solved. If a risk is owned by someone this means that it is their responsibility to log any occurences of this and decide if the mitigiation or likelihood needs changing. This may be done in the form of a message to the person editing this document or editing the document directly. These updates will be date stamped. 

| ID | Type | Description | Consequences | Monitoring | Likelihood | Severity | Mitigation | Owner |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R1 | Technology | AI interaction proves infeasible to implement | Opposing ships will behave differently | not currently happening | H | H | Fake AI via scripted interaction | Katie |
| R2 | Product | NPC targeting of player ship not enough or too challenging | Game may not be enjoyable | unknown - ship combat not implemented until assignment 2 | M | M | Player test gameplay and adjust parameters | Cody |
| R3 | Technology | AI decision making too slow to be convincing | Game may not be enjoyable | not currently happening | L | M | Fake AI via scripted interaction | Cody |
| R4 | Technology | Physics engine being unstable | Player and projectiles may not interact with the other elements in the program correctly. | not currently happening | M | M | Make it difficult to get into an unstable situation | Jacob |
| R5 | Technology | Cost of high res textures cause high loading time | Game may have a large loading time, which may cause the user to think the program is broken | not currently happening | L | L | Minimal resources are loaded (possibly on another thread) or compression used  | Jacob |
| R6 | Technology | Large maps and complex algorithms cause low fps | Game is harder to run on low specification computers | not currently happening | M | H | Optimisation Frustrum culling more simple AIs | Katie |
| R7 | Technology | Rendering during movement may stutter/lag/flicker | Graphics look slightly worse than they would if you pay close attention | not currently happening | L | L | Consistent manual testing to spot graphical glitches | Katie |
| R8 | Technology | Tile map rounding error causing visual artifacts | The game runs without any errors, but a lot of visual artifacts | not currently happening | H | M | pad texture atlas that is used for the tile map | Jacob |
| R9 | Estimation | The team misjudges how long different tasks will take | The deadline is missed or the work is of a lower quality | not currently happening | M | H | The team will work together closely to make sure everyone is working at a good speed and encourage others to keep working. | All |
| R10 | People | Bad team communication | Elements of the project may not be done and others duplicated | not currently happening | M | H | The team will ensure that they update the Trello/Github project board and communicate their progress regularly | All |
| R11 | People | Katie has to look after her child | She may not be able to commit to every meeting | Consistent risk | H | L | Using discord to hold online meetings | Katie |
| R12 | Technology | GitHub has been known to go down | Work cannot be completed and unsaved work will be lost | ~~not currently happening~~ **Update** see note 1| H | H | Documents should be pulled to a local machine, to be pushed back onto GitHub when its services are available | All |
| R13 | People | Saud is in Dubai | Due to time difference, Saud is running on a different time schedule | For the next few weeks | n/a | L | Give Saud tasks that he can complete independantly | Saud |
| R14 | People | Merging issues causing delays | If people make mistakes causing major bugs in the product, the project may be delayed  | Consistent risk | M | M | Use continuous integration to test the product between pull requests so issues can be spotted quickly | Jacob |
| R15 | People | Conflicting opinions | Team members having conflicting opinions could cause discorse and delay the project | Consistent risk | M | M | Have a team leader for the group plus one for imlpementation and documentation who get the final say. | Katie/Jacob/Saud |
| R16 | People | Misunderstanding of requirements | If the team misreads or misunderstands the requirements given, the final product could be not to the customers standard. | Consistent risk | M | M | Ensure brief is referred to often and clarifications made in the form of formal customer meeting at the start and contact via email or in person | Saud |
| R17 | People | Struggling to understand previous teams code | Spending a long time learning how their code works can delay the implementation of new requirements | Consistent risk | M | M | Communicate between implementation team and discuss how the new code base is structured and peculiarities of implementation | Jacob |

Note 1: GitHub has been having frequent 404 errors. Team members are ensuring they work on a local editor rather than through the github website. 23/02/22 [2] 16/03/22 down for atleast 3 hours. 23/3/22 down for atleast 2 hours [3] 


## Bibliography

[1]I. Sommerville and M. Paul, Software engineering--ESEC ’93 : 4th European Software Engineering Conference, Garmisch-Partenkirchen, Germany, September 13-17, 1993 : proceedings. Berlin ; New York: Springer-Verlag, 1993.

[2]“Slack and Github are down [Updated],” iMore, Feb. 22, 2022. https://www.imore.com/going-down-aws-struggling-and-yes-slack-and-github-are-down

[3]“An update on recent service disruptions,” The GitHub Blog, Mar. 23, 2022. https://github.blog/2022-03-23-an-update-on-recent-service-disruptions/ (accessed Apr. 24, 2022).
