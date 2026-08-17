<h1 align="center"><span style="color: #d21f26">McGill Rocket Team</span> <br> Orbital CubeSat Division</h1>
<p align="center">
    <img src="/assets/ocs-logo.png" alt="ocs logo" width="30%">
</p>

## About Us

We are the Orbital CubeSat (OCS) Division of the [McGill Rocket Team](https://github.com/McGillRocketTeam) (MRT). We build satelittes and (try to) launch them to space. We made this Organization to separate both division's repositories.

Learn more about us on our [website](https://mcgillrocketteam.com/cubesat/).

## Division Organization

The OCS division is currently divided into the following projects

| Project Code | Project Short Name | Name | Description |
| - | - | - | - |
| OCS 1 | MECH | Structures and Mechanisms | Mechanical stuff |
| OCS 2 | C&DH | Command & Data Handling | On-board Computer (OBC), Microcontrollers, Software, The "brains" of the CubeSat | 
| OCS 3 | SATCOMMS | Space-Ground Communications | Radios, Ground Station, Communication, etc. |
| OCS 4 | ADCS | Attitude Determination and Control | ADCS System, Orientation, Control Systems |
| OCS 5 | POWER | Power | Batteries and such |
| OCS 6 | PAYLOAD | Payload | The mission of the satellite, or the "Why are we doing all this?" |
| OCS 7 | HAB | High-altitude Balloon | Sending balloons **very** high into the air |

## Contribution Rules

In the sprit of keeping our repositories organized, there are some rules to follow when contributing to this organization (creating new repos, pushing code, etc). **All** members, new and existing, must read and get acquainted with these rules.

### GitHub 101

We are aware that for newer or less experienced members, this might be your first time using git/github and working in a collaborative coding environment. That's all right! We all went through the same, and we are all here to learn something new. We recommend the following resources for learning the basics of git and github. For those of you in CS/ECSE, this is also something that should be thought in your classes.

- TODO list of resources on github and github (i think there already exists some tutorials/documents in the Drive, to confirm)

### Repository names

When creating new repositories, use the following naming convention:

```
TODO
```
Examples:
```
TODO
```

- Repository names to be written in lowercase with dashes (`-`) between words
- Avoid vague and generic names, e.g. `obc`, `radio`, `hardware`
- If hosting a design revision in the repository, include the revision number in the name of the repo, i.e. prefer `obc-hardware-rev1` or `obc-hardware-1.0` over simply `obc-hardware`

### Branches

Use `main` as your primary branch name. **Don't** use `master`

We **highly** encourage, if not enforce, the use of branches in your projects.

Please use the following standard naming convention for your branches:
```
feature/[name] # new feature or element working on
fix/[name] # bug fixes and quick fixes
docs/[name] # documentation
```

- Avoid general and vague names, e.g. `fix/bug` or `feature/work`
- Don't use your name as a branch name, instead write what you do in the branch, e.g. `feature/schematic` instead of `feature/joe`

As for branching, unless you know that you will be merging into another branch that is not `main` (and by consequence opening your new branch from that branch), always branchout from the `main` branch. Trust me, this simplifies merging back to `main` later.

### Commits and pushing

- Take the time to write a meaningful commit message, even if short.
    - Yes, it sucks and sometimes you don't know what to write, but trust me that added 10 seconds to think and write your commit message will save you lots later. Especially if you need to revert and refer back to previous work.
- In 95% of ocassions, **never** push directly into the `main` branch.
    - Instead, work on a branch, create a PR, and have it reviewed/merged to `main`.

> [!TIP]
> For leads, try to add rules to the repos you manage to restrict pushes to main and force PRs/reviews/approvals. Will save you headaches, especially in messy repos ;)

### Pull requests and review

- Most code (at the discretion of the Project Lead) should be PR'd before it is merged or pushed to `main`
- TODO PR template (?)
- For members: validate with your project lead about their PR review rules. In general however, you should get your PR reviewed by your lead before merging
- For leads: at your discretion, but try to lead by example and keep clean commits, branches, and PRs. No harm in creating, reviewing, and merging your own PR

### Documentation

It is **required** to keep good documentation in your repos. The reason for that is simple: people come and go, and it is crucial for information to be tracked for future members who will join in future years. Having well documented work helps avoiding double working and facilitates knowledge transfer.

As for documentation rules, generally the more the better (still try to keep it simple and avoid AI slop documentation). The minimum required in a repo should be a `README` file detailing:

- What the project is / how to run it / what it does
- The date
- People involved, mainly the lead
- The state of the project (completed, work in progress, archived/depecrated)
- Any useful links to documents (Data sheets, Google Drive files, meeting notes, etc)

## Communication

All division and team communications are to be done in the appropriate MRT Slack channels.
