# Contributor Ladder

* [Contributor Ladder](##contributor-ladder-template)
    * [Contributor](###contributor)
    * [Member](###member)
    * [Reviewer](###reviewer)
    * [Approver](###approver)
* [Inactivity](##inactivity)
* [Involuntary Removal](##involuntary-removal)
* [Stepping Down/Emeritus Process](##stepping-downemeritus-process)
* [Contact](##contact)


## Contributor Ladder

Hello! We are excited that you want to learn more about contributing to Konveyor. This "contributor ladder" outlines the different contributor roles within the project, along with the responsibilites and privileges that come with them. Community members generally start at the first levels of the ladder and advance up it as their involvement in the project grows.  Our project members are happy to help you advance along it.

Each of the contributor roles below is organized into lists of three types of things. "Responsibilities" are things that contributor is expected to do. "Requirements" are qualifications a person needs to meet to be in that role, and "Rights" are things contributors on that level are entitled to.


### Contributor

Description: A Contributor contributes directly to the Konveyor ecosystem and adds value to it. Contributions need not be code. People at the Contributor level may be new contributors, or they may only contribute occasionally.

* Responsibilities include:
    * Must follow the [Konveyor Code of Conduct](TODO:Add Code of Conduct)
    * Following the project contributing guide(s)
* Requirements (one or several of the below):
    * Participates [community discussions](https://github.com/konveyor/community#communication)
    * Reports and sometimes resolves issues
    * Occasionally submits PRs
    * Contributes to the documentation
    * Regularly shows up at meetings, takes notes
    * Answers questions from other community members
    * Submits feedback on issues and PRs
    * Tests releases and patches and submits reviews
    * Runs or helps run events
    * Promotes the project in public
    * Helps run some part of the project infrastructure
* Privileges:
    * Invitations to contributor events
    * Eligible to become a Project Member


### Member

Description: A Member is an established contributor who regularly participates in the Konveyor ecosystem. Members have privileges in both project repositories and elections, and as such are expected to act in the interests of the whole project.

A Member must meet the responsibilities and has the requirements of a Contributor, plus:

* Responsibilities include:
    * Continues to contribute regularly, as demonstrated by having at least [TODO: Number] contributions a year, as demonstrated by [TODO: contributor metrics source].

* Requirements:
    * Must have successful contributions to the project, including at least one of the following:
        * Authored or co-authored 2 accepted PRs,
        * Reviewed 2 PRs,
        * Led resolution of 2 Issues,
        * Become responsible for a key project management area,
        * Or some equivalent combination or contribution
    * Must have been contributing for at least 2 months
    * Must have two sponsors who are also Members
    * Must enable 2FA on their GitHub account
    * Must be subscribed to the Konveyor.io mailing list.

* Privileges:
    * May be assigned Issues and Reviews
    * May give commands to CI/CD automation
    * Entitled to vote for the Member Representative to the Steering Committee
    * Can be added to GitHub teams
    * Can recommend other contributors to become Members

The process for a Contributor to become a Project Member is as follows:

1. The nominator will open an issue against the Community repository, titled "Candidate for  Membership: NAME". Candidates may self-nominate.
2. This issue will tag two current project members (sponsors) who can attest to the candidate's contributions.
3. Both sponsors will +1 the nomination.
4. A member of the Konveyor Github admin team will add the new project member to the Github organization and any appropriate teams.

Note: once a project has three or more Project Members who do not work for the same employer as the largest group of Project Members, sponsors must include at least one Member who does not work for the same employer as the nominee.

### Reviewer

Description: A Reviewer has responsibility for specific code, documentation, test, or other project areas. They are collectively responsible, with other Reviewers, for reviewing all changes to those areas and indicating whether those changes are ready to merge. They have a track record of contribution and review in the project.

Reviewers are responsible for a "specific area." This can be a specific code directory, driver, chapter of the docs, test job, event, or other clearly-defined project component that is smaller than an entire repository or project. Most often it is one or a set of directories in one or more Git repositories. The "specific area" below refers to this area of responsibility.

Reviewers have all the rights and responsibilities of an Project Member, plus:

* Responsibilities include:
    * Following the reviewing guide
    * Reviewing most Pull Requests against their specific areas of responsibility
    * Reviewing at least 5 PRs per year
    * Helping other contributors become reviewers
* Requirements:
    * Experience as a Contributor for at least 3 months
    * Is a Konveyor org Member
    * Has reviewed, or helped review, at least 8 Pull Requests
    * Has analyzed and resolved test failures in their specific area
    * Has demonstrated an in-depth knowledge of the specific area
    * Commits to being responsible for that specific area
    * Is supportive of new and occasional contributors and helps get useful PRs in shape to commit
* Additional privileges:
    * Has Github or CICD rights to approve pull requests in specific directories
    * Can recommend and review other contributors to become Reviewers

The process of becoming a Reviewer is:

1. The contributor is nominated by opening a PR against the appropriate repository, which adds the to the OWNERS file for one or more directories.
2. At least two members of the team that owns that repository or main directory, who are already Approvers, approve the PR.


### Project Approver

Description: Approvers are very established contributors who are responsible for the entire project/repo. As such, they have the ability to approve PRs against any area of that project/repo, and are expected to participate in making decisions about the strategy and priorities of the project and of Konveyor overall.

An Approver must meet the rights, responsibilities, and requirements of a Reviewer, plus:

* Responsibilities include:
    * Reviewing at least 10 PRs per year, especially PRs that involve multiple parts of the project
    * Mentoring new Reviewers
    * Writing refactoring PRs
    * Participating in CNCF maintainer activities
    * Determining strategy and policy for the project
    * Participating in, and leading, community meetings
* Requirements
    * Experience as a Reviewer for at least 3-6 months
    * Demonstrates a broad knowledge of the project across multiple areas
    * Is able to exercise judgement for the good of the project, independent of their employer, friends, or team
    * Mentors other contributors
    * Can commit to spending at least 15 hours per month working on the project
* Additional privileges:
    * Approve PRs to any area of the Project
    * Vote in Project Approver decision-making meetings
    * Eligible to represent the project on the Steering Committee
    * Eligible to run for, and vote for, Maintainer Representative in Steering Committee elections

Process of becoming an Approver:
1. Any current Approver may nominate a current Reviewer to become a new Approver, by opening a PR against the root of the main code or documentation repository for the project, adding the nominee as an Approver in the OWNERS file.
2. The nominee will add a comment to the PR testifying that they agree to all requirements of becoming an Approver.
3. A majority of the current Approvers must then approve the PR.

## Inactivity

It is important for contributors to be and stay active to set an example and show committment to the project. Inactivity is harmful to the project as it may lead to unexpected delays, contributor attrition, and a lost of trust in the project.

* Inactivity is measured by:
    * Periods of no contributions for longer than 9 months
    * Periods of no communication for longer than 5 months
* Consequences of being inactive include:
    * Involuntary removal or demotion
    * Being asked to move to Emeritus status

## Involuntary Removal or Demotion

Involuntary removal/demotion of a contributor happens when responsibilities and requirements aren't being met. This may include repeated pattern of inactivity, extended period of inactivity, a period of failing to meet the requirements of your role, and/or a violation of the Code of Conduct. This process is important because it protects the community and its deliverables while also opens up opportunities for new contributors to step in.

Involuntary removal or demotion is handled through a vote by a majority of the current Approvers.

## Stepping Down/Emeritus Process
If and when contributors' commitment levels change, contributors can consider stepping down (moving down the contributor ladder) vs moving to emeritus status (completely stepping away from the project).

Contact the Project Approvers about changing to Emeritus status, or reducing your contributor level.

## Contact

For community needs/issues please reach out to [the Konveyor Leads](konveyor-leads@googlegroups.com)
