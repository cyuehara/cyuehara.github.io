---
layout: project
type: project
image: images/HACCHui.png
title: HACC-Hui
permalink: projects/HACChui-project
# All dates must be YYYY-MM-DD format!
date: 2020-12-15
labels:
  - Software Engineering 
  - MongoDB
  - Web Design
  - Semantic UI
  - React 
  - Project Management 
summary: Creating a website to provide a user friendly application to simplify and improve the team formation process during the Hawaii Annual Code Challenge
---
<h2> Hawaii Annual Code Challenge </h2>
[Hawaii Annual Code Challenge](https://hacc.hawaii.gov/) (HACC) is a unique hackathon that stregthens the pipeline of the IT workforce in the state of Hawaii. At the HACC kick off, participants form teams, select a challege that interests them, and work together to create an innovative web application. In the past, the informal team formations lead to high failure rate with participants joining the wrong teams and overall having a bad experience. The students taking ICS 414 (Software Engineering II) spent eight weeks building a Meteor application intergrated with Slack to create [HACC Hui](https://hacc-hui.github.io/), a user friendly web application, to improve the team formation process at the event. This project was a success at the October 24 2020 HACC Kickoff making the team formation a better experience for all participants. 
<img class="ui rounded image centered" src="../images/HACCHomePage.png">

<h2> LevelUpTeamA </h2>
At the beginning of the semester, our class was randomly split into teams of four- five students. Each team would work on the milestones created. At the end of each milestone, our professor would pick the best implementation and add it to the master repository which we would work on. I was on LevelUpTeamA with Nadine Alcantara, Angeli Amascual, Newton Ransfer, and Justin Wong. We communicated through Discord to set up team meetings to go over what everyone's tasks were for each milestone. Before assigning the issues, we added our class/work schedules in our group chat so we could find the days that we could meet and discuss our game plan for this project. We ceated a project board for each milestone and assigned ourselves to an issue to work on during the week. This was a good way to organize the tasks that needed to be completed and everyone could pick an issue they were interested to work on. 

<h2> User Stories </h2>
HACC Hui has three different types of users. The first would be the "installers" who are the software developers, "Administrators" who are the members of the program committee, and lastly "Participants" who are the HACC participants. We were provided with [User Stories](https://hacc-hui.github.io/docs/requirements/installers) that gave us an explanation of what needed to be featured on the website. Each milestone included a specific user story that we would have to implement. After completing each milestone, each group would present their solutions to the class and our professor would pick the best and implement it in the "final" repository that the whole class would use in the end.  

<h3> Milestone 1 </h3>
[Milestone 1 Project Board](https://github.com/LevelUpTeamA/HACC-Hui1/projects/1)

| User Stories | Description |
| ----- | ----------------------------------------------------------- |
| [US-A2: Confiugure HACC](https://hacc-hui.github.io/docs/requirements/administrators#hacc-hui-configuration) |  As an administrator, I want to login to HACC Hui and configure the application.  |
| [US-D2: Login & Profile](https://hacc-hui.github.io/docs/requirements/participants/#participant-profile-configuration)  | As a participant, I want to login to HACC Hui and develop my profile, so I can be matched with the best open team.  |
| [US-D4: Create Team](https://hacc-hui.github.io/docs/requirements/participants/#team-creation)  | As a participant, I want to create a team, so we can solve a challenge and win the HACC. |
| [US-D13: Delete HACC Hui account](https://hacc-hui.github.io/docs/requirements/participants/#delete-account)  | As a participant, I want to be able to delete my HACC Hui account at any time. |

<img class="ui medium left floated rounded image" src="../images/LoginCreateTeam.png">
For milestone 1, I created the login page and create team page. I used the skills I learned from ICS 314 to layout the login page. I kept it simple and added the HACC logo on the side next to the login box. Before building the create team form, I made a mock up page of what I wanted the form to look like. Then I took a look at the requirements for the create team page. The important requirememnt for this form was that the team name, github repo, and devpost page had to be the same name and the about us had a character count of 200 characters. Creating the UI for this page was easy for me to do since I had more experience with designing/building pages from my ICS 314 project last semester. I struggled with getting the team information to be saved correctly in the team collection. After talking with my teammates, they were able to help me see if the team profiles were saved correctly with using the Meteor Mongo commands. 


<h3> Milestone 2 </h3>
[Milestone 2 Project Board](https://github.com/LevelUpTeamA/HACC-Hui1/projects/2)

| User Stories | Description |
| ----- | ----------------------------------------------------------- |
| [US-D5: Update team](https://hacc-hui.github.io/docs/requirements/participants/#team-creation) |  As a team owner, I want to update the team to reflect the current status. |
| [US-D6: Delete team](https://hacc-hui.github.io/docs/requirements/participants#team-creation)  | As a team owner, I want to delete the team. |
| [US-D7: See best fit teams](https://hacc-hui.github.io/docs/requirements/participants#team-matching-participant-initiated)  | As a participant, I want to see which team is the best fit for me. |
| [US-D8: Indicate desire to join](https://hacc-hui.github.io/docs/requirements/participants#team-matching-participant-initiated)  | As a participant, I want to indicate I'm interested in joining a team. |

For milestone 2, I worked on the update team page. The team profile card was created by another team in milestone 1 so all I had to do was link the edit team form to the edit button on the page. I used the same layout as create team for the edit team form and had the information filled out. The user would only be able to change the challenge, skills, tools, and availaility. The team name cannot be changed. It was difficult for me to update the things changed in the team collection since I was still learning about how to use MongoDb collection. I was unable to get the update team to corretly update the teams information, however I still was able to get the form to link to the edit team button. 

<h3> Milestone 3- "The Final Sprint" </h3>
[Milestone 3 Project Board](https://github.com/HACC-Hui/HACC-Hui/projects/1)

| User Stories | Description |
| ----- | ----------------------------------------------------------- |
| [Update Edit Team Page](https://github.com/HACC-Hui/HACC-Hui/issues/84) |  Add labels to the form: requirement that the team name, github repo, and devpost page all use the same name. |
| [Update Create team Page](https://github.com/HACC-Hui/HACC-Hui/issues/38) | Add labels to the form: requirement that the team name, github repo, and devpost page all use the same name. |
| [Implement a List Participant Page](https://github.com/HACC-Hui/HACC-Hui/issues/37)  | Create a page to list all the participants and list their information. Also update UI of profile card |

<img class="ui medium left floated rounded image" src="../images/ListParticipant.png"> 
For milestone 3, we switched the format of the class to work on one main repository and choose the issues we wanted to work on individually or with a partner. The three issues listed above was the ones I worked on for this milestone. The first two were fairly simple. There was a requirement that the team name, github repo, and devpost page all had to use the same name so I had to add labels to the forms to tell the participants of this requirement. The last issue I worked with Matthew Kim to implement a page that list all the participants and their profile. There was a basic layout of the participant page already created, so Matthew and I discussed different ways we could better the look of the page. I took into consideration of the things that should be highlighted when teams are looking to add members. If I was a team leader looking through the participants, I would focus on the "about me" portion to see which participant stands out and would be a great asset to the team.<img class="ui medium left floated rounded image" src="../images/Profile.png">  There is a before and after picture that shows the small changes made to the page. When the user clicks on the participants name, there is a pop up box that shows the full profile of the participant. Again, it was a simple layout that was already existed in the repository, so we discussed ways to make it look more professional and cleaner. The participants ranged from middle school students, to high school students, to college students, to professional. We listed their status under their name to distinguish the range of which the participant was listed in. 










