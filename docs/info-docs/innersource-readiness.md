## About InnerSource readiness

## Step 1: Evaluate the projects your team owns. Divide projects into four lists

* Projects that can accept internal community contributions from developers within the organization.
  * These are projects that get contributions from users outside of your team, even if users only contribute once!
* Projects with security requirements that cannot accept external contributions.
  * Not all projects are good for InnerSource. Specifically, those that are higher risk or have restricted access.
* Projects that need to have ownership transferred.
  * These projects may be better owned by a different team.
* Projects that need to be deprecated
  * Find the projects that are no longer being maintained and archive them.

To begin, focus on the list of projects that can accept contributions from external contributors. Later on you will work on projects that will be transferred to other teams.

## Step 2: Create Transparency

All InnerSource code will live in GitHub or standardiced VCS

## Step 3: Create Quality Documentation

* Add CONTRIBUTING.md to each repo your team owns.
* Add README.md to each repo your team owns.
* Add COMMUNICATION.md to each repo your team owns.

Link the communication documentation to the contributing and readme documents.

**Tips:**

One person does not need to be responsible for writing all of these documents. Gain buy-in from your entire team and get it done faster by having the people most knowledgeable about the content take ownership of the different documents.

Write the first draft of the template in a document where you can get feedback before you put it into the repo. Use the markdown add-on in Google Docs to convert the entire document into markdown so you don’t have to do it manually.

## Step 4: Organize Documentation

* Explore the InnerSource portal. This is where you will be able to search for documentation and reusable code.
* Place all documentation specifically related to each project's code in the project repo. The best practice is to have documentation in the repository, so users can submit pull requests to suggest updates to existing documentation.
* Set permissions to “internally visible to the organization” for all documentation linked to documentation not stored in the repo.
    Documentation should be in your project repository, not in a drive. This way every user does not have to ask permission to access it.

## Step 5: Verify that your Documentation Current and Accurate

* Review all documentation in your repos to make sure it is current and accurate.
* The person responsible for the documentation will write “Reviewed on **Date (use 3 letter abbreviation for month)\_ by**Name\_\_” at the top of the document.
  * This convention will be used on all of your documentation in your repositories
* Review and reverify documentation is up to date quarterly, unless the documentation:
  * Requires more frequent updates.
  * Is documentation that will never change. If this is the case, make note of this in the documentation.

## Last Step: You are InnerSource Ready

Have someone on your team set up a consultation with the InnerSource team.

Get added to the ADI InnerSource team directory.

Collaborate with other teams!

## Future Planning

## Frequently Asked Questions

**How long should this take my team?**

If you choose a team member who is familiar with all of the team projects to create the lists of projects, they can categorize your projects in a couple of hours. Make sure this is thorough and documented for your team’s records.

Preparing the repos will depend on how many repos your team owns and how many team members are working on it. Writing documentation that is familiar to team members will likely be less time consuming than finding all of the documentation, reviewing it, and putting it in the right location.

**How does InnerSource impact our projects in the other three categories?**

Your priority is making the projects that can be contributed to by external users InnerSource ready. If a project is not being deprecated, these documentation templates and cleanup processes will improve discoverability and repo health to assist with the handoff of projects and long-term documentation tracking.

It will make it easier to hand off a project to a different team if ownership needs to be reassigned. It will also make it easier to onboard new team members and reduce the onboarding time, as permissioning and discoverability will be easier.
