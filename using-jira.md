# Using the Jira Board

## Overview
The Codecademy Curriculum team uses the agile workflow features in Jira with custom configurations and fields to manage production projects. The goal for your Jira boards is to use Jira as a single source of truth across your team for your project as it automates changes and centralizes information. In this document, we will break down the agile features of the Jira.
## Introduction
Jira Software Cloud is a project management tool that allows you to plan, track, and launch projects Jira also has reporting features that allow project managers to view and take action to improve the team's performance in real-time.

Jira allows you to customize the tool to reflect your team's workflow. Jira integrates with other tools that we use at Codecademy frequently like:
- DropBox
- GitHub
- Gmail
- Google Calendar
- Google Drive
- Invision
- Slack
- Zapier
- Zendesk
- And other tools.

## Features
### Projects
Projects in Jira are a cumulative group of workflows for a specific team or group. Projects can be broken down into components, or sub-groups of smaller aspects of the larger project. Projects are made of a series of tasks, known as issues, that will be explained further in this document. Check out the key terminology for the project feature below.

| Feature | Description |
|----|----|
| Versions  | Different adaptations of the same project can be tracked and have issues assigned to them. |
| Workflow  | The sequence of steps that the tasks will follow (i.e.`In Progress`,`Resolved`). The project should follow processes that mirror the team's practices.  |
|  Screen |  Arrange the fields to filter and display specific views of the project. |
| Repositories  | Add a GitHub repository to show information about branches, commits, and pull requests required for a project inside a Jira issue.  |

### Team Members
#### Project Administrator
The project administrator, in most cases, is the team project manager. The project administrator maintains the project versions, components, and user roles.  They also maintain project boards and start/end project sprints, which we will discuss further in this document.
#### Roles in Jira
Jira enables the project administrator to assign particular users to specific roles (i.e. `Author` or `Reviewer`). Roles define user capabilities and settings like frequency of Jira notifications. The project administrator can set up Jira notifications the appropriate roles when particular events take place in a project (i.e. when an issue is moved or a comment is made). You can choose specific people, groups, or roles to receive notifications.

Roles oftentimes have different permissions associated with them. Permissions allow the project administrator to control who can access the project, and what they can do. Access to individual issues is granted to users by issue permissions.

## Jira Boards
Boards are a view of the project's workflow in the most current, or live, state of the project. Based on the workflow and anticipated outcome of the project, you must choose a Jira board style: scrum, kanban, or hybrid.

### Kanban Boards
We will be managing course production with a kanban board. Kanban boards manage work by visually displaying work and/or project tasks at various stages of the project or process.

Swimlanes -  help you distinguish tasks of different categories, such as workstreams (horizontal for Scrum, vertical for kanban) - you can add limits to this
Adding maximum for issues in a column
Prioritizing items that are added to the potential work list then only commencing work on items when capacity exists to take them on (may use a backlog but not necessary for most projects.)
Tracking items in progress so that items that have started are completed before new work is taken on
Ensuring that items that are in progress do not get blocked indefinitely at any particular stage of the work
Place priority on issues - Work items are ranked in priority order (from top to bottom) 
See how long items have been in the columns
WIP limits set the maximum amount of work that can exist in each status of a workflow
improve throughput and reduce the amount of work "nearly done" - no idleness or overload
make blockers and bottlenecks visible. Teams can swarm around blocking issues to get them understood, implemented, and resolved
Important to size individual tasks consistently.
Hybrid Boards
Kanplan is ideal for teams who want the ability to backlog groom, but don’t want to work in sprints. (kanban with a backlog) Instead of having a long and disorganized to-do list with daily stand-ups and weekly planning meetings, we have a backlog
Scrumban uses sprints with a backlog, WIP limits and cycle time from kanban. (Note: cycle time is the amount of time it takes for a task to go through a team’s workflow.)

## Issues
Issues have progress statuses
Issue types can be user stories, tasks, sub-tasks, bugs, spikes, support, improvement, etc
Epics are a type of issue that has distinct starts and ends, lasts multiple sprints (not a grouping of items, thats a component), contain stories, bugs, tasks that have the same priority level; determine what your epics for the project board will be first (Add course description, priority, and assign to someone)!
Stories are user stories
Bugs are problems which impairs or prevents the functions of the product - this takes less priority than a standard task
Improvement type describes a change that should be made but takes less priority than a standard bug or task)
Subtasks are when multiple people are working on a story or bug
You can add flags to alert that you need help with something
Add task dependencies, attachments, code snippets
You can add custom fields like time in status and days since the last comment on card
