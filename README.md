# [Nerine](https://github.com/einuye/proposals/blob/master/ndb-specifications.txt) - RFCs & RFCs
----
Changes to the Nerine landscape have to be made to adapt it as a database to many challenges to it's ecosystem, and this repository exists as a way to formally change it as a landscape and outline the design behind the design of it. Many changes, including bug fixes and documentation improvements can be implemented and reviewed via the normal GitHub pull request workflow.

The "RFC" (request for comments) process is intended to provide a consistent and controlled path for new features to enter the ecossytem and standard libraries.

### Table of Contents

## How?
RFCs are first drafted over an [issue](https://github.com/einuye/proposals/issues), then once they are formally established with a repository with proper examples of it's implemenetation of it's own created by someone who can formally [champion](https://cdn.discordapp.com/attachments/791909945146605621/805973905415733288/unknown.png) the RFC.

All RFCs are dictated by the [process of stages](https://github.com/einuye/proposals) established.

### The beforehand.
Before creating an RFC, make sure it's thoroughly reviewed and proposed properly, otherwise its chances at acceptence become marginally low. Anything that looks low quality can easily be rejected quickly, unless proper change is made to it. Most of us don't want to be that one person who had a bright idea just for someone else to do it better than you.

Although there is no really singular proper way to prepare for submitting an RFC, it is generally a good idea to pursue feedback from other project developers or users beforehand, to ascertain that the RFC may be desirable; having a consistent impact on the project requires concerted effort toward consensus-building.

## Why?
This RFCs repository was created with the intention of providing a simple way for the community and [committee members](https://github.com/orgs/einuye/teams/einuye-proposals) of all kinds to request significant changes to the specifications of the Nerine database.

What count's as significant are:
* Any remote change to the database ecosystem that would account towards an eventual newer format version
* Removal of features to the database specifications.
* Additions to any of the major specifications for the RFC process itself.
* Changes to the main interface of the database.

While significant changes will always warrant requiring it to go through the RFC process, some changes do not require a RFC beforehand:
* Rephrasing, refactoring or otherwise changing the shape of something whilst not changing its meaning
* Additions most likely only to be noticed by library developers and specification readers, rather than the community itself. (e.g function implementation, but still providing the same result)

## A RFC's Lifecycle
A RFC has a lifecycle of it's own to go through, as determined by the stage it's in. If a RFC is determined to be "inactive", or otherwise is generally unseen and forgotten over a long period of time, then it'll be closed for a new champion to pick it up again.

"Inactive" RFCs are ones that have been rejected, or have been untouched for enough time to render it such. No matter the cause of inactivity, a new RFC [issue](https://github.com/einuye/proposals/issues) will need to be created entirely from the start of the process.

### The process itself
Aside from everything above, in short; in order to get something added to the Nerine specifications, one must first chair and champion a RFC by an [issue](https://github.com/einuye/proposals/issues). When that [issue](https://github.com/einuye/proposals/) is created, a RFC is deemed "active".

Once a RFC has been passed and approved by the community and committee, the RFC template can be formally used to induce it in the repository.

The process is usually of the following:
* The creation of an [issue](https://github.com/einuye/proposals/issues).
* Copy the template [here](https://github.com/einuye/proposals/blob/master/rfcs/0000-template.md).
* Fill in the RFC details. Please put in a compelling and persuasive argument as to why the proposal should be accepted, otherwise it may be poorly recieved.
* Build consensus and integrate feedback. RFCs that have broad support are much more likely to make progress than those that don't receive any comments.
* RFCs rarely go through this process unchanged, especially as alternatives and drawbacks are shown. You can make edits, big and small, to the RFC to clarify or change the design, but make changes as new commits to the pull request, and leave a comment on the issue properly noting your changes.
* Committee members will discuss the RFC if it gets to the proper respective stage through the issue itself, or on the [team's discussion page](https://github.com/orgs/einuye/teams/einuye-proposals/discussions).
* Once everything is done and finished, and all the expected binary examples and tests are done; it'll go to a final proper phase before being implemented into the specifications.

### RFC Reviewing
Many approved RFCs represent important, necessary features that need to be implemented right away. A few other accepted RFCs can represent features that can wait until some arbitrary developer feels like doing the work, as anyone who makes a database implementation most likely has an actual life. Every accepted RFC most likely has an associated issue tracking its implementation in other associated projects.

The author of an RFC is not obligated to implement it. Of course, the RFC author (like any other developer) is welcome to post an implementation for review after the RFC has been accepted.

If you are interested in working on the implementation for an "active" RFC, but cannot determine if someone else is already working on it, feel free to ask (e.g. by leaving a comment on the associated issue).