# CS3028 Group Foxtrot

## Organisation Overview
This organisation was created to manage the *CS3028 Principles of Software Engineering*/*CS3528 Software Engineering and Professional Practice* project. In it, our group - Group Foxtrot - will work with the National Decommissioning Centre to develop the Simulation Scene Editor for the Marine Simulator. This project is intended to strengthen not only our technical skills but also our soft skills.

### The Team
- **Project Manager/SCRUM Master** -> John Dunbar
- **Product Owner** -> Kieran Thursby
- **Developers** -> Abdurrehman Sajid, Archie Mearns, Dylan Cairney, John Dunbar, Kieran Thursby, Mateusz Templin, Shaelen Fernandes
- **Testers** -> John Dunbar, Dylan Cairney
- **Documenters** -> Archie Mearns, Mateusz Templin
- **QC/QA** -> Shaelen Fernandes

These roles were established and assigned based on each individual's self-identified strengths.

### Project Overview

Working Name: *Simulacra*

The team will be taking the existing simulator scene editor developed by the NDC and improving upon it (further details to be added following the client meeting on 03/10/2024).

### Developer Housekeeping

#### Feature Implementation

For any new feature to be worked on during a development sprint, an Issue should be raised and associated with the Product Iteration (PI) project, assigned into the backlog to be picked up and/or manually assigned to a developer.
- **FOXTROT PI 1** is for CS3028 Semester 1 and consists of 4 two-week sprints commencing 03/10/2024.
- **FOXTROT PI 2** is for CS3528 Semester 2 and consists of 4 two-week sprints commencing TBC.

When working on an Issue in the backlog, developers should first run the following Git commands in their IDE:
1. `git init`
2. `git remote add origin 'https link to repository'`
3. `git pull origin main`

This ensures that developers are working on the same version of the main branch before continuing.

Once developers have performed the above Git commands, they should create a Feature Branch using the naming convention *feature/featureName* and move to that branch using `git checkout -b newBranchName`.

In this Feature Branch, developers are encouraged to commit frequently to ensure code integrity.

After a feature has been implemented in its corresponding Feature Branch, a *Pull Request* should be made in the repository. In this PR, developers should ensure that a sufficiently detailed title is given alongside an in-depth description of the functionality implemented alongside any changes made to existing code (this helps the reviewer determine if there will be any merge conflicts). **Do _not_ force merges to the main branch under any circumstances**.

Once the PR has been reviewed, it will be merged into the main branch, closing the Feature Branch. After this, use `git checkout -b main` to move to the main branch and then run `git pull origin main` to ensure the codebase is fully up-to-date before creating the next Feature Branch.

*If in doubt about anything regarding merging into the main branch, contact either the Project Manager or Product Owner*.

#### Code Standards

To ensure all code being worked on adheres to the same conventions and format, follow the below rules when developing feature code for sprints:
- **Use Camelcase for function definitions (e.g. exampleFunction())**.
- **Add a sufficient number of high-quality comments throughout the code to ensure that Documenters can write accurate documentation easily**.
- **Do not use ambiguous variable names (e.g. x = 0)**.

### Meeting Schedule
- *In-Person*: 09:00 - 11:00 BST Thursdays
- *Online*: 18:00 - 19:00 BST Mondays, 12:00 - 13:00 BST Thursdays, and 14:00 - 15:00 BST Saturdays

### Team Member Expectations
To ensure the project runs as efficiently as possible, all team members are expected to adhere to the following list of expectations:
1. Attend *at least* the weekly in-person meeting on Thursdays to provide progress reports and discuss any upcoming feature releases.
2. Make every effort to adhere to development deadlines and provide sufficient notice if a deadline will be missed with reasoning.
3. Assist other team members if required, and conversely, ask for assistance if required.
4. Actively contribute to the project in a meaningful manner.

### Escalation Protocol
In the event a team member is not meeting the aforementioned expectations, the following escalation scale will be actioned:
1. Either the Project Manager or Product Owner will get in touch to see if there is any way they can help, and provide development extensions where required. If they receive no response, the escalation moves to **Level 2**.
2. One of the course coordinators will be informed and will subsequently get in touch to make sure there are no personal issues causing expectations not to be met, and will provide assistance/extensions where required. If they receive no response, the escalation moves to **Level 3**.
3. A final notice is given to the team member stating that failure to reply within 48 hours with justification for not meeting team member expectations will result in being removed from the group, and re-admittance will require approval from the course coordinator and a fixed maximum contribution score of 10%.
