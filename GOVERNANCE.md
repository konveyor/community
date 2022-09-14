## Konveyor Governance

The Konveyor project is composed as a consortium of individual projects, some independent and some interdependent, each of which focuses on some aspect of migrating applications and infrastructure to Kubernetes.  Our governance reflects this federated structure.

## Individual Project Governance

Each individual project is permitted to have its own governance structure if the maintainers of the project wish it, provided that its governance is "open" (defined below).  Should a project's members be ambivalent about governance, or join Konveyor with no governance in place, the project will adopt the "default governance" structure.

## Community Groups

Konveyor project consists of various Special Interest Groups AKA SIGs. Konveyor SIGs are based on Kubernetes SIGs. 

### Special Interest Groups

Each SIG in the Konveyor project pertains to advancing the project in a specific area, like Core components or UI. Each SIG will be led by two or three co-chairs. Initial bootstrapping of the SIGs will be led a chair appointed by the Konveyor Maintainers. As the members move through the contributor ladder, they will be eligible to be a co-chair after they have been a maintainer for 3-6 months. Konveyor steering committee will vote on the co-chair nominations.  

## Contributor Participation

Members, Reviewers, and Maintainers are defined in the [Konveyor Contributor Ladder](https://github.com/konveyor/community/blob/main/contributor_ladder.md).  Each project will have its own Members, Reviewers, and Maintainers according to those criteria.  Members, Reviewers, and Maintainers of any project are also considered Members of the overall Konveyor umbrella project for governance purposes, but not for purposes of code repository permissions.  

### Governance Requirements

All Konveyor projects are required to have "open" governance of some kind.  Open governance is defined by the following principles:

1. The governance structure is fully documented in a GOVERNANCE file.
2. All regular contributors are eligible to be project members, regardless of employer, nationality, or other characteristics.
3. Most meetings or discussions of project leadership are open to all project members.
4. Leadership positions are held by individuals, not companies.
5. All project members are eligible for advancement within the project based on clearly defined criteria.
6. All project members who meet clearly defined leadership criteria are eligible for leadership positions.
7. There is a defined cadence of leadership replacement, annually or more frequently.
8. Governance rules are modifiable by project leaders through a defined process.
9. The project adopts, and adheres to, the Code of Conduct.

Within these requirements, projects may be governed by a council of code maintainers, an elected committee, an elected project lead, or even a self-selecting committee with regular rotation.  Projects may choose the form that works best for them, as long as it's documented.  Members of the Konveyor Steering Committee are available to review project governance to ensure that it fits Open Governance requirements.

### Default Project Governance

Most projects that join Konveyor will not have a governance structure in place, in which case they "default" to Maintainer Governance:

All active Maintainers of the project, as defined in the Konveyor Contributor Ladder, are members of the Maintainer Committee, which governs that project.  The project's Maintainer Committee is responsible for the following project governance activities:

* Ensuring that the project creates and publishes regular releases;
* Holding regular, project-wide discussions on issues and planning for the project;
* Monthly review of project contributors for advancement on the Contributor Ladder;
* Making final decisions on project changes that involve controversial trade-offs;
* Responding to security compromise reports;
* Supporting the Code of Conduct within their project and referring violations to the Code of Conduct Committee.

Additionally, the Maintainer Committee will select, by majority vote, one representative of the project to the Konveyor Steering Committee.  This representative need not be a member of the project's Maintainer Committee, and will be replaced or renewed by the Committee annually.

Should a member of the Maintainer Committee cease being active in the project, violate the Code Of Conduct, or need to be removed for some other reason, they may be removed by a 2/3 majority vote of the other Committee members, or a vote of the Steering Committee.

## Konveyor Steering Committee

The overall Konveyor umbrella project is governed by a Steering Committee, which is selected as follows:

* One representative from each Konveyor project
* One overall "Maintainer Representative"
* One overall "Member Representative"

### Steering Committee Duties

The Steering Committee is responsible for the following tasks, any of which may be delegated to a person or group selected by the committee:

* Reviewing and deciding on new projects to add to Konveyor
* Arbitrating inter-project disagreements
* Selecting the Code of Conduct Committee and ratifying CoC judgements
* Removing projects from Konveyor which have become inactive
* Acting on escalated requests from security or code quality issues
* Administering Konveyor project infrastructure, intellectual property, and resources
* Determining overall direction for advocacy and marketing of Konveyor
* Resolving project issues that individual projects are unable to resolve
* Issue statements on behalf of Konveyor and its projects
* Reviewing and approving Contributor Ladder advancement for participants who work on the overall umbrella project

In performance of these duties, the Steering Committee will hold a monthly meeting that is open to all Members.  The Committee may hold additional, closed meetings in order to discuss non-public issues such as security exploits, CoC enforcement, and legal questions.  Decisions are confirmed if they receive the endorsement of a majority of Steering members, except where otherwise noted.

Steering Committee members are expected to advocate for all of Konveyor, not just certain projects or corporate sponsors, comply with and support the Code of Conduct, and be professional and compassionate in all of their dealings with project participants.

### Steering Committee Elections

The Maintainer Representative will be elected by the collective Maintainers of all Konveyor projects, as defined in the Contributor Ladder and accepted by the projects.  The Member representative will be elected by the collective Members of all Konveyor projects, as defined in the Contributor Ladder.  These positions will be elected annually.

Once per year, the Steering Committee will select between one and three Election Officers to run the annual election and sets the dates for the election.  These officers will update the list of eligible Maintainers and Members according to project records, send out announcements, and conduct the election.  The election starts with a call for nominations, which lasts for at least one week, and will include a period for project Members to request changes to their voting status. Candidates may nominate themselves, or they may be nominated by their colleagues. 

The election itself will last for at least one week, and is conducted as a preference election online, using a method such as Condorcet or IRV.  The Election Officers will announce the selected candidates at the next regular community meeting.

## Code of Conduct Committee

In order to review and enforce the Code Of Conduct, the Steering Committee selects three to five people to be on the Code of Conduct Committee.  These individuals will be chosen based on their experience in community management and conduct issues, and to represent a diversity of viewpoints, including employer, gender, race, and region of the world.  To avoid fatigue, the Steering Committee will replace at least one member of the CoC Committee each year.  Members of the committee do not need to be members of Konveyor if they have sufficient other expertise.

The CoC Committee will receive reports of conduct violations confidentially, and will discuss them in closed meetings.  If a report is determined to be a violation, they will recommend action on it appropriate to the scale, nature, and context of the violation, from requiring an apology, up to expulsion of an individual from the project.  In the event that a contributor is to be demoted or expelled, the CoC Committee will forward this recommendation to the Steering Committee who will ratify it in a closed meeting.  Should a member of the Steering Committee be the offender, they will recuse themselves from that meeting.

## Projects Joining Konveyor

During the monthly Steering meeting, any project member may recommend projects to become part of Konveyor.  These projects should have the following characteristics:

* Have a mission of enabling migration to Kubernetes;
* Are appropriately licensed and governed or willing to become so;
* Are under active development;
* Consist of high quality code and designs.

Projects meeting the criteria must vote by consensus of all major contributors to join Konveyor.  The Steering Committee will then review the project, and decide whether or not to accept it.  If it is accepted, the Committee will assign one person to assist the project in their integration into Konveyor.

In some cases, promising but incomplete projects may be accepted as Experimental Projects in Konveyor.  Such Experimental Projects will be considered part of Konveyor, but will be marked as Experimental on the Konveyor site and in Github repos, in order to inform users.  Experimental project Members are considered Members of Konveyor, but the project is not entitled to a representative on the Steering Committee.  Steering will review Experimental Projects at least twice per year to determine if they have matured to full project status.

## Removing Projects

In some cases, projects will become inactive or unmaintainable, or wish to separate from Konveyor. Any Steering Committee member may propose removal of a project on these grounds, and Steering can confirm this with a majority vote.

Projects which still have contributors will then be moved to a repository in their own namespace.  Projects which have ceased all activity are moved to a "konveyor-archive" namespace.
