## The contribution process

Are you ready to start contributing to other teams projects/repos? If your contribution is larger, you may go through (some) of these steps repeatedly as you iterate towards your common goal.

## Preparing to work

### Lead times

With every first-time contribution, you are coming to a new (host) team. As a result, you’ll need to get to know their code base, technologies used, and their preferred development environment. Each team will have some individual processes. In addition to the technical side, there may be differences in communication. If you are returning after an extended period of time, the teams' processes and members might have changed. Take time to read documentation and reconnect with the team.

Give yourself enough lead time. Start early enough, so that your work is available for you to leverage at the time you need it. It’s better to add more slack time initially - you’ll get a feeling about the turnaround times once you work with the host team. Often, you will notice a reduction in turnaround time per host team after making a few successful contributions to that host team.

### Expectation management

In your classic teams everyone had an idea of the expected lead times. Within an InnerSource context this might not be the case, either due to large time-zone differences or you not being available full-time as with your original team. To prevent frustration on both sides, explicitly set expectations about expected reaction times.

One approach is to quickly react with "I’ll look into it; I won’t get to it in the next few days though." Ideally, provide them a rough estimate of when you will have time to review their input. Doing so builds trust. Established trust will allow you to overcome uncertainty in the collaboration.

### Building trust

InnerSource puts huge weight on written communication, especially when it comes to project decisions. Written communication is important for archiving and searchability; face-to-face communication is important when it comes to communication bandwidth. Try to make time to meet with people behind the names. When you’re able to hear people speak and know their idiosyncrasies, asynchronous collaboration becomes easier.

### Avoiding rejection

Some frequently encountered challenges may include:

* The host team is already building something very similar to the feature you are trying to contribute.
* The host team is planning to deprecate the software.
* The host team does not see what you are proposing to be a fit for their project.

Many team relationships suffer from not agreeing in advance that a contribution is a good fit. Make yourself and the host team happy (and possibly save some work) by getting agreement from the host team on the user/technical design of the contribution before working on the changes and submitting a pull request. You have to understand how the host team would like you to reach out for this. It’s best to ask a Trusted Committer about how to best discuss your proposal.

You should try to select a written way to discuss features so that documentation can be recorded. Ideally, choose the way where artifacts are public, searchable and perma-linkable to enable referencing your proposal in later discussions on this future contribution. This can be aided with the use of a Request for Comment  (RFC) document. This could be an issue template or a markdown file.

This type of high-level, early upfront agreement will save time in rework or rejection of your pull request down the road.

### Communication and unblocking yourself

Try to peruse their documentation, the conversation archives and code artifacts from the host team to unblock yourself. Ask the host team if things are going nowhere even after trying to unblock yourself. The questions you ask and the answers you receive will help others coming after you solve the same issues. Make sure that your communication ends up in a searchable archive that is closely linked to the project itself.

If you see easy improvement opportunities to reach said goal if it is not reached yet, you could suggest an improvement to the host team. Sometimes the status quo arises from pure happenstance and stays that way because no one had a different idea. Suggestions for improvement might be welcome in such cases. As you work, if you find missing (or out-of-date) documentation, help the next contributor and update it with what you’ve discovered. Project teams are often happy to receive additions, updates or corrections for their existing documentation - you’ve just found another opportunity to contribute! (Or just politely provide them with a feedback on your experience, and what would have helped you.)

Use the communication channels laid out in the projects ‘COMMUNICATION.md’. Following these channels means communications are text-based, archived, searchable and come with stable links. Your question and the answer will be written down, and the references you link in those answers will be kept reachable. This way you can benefit from this passively documented knowledge in your search AND help future contributors have the same advantage. Such passive documentation could even serve to enrich 'official' documentation, should it happen to contain valuable information - such as important definitions that got created ad-hoc.

### Creating the pull request

The host team’s project has code style preferences. Try to adapt and match those preferences even if it’s not what you would normally do, and even if it is not specified in the projects' ‘CONTRIBUTING.md’. If you are unsure, you can ask. A guest contribution for a feature or a bug fix is not the time to introduce a new way of structuring or formatting project code.

Submitting the pull request
Here’s what you can do to make reviewing and merging as easy as possible for the the Trusted Committer and the host team. This might actually be pretty similar to what you may already be doing on your own project to get your changes accepted.

#### Testing and automation

Enable the Trusted Committer to validate the contribution without your presence and to ensure easy maintainability. If for instance, you built a feature, handled of an unsolvable quirk, made an important performance tweak, and your code is not entirely obvious (or might even look hacky / wrong at the first glance). If you have covered this with a test and have documented the rationale behind it in a comment, a future editor will be reminded about the purpose of the code, and the test(s) will ensure that the value your code realizes will be kept, even in the new implementations. To achieve this, do the following:

Add tests for your code contribution, so that validating the function of your contribution by others works well, even after some time, when you work in other projects or might have stopped contributing to this project.
Often projects will have automated checks against pull requests using those tests and the level of code coverage. Try to meet the criteria these tests enforce.
Many projects will provide project build and validation scripts that enable you to locally test your changes. Use those to ensure that your contribution works as well as possible before opening a pull request. No one is perfect though. Do your best, use prepared validation scripts if there are any.
If your pull request keeps breaking tests, and you can’t find out why, try to highlight those tests in the pull request comment, illustrate your current understanding of the problem and ask for help on it.
Create a modified build of the shared project with your changes and try it out in your own project that consumes it.
Having to review defective pull requests with easy-to-fix errors often frustrates trusted committers. They will not fix your code but ask you to do so. This may create more round-trips and slow the merge.

#### Documentation and reviewability

You want to ensure that your pull request includes any documentation updates that are relevant to your changes. If the documentation should live in a different place, make sure you add it there and link to it  in your pull request.

To make the actual code review as easy as possible for the trusted committer or other persons reviewing it, try to follow these hints:

* Be sure that your pull request includes only the relevant changes for the issue you’re completing.
* Try to avoid super-large commits, commits with unclear commit messages, gazillions of files, or incoherent changes (e.g. touching multiple topics).
* Provide a clear description of what this pull request changes, why it does so, and which issue and design documents (if there were any) it refers to.
* If there is anything uncommon or unexpected in the pull request, highlight it and provide the explanation. This will make it easier to reason about and solve potential blocking questions that a reviewer might have during the review.
  * The same goes for the scenario where you were unsure of the implementation or your approach - highlight it and ask for an insight.
* Making pull requests too broad and large makes them more difficult to review, so it will take much longer before they’re accepted.
* If you have a larger feature that you are contributing, it helps to split it in multiple pull requests that are submitted, reviewed and accepted sequentially. You can still bind them together with an issue that you are referring to.
* Some tools also have Draft / WIP pull request functionality that you can use to explicitly mark unfinished and non-polished work and still get early feedback from your host team’s Trusted Committers.  This allows you to ensure that you are going down a path that your host team is happy to merge once it’s done, adhering to the "release early, release often" idea in a way.
* Try to balance between asking for a review early and providing meaningful changes to review.
* The host team’s responsibility is to create an atmosphere where sharing and discussing not-totally-polished work is possible and welcome. If you can’t fail safe, you can’t innovate, and collaboration becomes very hard. Be civil and expect civility from the Trusted Committer’s review.

---
References:

InnerSource Commons – The Mechanics of Contributing: [https://innersourcecommons.org/learn/learning-path/contributor/04/](https://innersourcecommons.org/learn/learning-path/contributor/04/)
