## About the RFC.md Template

This template will help InnerSource projects that want to achieve high participation rates and make the best possible decisions for everybody involved. An internal Request for Comments (RFC) is a way to create participatory systems throughout the full software lifecycle. Publishing RFC documents creates the opportunity for discussions early on in the design process, and increases the chances to build solutions with a high degree of commitment from all involved parties.

Contributors may have different requirements for the given project. They may want to add features to the project that are not compatible with one another or lead to an unhealthy bloat in the architecture. A RFC can help reveal such disagreements or misunderstanding early in the process, before the software is built. This will eliminate costly conflicts and frustrations by all parties involved. They can prevent disruption to the health of the collaboration culture in the project.

A common situation where such a disagreement surfaces is a pull request that is open for a long time because the author of the PR and the maintainers of the project don’t agree that the proposed change should be made. The RFC can help prevent these situations from occurring.

## Notes About the Template

* This can be used as a documents in a folder in your projects repository or it can be used as a template in the discussions section of the repository. More guidance around this will be provided as workflows are created.

Below is the InnerSource RFC template based on the InnerSource [RFC pattern](https://patterns.innersourcecommons.org/appendix/extras/rfc). This is an optional, but highly recommended.

_____________________________________________________________________________________________________________________

## Request for Comment

Publishing internal Requests for Comments (RFCs) documents facilitates discussions early on in the design process. It increases the opportunities to build solutions with a high degree of commitment from all parties involved.

* Feature Name: (fill me in with a unique identifier, `my_awesome_feature`)
* Start Date: (fill me in with today's date, YYYY-MM-DD)
* Nominated owners: (Representatives of technical ownership areas affected by the RFC. This will often be tech leads, but they may delegate. RFCs cannot be accepted until all nominated owners have signed off.)

## Summary

One paragraph explanation of the feature.

## Retrospective

This section is essential to allow us to learn from the things we are implementing.

_When is the retrospective?_

[ ] Retro completed?

(where/how it will be held, how can people get involved, where are the results?)

## Motivation

Why are we doing this? What use cases does it support? What is the expected outcome?

## Guide-level explanation

Explain the proposal as if it was already existing and you were teaching it to another engineer. That generally means:

* Introducing new named concepts.
* Explaining the feature largely in terms of examples.
* Explaining how engineers should think about the feature. It should explain the impact as concretely as possible.
* If applicable (e.g. code/architecture proposal), provide sample error messages, deprecation warnings, or migration guidance.
* If applicable, describe the differences between teaching this to existing engineers and new engineers.

For implementation-oriented RFCs, this section should focus on how contributors should think about the change, and give examples of its concrete impact. For policy/process RFCs, this section should provide an example-driven introduction to the policy/process, and explain its impact in concrete terms.

## Reference-level explanation

This is the technical portion of the RFC. Explain the design in sufficient detail that:

* Its interaction with other features is clear.
* It is reasonably clear how the feature would be implemented.
* Corner cases are dissected by example.

The section should return to the examples given in the previous section, and explain more fully how the detailed proposal makes those examples work.

## Drawbacks

Why should we _not_ do this?

## Rationale and alternatives

* Why is this design the best in the space of possible designs?
* What other designs have been considered and what is the rationale for not choosing them?
* What is the impact of not doing this?

## Prior art

Discuss prior art, both the good and the bad, in relation to this proposal.
A few examples of what this can include are:

* For language, library, tools etc: Does this feature exist in other places and what experience has their community had?
* For community proposals: Is this done by some other community and what were their experiences with it?
* For other teams: What lessons can we learn from what other communities have done here?
* Papers: Are there any published papers or great posts that discuss this? If you have some relevant papers to refer to, this can serve as a more detailed theoretical background.

This section is intended to encourage you as an author to think about the lessons from other places, provide readers of your RFC with a fuller picture.
If there is no prior art, that is fine&mdash;your ideas are interesting to us whether they are brand new or adapted from other places.

## Unresolved questions

* What parts of the design do you expect to resolve through the RFC process before this gets merged?
* What parts of the design do you expect to resolve through the implementation of this feature before stabilization?
* What related issues do you consider out of scope for this RFC that could be addressed in the future independently of the solution that comes out of this RFC?

## Future possibilities

Think about what the natural extension and evolution of your proposal would be and how it would affect the teams and projects as a whole in a holistic way. Try to use this section as a tool to more fully consider all possible interactions with the project and teams in your proposal. Also consider how this all fits into the roadmap for the project and of the relevant sub-team. This is also a good place to "dump ideas," if they are out of scope for the RFC you are writing but otherwise related. If you have tried and cannot think of any future possibilities, simply state that you cannot think of anything.

Note that having something written down in the future-possibilities section is not a reason to accept the current or a future RFC; such notes should be in the section on motivation or rationale in this or subsequent RFCs. The section merely provides additional information.

For more information see this InnerSource [RFC pattern](https://patterns.innersourcecommons.org/appendix/extras/rfc).
