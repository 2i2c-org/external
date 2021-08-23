# Coordinating upstream work

This is a lightweight repository to facilitate planning deliverables and tasks for projects that do not have a natural repository inside of 2i2c.


## Goals of this repository

2i2c needs to coordinate its priorities and work as a team, but doesn't wish to create silos of discussion around work that happens in upstream communities. The `upstream/` repository exists to be a bridge between 2i2c's work and these communities.

We want this repository to be as lightweight as possible - it is just a place for us to keep track of items we wish to work on, not a place for discussion.


## How to use this repository

**Create tracking issues only**.
Each issue in this repository should be a **tracking issue** that points somewhere else. For example, to one or more issues or pull requests in an upstream repository.

**Do not use this repository for long-term planning**.
Any longer-term planning or roadmapping should be done in an upstream repository. We do not use this repository to project plan over longer periods of time, *only* to track issues that we want to work on soon (say, within a few sprints).

**Upstream issues should exist first**.
Upstream issues are the "real" location for discussion, and should exist first before issues are created here. Any decisions about implementation should already happen upstream before we decide to work on something ourselves.

**Each issue should have a project label**.
These are GitHub labels structured like `proj: <project-name>`.
The project label helps us know where else an issue refers to, and helps team members filter and sort them in our project boards.

**Conversations happen in upstream repositories**.
If there are conversations that must happen around the work, these should happen in upstream repositories, not here. The "comments" in any of the issues in this repository should be as minimal as possible.
