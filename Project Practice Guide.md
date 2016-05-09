**Project Practice Guide**

Collaboration and Communication
* Daily stand-ups
* Weekly full-length meetings
* Make sure everyone knows well in advance about days and times of meetings, and what is going to be discussed in those meetings
* Workspace layout contributes to communication across different sectors


Requirements Engineering
* Requirements elicitation
* Requirements specification
   * What game engine is required?
   * Proof of concept
   * Design method
   * Anything else required? Art design?
* Systems modelling



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

Managing Change
* The above methods under ‘Project Planning and Tracking’ both play a part in managing change, as things like a lower ‘focus factor’ or an extra person who has just joined the team can be taken into account in the calculations.
* Other ways of managing change? - DISCUSSION POINT

Quality Assurance
* GitHub is a good way to do this, as it requires approval from other people in the team in order to process a change, and so everyone in the group can have a role in Quality Assurance.
* Other tools ? - DISCUSSION POINT
