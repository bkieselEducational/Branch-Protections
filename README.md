# Branch-Protections

Ultimately, in the workplace you will not be merging any feature branches into main from the command line. Or rather, the merge is not going to complete. A pull request must be made in the Github console in the event where running the merge on the command line does not automate this for you (Generally it will). This allows a senior team member, or at a minimum fellow collaborators, to review the code and approve it before anything is merged into the production branch. Let's examine a simple setup for protecting our main branch in this way.

## 1. Repo Settings Tab
First we must navigate to the Settings Tab for our concerened repo and then click the 'Branches' button in the sidebar.

<img width="1180" alt="nav_to_branches" src="https://github.com/bkieselEducational/Branch-Protections/assets/131717897/ab8f895c-26a0-4488-804c-9661a417a00f">

## 2. Create a Ruleset for your branch

<img width="1170" alt="create_ruleset" src="https://github.com/bkieselEducational/Branch-Protections/assets/131717897/12a40b88-d09b-48db-af4a-68c8e2d47a34">

## 3. Name, Activate, Target
On the page you have now navigated to, the real action begins! Let's make a name for this ruleset. Let us ensure that it will be active on the branch or branches in question, and lastly, let's select the branch(es) that is/are to be the targets of this Ruleset.



## Another prompt
<img width="1208" alt="name_active_target" src="https://github.com/bkieselEducational/Branch-Protections/assets/131717897/7f8d2727-f79f-4013-961f-e6cba975aa4a">
