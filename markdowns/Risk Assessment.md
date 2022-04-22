## Risk assessment and mitigation

The risks to the project are presented in the table below, with the following information about each one: 



* An ID- to identify individual risks
* Category type- helps to read the table quickly and find the specific risks
* Description- details what the risk is 
* Potential consequence- explains what could go wrong and why this risk needs solving
* Monitoring- shows whether the risk is happening, indicating if it is of immediate concern
* Likelihood and severity- allows the team to make a judgement about how much of a priority this risk is in solving or preventing
* Mitigation - details the steps that need to be, or are being taken to prevent the risk from happening. 
* Owner- shows who is responsible for either solving the problem or arranging for it to be solved

There is significant detail about the risks to the programming and game itself because each item can affect the overall game, and are distinct issues. The likelihood and severity of the risks are also included because this tells us which risk to prioritise in mitigating, and each item has an ‘owner’- without one, the responsibility can be unclear, causing the issue to not be solved.

| ID | Type | Description | Consequences | Monitoring | Likelihood | Severity | Mitigation | Owner |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R1 | Technology | AI interaction proves infeasible to implement | Opposing ships will behave differently | not currently happening | H | H | Fake AI via scripted interaction | Katie |
| R2 | Product | NPC targeting of player ship not enough or too challenging | Game may not be enjoyable | unknown - ship combat not implemented until assignment 2 | M | M | Player test gameplay and adjust parameters | Cody |
| R3 | Technology | AI decision making too slow to be convincing | Game may not be enjoyable | not currently happening | L | M | Fake AI via scripted interaction | Cody |
| R4 | Technology | Physics engine being unstable | Player and projectiles may not interact with the other elements in the program correctly. | not currently happening | M | M | Make it difficult to get into an unstable situation | Jacob |
| R6 | Technology | Cost of high res textures cause high loading time | Game may have a large loading time, which may cause the user to think the program is broken | not currently happening | L | L | Minimal resources are loaded (possibly on another thread) or compression used  | Jacob |
| R7 | Technology | Large maps and complex algorithms cause low fps | Game is harder to run on low specification computers | not currently happening | M | H | Optimisation Frustrum culling more simple AIs | Katie |
| R8 | Technology | Rendering during movement may stutter/lag/flicker | Graphics look slightly worse than they would if you pay close attention | not currently happening | L | L | Consistent manual testing to spot graphical glitches | Katie |
| R11 | Technology | Tile map rounding error causing visual artifacts | The game runs without any errors, but a lot of visual artifacts | not currently happening | H | M | pad texture atlas that is used for the tile map | Jacob |
| R14 | Estimation | The team misjudges how long different tasks will take | The deadline is missed or the work is of a lower quality | not currently happening | M | H | The team will work together closely to make sure everyone is working at a good speed and encourage others to keep working. | All |
| R15 | People | Bad team communication | Elements of the project may not be done and others duplicated | not currently happening | M | H | The team will ensure that they update the Trello and communicate their progress regularly | All |
| R16 | People | Katie has to look after her child | She may not be able to commit to every meeting | Consistent risk | H | L | Using discord to hold online meetings | Katie |
| R17 | Technology | GitHub has been known to go down | Work cannot be completed and unsaved work will be lost | not currently happening | M | H | Documents should be pulled to a local machine, to be pushed back onto GitHub when its services are available | All |
| R18 | People | Saud is in Dubai | Due to time difference, Saud is running on a different time schedule | For the next few weeks | n/a | L | Give Saud tasks that he can complete independantly | Saud |
| R19 | People | Merging issues causing delays | If people make mistakes causing major bugs in the product, the project may be delayed  | Consistent risk | M | M | Use continuous integration to test the product between pull requests so issues can be spotted quickly | Jacob |
