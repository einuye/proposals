# [Nerine](https://github.com/einuye/proposals/blob/master/ndb-specifications.txt) - RFCs & RFCs
----
Changes to the Nerine landscape have to be made to adapt it as a database to many challenges to it's ecosystem, and this repository exists as a way to formally change it as a landscape and outline the design behind the design of it. Many changes, including bug fixes and documentation improvements can be implemented and reviewed via the normal GitHub pull request workflow.

The "RFC" (request for comments) process is intended to provide a consistent and controlled path for new features to enter the ecossytem and standard libraries.

### Table of Contents

## How?
RFCs are first drafted over an [issue](https://github.com/einuye/proposals/issues), then once they are formally established with a repository with proper examples of it's implemenetation of it's own created by someone who can formally [champion](https://cdn.discordapp.com/attachments/791909945146605621/805973905415733288/unknown.png) the RFC.

All RFCs are dictated by the [process of stages](https://github.com/einuye/proposals) established.

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
* Copy the template in