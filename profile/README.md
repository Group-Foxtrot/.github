# CS3028/CS3528 Group Foxtrot

## Organisation Overview
This organisation was created to manage the *CS3028 Principles of Software Engineering*/*CS3528 Software Engineering and Professional Practice* project. In it, our group - Group Foxtrot - will work with the National Decommissioning Centre to develop the Simulation Scene Editor for the Marine Simulator - Simulacra. This project is intended to strengthen not only our technical skills but also our soft skills.

### The Team
- **Project Manager/SCRUM Master** -> John Dunbar
- **Product Owner** -> Kieran Thursby
- **Project Administrator** -> Archie Mearns
- **Developers** -> Archie Mearns, Dylan Cairney, John Dunbar, Kieran Thursby, Mateusz Templin, Sebastian Codley, Shaelen Fernandes
- **Testers** -> Dylan Cairney, John Dunbar
- **Documenters** -> Archie Mearns, John Dunbar, Mateusz Templin

These roles were established and assigned based on each individual's self-identified strengths.

### Developer Housekeeping

#### Feature Implementation

For any new feature to be worked on during a development sprint, a task will have been assigned to a developer in the Jira board. Pair programming is highly recommended as many of the project's tasks are complex due to the bespoke nature of the system.
- **FOXTROT PI 1** is for CS3028 Semester 1 and consists of 4 two-week sprints commencing 03/10/2024.
- **FOXTROT PI 2** is for CS3528 Semester 2 and consists of 12 one-week sprints commencing 30/01/2025.

When working on an Issue in the backlog for the first time, developers should first run the following Git commands in their IDE:
1. `git init`
2. `git remote add origin 'https link to repository'`
3. `git pull origin main`

This ensures that developers are working on the same version of the main branch before continuing.

Once developers have performed the above Git commands, they should create a Feature Branch using the naming convention *feature/featureName* and move to that branch using `git checkout -b newBranchName`.

In this Feature Branch, developers are encouraged to commit frequently to ensure code integrity. Feature branches should *not* exist for more than one day before being merged through a Pull Request.

After a feature has been implemented in its corresponding Feature Branch, a *Pull Request* should be made in the repository. In this PR, developers should ensure that a sufficiently detailed title is given alongside an in-depth description of the functionality implemented alongside any changes made to existing code (this helps the reviewer determine if there will be any merge conflicts). Automated tests will be carried out through GitHub Actions which will confirm whether the feature works in its entirety. **Do _not_ force merges to the main branch under any circumstances**.

#### Pull Request Reviews

Pull Requests should be approved or denied based on the following criteria:
- Proper indentations/whitespace.
- Meaningful variable names.
- camelCase for variables and methods.
- UpperCamelCase for classes.
- BLOCK CAPITALS for constants and Enums.
- Comments above a line of code if it is not intuitive.
- XML comments above method and class declarations (in VS2022 type /// and it will generate the basic XML comment structure).
- Methods under 50 lines of code (excluding whitespace).
- Implemented code makes use of pre-defined tests and passes existing ones.
- Avoids compiler warnings.

The reviewer must ensure all tests pass, read through every line of code submitted in the PR, and write a *detailed* comment in the PR as to why the PR has been accepted or denied based on the above acceptance criteria.

Once the PR has been reviewed, it will be merged into the main branch, closing the Feature Branch. After this, use `git checkout -b main` to move to the main branch and then run `git pull origin main` to ensure the codebase is fully up-to-date before creating the next Feature Branch.

*If in doubt about anything regarding merging into the main branch, contact either the Project Manager or Product Owner*.

#### Bug Reporting

If a bug is found in a Pull Request, refer to the following:

- **Quality of Life (QOL)** -> These are bugs that do not cause fatal errors in the software and have very specific edge-cases. These should be reported but are not a priority to patch.
- **Medium Severity Faults (MSF)** -> These are bugs that do cause fatal errors in the software but have very specific edge-cases. These should be reported and be patched by the end of the following sprint.
- **Critical Severity Faults (CSF)** -> These are bugs that cause fatal erros in the software and can be triggered by a number of actions. These should be reported and be patched within the current sprint with the highest priority.

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
3. A final notice is given to the team member stating that failure to reply within 48 hours with justification for not meeting team member expectations will result in being removed from the group, and re-admittance will require approval from the course coordinator and a fixed maximum contribution score of 10% and default penalty of -40% to any existing contribution.
