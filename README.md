# Branch-Protections

Ultimately, in the workplace you will not be merging any feature branches into main from the command line. Or rather, the merge is not going to complete. A pull request must be made in the Github console in the event where running the merge on the command line does not automate this for you (Generally it will). This allows a senior team member, or at a minimum fellow collaborators, to review the code and approve it before anything is merged into the production branch. Let's examine a simple setup for protecting our main branch in this way.

## 1. Repo Settings Tab
First we must navigate to the Settings Tab for our concerened repo and then click the 'Branches' button in the sidebar.

<img width="1180" alt="nav_to_branches" src="https://github.com/bkieselEducational/Branch-Protections/assets/131717897/ab8f895c-26a0-4488-804c-9661a417a00f">

## 2. Create a Ruleset for your branch

<img width="1170" alt="create_ruleset" src="https://github.com/bkieselEducational/Branch-Protections/assets/131717897/12a40b88-d09b-48db-af4a-68c8e2d47a34">

## 3. Name, Activate, Target
On the page you have now navigated to, the real action begins! Let's make a name for this ruleset. Let us ensure that it will be active on the branch or branches in question, and lastly, let's select the branch(es) that is/are to be the targets of this Ruleset.

<img width="1208" alt="name_active_target" src="https://github.com/bkieselEducational/Branch-Protections/assets/131717897/7f8d2727-f79f-4013-961f-e6cba975aa4a">

## 4. Making a Pull-Request Mandatory
In our final step (further down the same page as above... in a galaxy far far away), we must now enable the feature that requires a pull-request and also set the number of collaborators whom must approve of the pull-request. 1 collaborator is a satisfactory minimum here.

<img width="1375" alt="mando_pull" src="https://github.com/bkieselEducational/Branch-Protections/assets/131717897/5fb30d30-2725-4d53-8af0-b38ae4efad26">

##
# Create a Pull Request in the Console
So if you have made changes to your feature branch (and commited them to the remote repo) and are ready to merge them into main, you can create a Pull request in the console.

## 1. Navigate to the Pull requests Tab

<img width="1858" alt="getting_started" src="https://github.com/bkieselEducational/Branch-Protections/assets/131717897/50d61780-d485-412e-a29b-f9140739b211">

## 2. Select a branch that differs from main

<img width="1605" alt="select_a_branch" src="https://github.com/bkieselEducational/Branch-Protections/assets/131717897/cc6112bd-8517-4385-b1ba-275e708e9c2c">

## 3. Finaze the creation (kind of)

<img width="1798" alt="finalize" src="https://github.com/bkieselEducational/Branch-Protections/assets/131717897/18dd645f-0a4f-4ec1-8228-8fe58153e0c6">

## 4. One last time (github REALLY likes you to be sure about things...)

<img width="1552" alt="last" src="https://github.com/bkieselEducational/Branch-Protections/assets/131717897/e39f7b0d-8666-4ad4-ace0-565fa1627c23">

##
# Pull Request Approval
Using the navbar of your Github repo, you will need to navigate to the Pull requests tab if there is not a button present on the main branch for this purpose. 

## 1. Create an approval review
Click on the button boxed in below. This shall take you to where you can review the code changes and add your review.

<img width="1741" alt="needs_approval" src="https://github.com/bkieselEducational/Branch-Protections/assets/131717897/0665224a-d589-4dce-9728-fb0b77203633">

## 2. Create Review, Give Approval
On the following screen, after examining the code, press the Review changes dropdown. note that a collaborator cannot approve their own pull request.

<img width="1859" alt="giving_approval" src="https://github.com/bkieselEducational/Branch-Protections/assets/131717897/376f89e9-b4c1-4efa-9927-e98728b217d0">

## 3. Time to Merge
Theoretically, things should look pretty green at this point. If so, you are ready!

<img width="1657" alt="set_to_merge" src="https://github.com/bkieselEducational/Branch-Protections/assets/131717897/a53d39b6-c89f-4c62-a2cc-bd5d149ac6b8">

## 4. Confirmation
You'll just need to confirm the changes as a final step.

<img width="1618" alt="merge_confirm" src="https://github.com/bkieselEducational/Branch-Protections/assets/131717897/6d6a38c0-0d55-49d9-a0f1-0a814250eba4">

