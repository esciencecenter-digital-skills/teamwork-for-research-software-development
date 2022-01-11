---
title: "Introduction to Kanban"
teaching: 15
exercises: 30
questions:
- "What is Kanban?"
- "What is a Kanban board?"
- "Can we combine Scrum and Kanban?"
objectives:
- "Describe the Kanban method"
- "Understand how to use a Kanban board"
keypoints:
- "Kanban consists of cards, columns, and continuous improvement."
- "Main elements of continuous improvements: Commitment point, Work In Progress
  (WIP) Limits, and Delivery point."
---

## What is Kanban?

Kanban is a process management method. It balances demands with available
capacity and improves the handling of bottlenecks. You can simply apply Kanban to
your current process of developing software.

You may often hear that Kanban is a "**pull**" system. It means that a new work-item
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

Here is an example of a Kanban board created using
[GitHub project boards](https://docs.github.com/en/issues/organizing-your-work-with-project-boards):

![Kanban board](../fig/kanban_board.png)

### Cards

Team members divide the work into some work-items and write onto cards
(stickies, or tickets), usually one per card. For Agile teams, each card could
represent one user story. Once on the board, these cards help everyone
understand what the team is working on.

Each card should also have "acceptance criteria" (AC). AC is a set of
statements that define how a user story can be completed.

> ## Who writes acceptance criteria
>
> Generally speaking, the "Product Owner" defines the product backlog, and
> acceptance criteria (AC). However, it is a good practice if team members
> contribute to writing AC.
>
{: .callout}

### Columns

Columns together show the process or workflow. Each column represents a specific
activity, for example “To Do", “In Progress”, "Done". Cards flow through the
workflow until completion, i.e. from the left to the right side of the board.

- What if your team works on more than one project/product?

If your team works on several projects/products, you can add one row (Swim Lane)
for each of them. As an alternative, your team may decide to have a time-boxed
workflow and work on one project at a time, see the section "Combining Scrum and
Kanban (Scrumban)" in this lesson.

> ## More examples of Kanban workflows (i.e. columns)
>
> - To Do, Doing, Done.
> - To Do, In Progress, Review, Done.
> - To Do, In Progress, Demo, Done.
> - Committed, Analysed, In Progress, Done.
> - Ready, Estimate, Development, Test, Done.
{: .callout}

### Continuous improvement

Continuous improvements can be achieved by three elements: Commitment point, Work
In Progress (WIP) Limits, and Delivery point.

#### Commitment point

Teams often have a product (or project) backlog that includes some work-items.
The commitment point is the moment when a work-item from backlog is picked up by
the team. In other words, a card is moved from backlog to “To Do" column.

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

 - How to estimate WIP limits?

 WIP limits is an estimation of how much work the team can commit to. So, it can
   vary depending on the team capacity and can be adjusted after a few trials.

- What if the “In Progress” column is “maxed-out”?

When the "In Progress” column is “maxed-out”, the team needs to check if some
  cards can be moved forward before adding new cards. If not, the team should
  inspect the problem. Sometimes, either the WIP limits or the amount of the
  work to commit in the current workflow need to be estimated again. Also, the
  team might re-visit the acceptance criteria of a work-item.

#### Delivery point

The delivery point is the end of a kanban workflow, i.e. all cards from “To Do"
moved to "Done". The team’s goal is to move cards from the commitment point to
the delivery point as fast as possible.

> ## Other Kanban boards
>
> Have a look at the examples of Kanban workflow (mentioned above).
>
> - Which of those can be used for the projects in your team?
> - What other workflows, if any, are you implementing in your team?
>
{: .discussion}

> ## Designing a Kanban board
>
> Imagine that you are working on a project.
>
> - Let's create a Kanban board using
[GitHub project boards](https://docs.github.com/en/issues/organizing-your-work-with-project-boards).
> - Discuss the board with your colleagues.
>
{: .discussion}

> ## Exercise
>
> Imagine that you are working with a Kanban board. One of the work items in “In
> Progress” got blocked. The _blocked_ item means that the team is not able to
> continue working on it because it is waiting for something from outside the
> team. How do you deal with the blocked item in the Kanban workflow?
>
> > ## Solution
> >
> > The simplest but effective approach is to put a "red dot" on the item. In an
> online board, it is possible to add a tag/label and more information like why
> this item is blocked, for how long, and who will unblock it. This visualizes
> the situation. So, the team can immediately see that the item is blocked and
> have it under control.
> Now, the blocked item does not count as a WIP item and 
> the team could potentially add an extra work-item to 'In Progress'.
> {: .solution}
{: .challenge}

## Summary

Kanban is great for processes focused on continuous delivery with changing
priorities. On the other hand, Scrum divides work into a series of time-boxed
iterations called sprints (see [episode 3](./03-scrum-into.md)). But maybe a
combination of Scrum and Kanban (known as "ScrumBan") is what your team would
benefit the most from. We will learn about it in the [next
lesson](./05-comparing-agile-methodologies.md).

> ## Discussion
>
> Think about following the Kanban methodology when working on your projects in a team.
>
> - What questions do you still have?
> - Are there any incremental improvements that can benefit your team?
> - What did you learn in the online course that you think is too much for your team?
{: .discussion}

Challenges specific to research projects will be discussed later, in [episode 6](06-agile-in-research.md).

{% include links.md %}
