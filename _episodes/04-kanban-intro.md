---
title: "Introduction to Kanban."
teaching: 5
exercises: 60
questions:
- "What is Kanban?"
- "What is a Kanban board?"
- "Kanban vs Scrum?"
- "Can we combine Scrum and Kanban?"
objectives:
- "Describe the Kanban method"
- "Understand how to work using a Kanban board"
- ""
keypoints:
- "Kanban is a framework used to implement Agile for software development."
- ""
---

## What is Kanban?

Kanban is a process managemnet method. It balances demands with available
capacity and improves the handling of bottelnecks. You can simply apply Kanban to
your current process of developing software.

You may often hear that Kanban is a `pull` system. It means that a new work-item
is pulled to the process as capacity permits. We will explain this in the next
section where we introduce a Kanban board. Read more about Kanban
[here](https://www.atlassian.com/agile/kanban).

> ## Did you know...
>
> Kanban is the Japanese word for signboard or billboard.
{: .callout}

## What is a Kanban board?

A kanban board is a project management tool designed to visualize processes,
define tasks, and manage backlog-items. It helps to show/record `what`, `how`
and `who` aspects of a work-item and keep everyone on the same page. A Kanban
board uses cards, columns, and continuous improvement to help teams commit to
the right amount of work, and get it done!

<!-- TODO add a figure  -->

### Cards

Team members divide the work into some work-items and write onto cards
(stickies, or tickets), usually one per card. For Agile teams, each card could
represent one user story. Once on the board, these cards help everyone
understand what the team is working on.

Also, each card shold have "acceptance criteria" (AC). AC are a set of
statements that define how a user story can be completed.

> ## Who writes acceptance criteria
>
> Generally speaking the "Product Owner" defines the product backlog, and
> acceptance criteria (AC). However, it is a good practice if team members
> contributed to wrting AC.
>
{: .callout}

### Columns

Columns together show the process or workflow. Each column represents a specific
activity, for example “To Do", “In Progress”, Done". Cards flow through the
workflow until completion, i.e. from the left to right side of the board.

<!-- TODO add more examples -->
> ## More examples of Kanban Columns
>
>
{: .callout}


### Continuous improvement

Cntinuous improvemnets can be achived by three elements: Commitment point, Work
In Progress (WIP) Limits, and Delivery point.

#### Commitment point

Teams often have a product (or project) backlog that includes some work-items.
The commitment point is the moment when a work-item is picked up by the team,
i.e. a card is moved from backlog to “To Do" column.

> ## Product backlog
>
> A product backlog is a prioritized list of work like a todo list that is
> derived from the project requirements and ideas.
> Read more about it [here](https://www.atlassian.com/agile/scrum/backlogs).
>
{: .callout}

#### Work In Progress (WIP) limits

WIP limits are the maximum number of cards in “In Progress” column. For example,
the column with a WIP limit=3 cannot have more than three cards in it.

> ## Q and A
>
> - How to estimate WIP limits?
>
> WIP limits is an estimation of how much work the team can commit to. So, it
> can vary depending on the team capacity and can be adjusted after a few
> trials.
>
> - What if the “In Progress” column is “maxed-out”?
>
> When the "In Progress” column is “maxed-out”, the team needs to check if some
> cards can be moved forward before adding new cards. If not, the team should
> inspect the problem. Sometimes, either the WIP limits or the amount of the
> work to commit in the current workflow need to be estimated again. Also, the
> team might re-visit the acceptance ceriteria of a work-item.
>
{: .callout}

#### Delivery point

The delivery point is the end of a kanban workflow, i.e. all cards from “To Do"
moved to "Done". The team’s goal is to move cards from the commitment point to
the delivery point as fast as possible.

<!-- TODO add a discussion about a workflow, clumn names -->
> ## Discussion
>
>
{: .discussion}

## Combining Scrum and Kanban (Scrumban)

Kanban is great for processes focused on continuous delivery with changing
priorities. On the other hand, Scrum divides work into a series of time-boxed
iterations called sprints (see [episode 3](./03-scrum-into.md)).

But maybe a combination of scrum and kanban (it is called Scrumban) is what your
team would benefit the most from.

Scrumban manifests itself in different ways depending on your team
characteristics. The team may use team meetings (like retrospective and
planning) from Scrum and a continuous workflow with WIP limits from Kanban.

> ## Discussion
>
>
{: .discussion}

{% include links.md %}

