**Project Practice Guide**

Collaboration and Communication
* Daily stand-ups
  * Daily stand-ups are very important in SCRUM in order to touch-base and monitor the progress of the project, as everyone needs to be aware of what they need to get done and what everyone else has to get done, so that deadlines are met. However, in some cases, daily in-person meetings can be too much for certain people or groups as everyone has their own commitments. Because of this, it is good to arrange an alternative method of have a daily stand-up remotely, e.g. Skype conference.
* Weekly full-length meetings
  * It is very important to have at least one full-length in-person meeting each week in order to collaborate on work and collate completed work. It should be made clear to everyone in the first meeting that these meetings are very important, and should anyone absolutely be unable to come to the meeting in-person for whatever reason, be it they have an urgent commitment, are sick etc. then they should atleast try to jump on a VOIP channel like Skype, so someone who will be at the meeting physically can open Skype and the 'away' person can join the meeting remotely.
* Make sure everyone knows well in advance about days and times of meetings, and what is going to be discussed in those meetings
  * This is also very important, as trying to arrange these things on-the-go is a lot more difficult than it seems. It is much better to arrange everything that's going to happen in every meeting from the first meeting, and layout a plan for adjustments should something not go as planned, and it almost certainly won't. The plan should be something like "If in the Skype meeting on Friday, we decide we need to meet in person urgently, we will either arrange to meet in-person next Tuesday, or if it's really urgent, sometime in the weekend". This ensures that should something go wrong, everyone is aware of what needs to happen and what they need to do. 
* Workspace layout contributes to communication across different sectors
  * If any of you have the time, see if you can find an article or two on this. I found one that showed employees preferred a closed-plan office, but I would like to try and see if we can find some articles that say otherwise, to get both sides.


Requirements Engineering
* Requirements elicitation
	* Document your approach and create a strawman to generate the right conversation
	* Send input material to participants in advance, with clearly defined objectives for the specific elicitation event
	* Continue to revalidate the requirement until it is clear and can be acted upon by those who read them
* Requirements specification
	* The requirements specification should contain information about what is required for the project.
		* What game engine is required? Does it need to be a high-end game engine? Or can you make do with a cheaper, low-end engine? These kinds of things will need to be taken into account when creating the requirements specification.
		* Proof of concept.
			* Proof of Concept is really important for any project, as in order for an idea to become reality, people need to see a Proof of Concept, particularly if you are looking to raise money via an investor.
			The Proof of Concept can be as simple or advanced as you like. It could be just be a sketch on a piece of paper, or it could be a functional product. For this particular case study, a simple demo should suffice.
		* Design method
			* What methods will you use to design the game? This would also be in listed in the requirements specification, as it is very important to plan out how the video game is going to be designed.
		* Anything else required? Art design?
* Planning poker
	* Planning poker is a very useful and efficient method of assigning story points to user stories as estimates of the effort it will take to complete each user story. Each team member gets a deck of 13 cards. Whenever a story is to be estimated, each team member selects a card that represents his/her time estimate and places it face-down on the table. When all team members are done the cards on the table are revealed simultaneously. This way each team member is forced to think for him/herself rather than lean on somebody else's estimate. If there is a large discrepance between two estimates, the team discusses the differences and tries to build a common picture of what work is involved in the story. Afterwards, the team estimates again. This loop is repeated until the time estimates converge, i.e. all esimates are *approximately* the same for that story.
	* Story points are the time estimate for each user story. This is used to prioritise different user stories so that time is balanced well across all user stories.
* Systems modelling
	* Not sure about this one?



Project Planning and Tracking
* Maintain version control using a tool like GitHub
* Track progress using a tool like Trello
* Estimate velocity using one of two methods (I read the textbook… ;) ):
    * Gut feel
    * Velocity calculations
      * Decide estimated velocity
        * Look at the team’s history, this technique is known as yesterday’s weather. This is only feasible for teams that have done a few sprints already. If this is the team’s first sprint (so statistics are available). It’s also only feasible if the team will do the next sprint in pretty much the same way, with the same team size and same working conditions etc. This is of course not always the case.
          A more sophisticated technique is to do simple resource calculation (SCRUM and XP from the Trenches, page 36)
          This takes into account a ‘focus factor’ along with the ‘available man-days’. Of course, a new team will not have a focus factor for the first sprint. This is fine, for the first sprint, you can simply make a guess, as once the first sprint is done, you will have an actual ‘focus factor’ for the next sprint. A good default ‘focus factor’ for the first sprint is 70%.
      * Calculate how many stories you can add without exceeding the estimated velocity
      	* To do this, you first calculate the ‘focus factor’. Focus Factor = Actual Velocity / Available Man-Days.
          Then, you use that ‘focus factor’ to calculate the next sprint’s estimated velocity, e.g. 50 Man-Days * 40% = 20 story points.
          You now have an estimated velocity of 20 story points, so the team should add stories to the sprint until it adds up to approximately 20.
* Gantt Chart
	* A Gantt Chart is another useful method/tool for tracking project progress. It does this by illustrating a project schedule along a timeline. It illustrates the start and finish dates of the individual elements of a project.
* Microsoft Project
	* Microsoft Project can also be a useful method/tool for tracking project progress, as it provides a range of utilities for different kinds of graphs and charts, including Gantt Charts, as well as other features to help track progress.

Managing Change
* The above methods under ‘Project Planning and Tracking’ both play a part in managing change, as things like a lower ‘focus factor’ or an extra person who has just joined the team can be taken into account in the calculations.
* Many Humans are naturally resist change. This is a problem in a world where everything is constantly evolving. 
* Change management is the process by which an organization gets to its future state, its vision. Creating change starts with creating a vision for change and then empowering individuals to act as change agents to attain that vision. The empowered change management agents need plans that provide a total systems approach, are realistic, and are future oriented. Change management encompasses the effective strategies and programs to enable those change agents to achieve the new vision. (Lorenzi & Riley, 2000)
* Struggling with this one....need to discuss it in touch-base meeting on Friday
* Change Management Plan
	* A Change Management Plan is a written plan used to track changes to a project, it consists of:
		* A lost of the roles that will be assigned for the project
		* A change control board can be useful, made up of representatives from each stakeholder group
		* A process for enacting change requests
		* A change request form
		* Additional information for the change log
		* Track major decisions

Quality Assurance
* GitHub is a good way to do this, as it requires approval from other people in the team in order to process a change, and so everyone in the group can have a role in Quality Assurance.
* After getting the hang of GitHub myself, I've found that the version control and quality assurance it offers is extremely good, as you can create branches that allow you to modify files, while leaving the original copies in the master branch unaffected. Once you have made changes, you can then submit a pull request to merge the local branch back into the master branch, and it will tell you if there are any conflicts. This way, someone can approve any and all changes before they are applied to the original copies of the files.
* Quality Assurance Plan
	* This is used to ensure a good quality is upheld for the duration of the project. A Quality Assurance plan includes:
		* An organisation chart with detailed job descriptions
		* Details of who is responsible for checking the work
		* Specitfications that the material produced must meet
		* Specifications that prospective suppliers must meet
		* Quality feedback practices/measures
		* A corrective action plan
* Testing software
	* Testing software is used to test the quality of written code, for example, Selenium, which is testing software used to automate testing in a web browser.
	* User stories are passed on to the testers after being completed by the developer, so that they can be tested for quality before being integrated.
