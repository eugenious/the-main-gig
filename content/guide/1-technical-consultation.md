---
title: "1 - The Technical Consultation"
weight: 2
---

_Have a chat with one or two other developers about the task before starting to code._

In modern software development, development effort is typically carved out in bite-sized chunks of work which can be completed within a reasonable amount of time, say a few days or a week. Work to be done is either committed to by the team (or specific individuals) as part of a sprint if Scrum is being followed, or continuously rolling in if an issue tracker or Kanban process is being used. The actual development work itself generally falls into three broad categories: user stories describing new features, bugs to be fixed, and technical tasks. There's a prioritization process, generally done by a product owner, and work tickets are refined to some level of detail.

Beyond this general structure, no assumptions are made about process. Each team, and each organization, has its own unique quirks, even if they are following a defined Agile framework. Agile in its various forms is pretty much ubiquitous for software development teams today.

Once a developer volunteers for, or is assigned to, a ticket, then the fun begins! But don't run off into a corner and start coding! Oh no, please don't do that. Instead, have a technical consultation at the start of the work.

Discuss with another developer who has solid knowledge in the domain of your ticket. Together, ensure that the scope of the ticket is clearly understood. Update the description as needed. Clarify with other team members or other stakeholders as needed. Depending on the level of detail already in the ticket, the technical consultation might be a straightforward review of well-understood requirements, or it might require a lot of effort, involving further analysis, investigation, or breakdown of the ticket into smaller, more manageable pieces.

It depends on the process your team has in place. Best practice is to have a lightweight "definition of ready", and the gathering of basic requirements before a ticket can be worked on by a developer. Generally speaking, demanding a full description of every detail before work begins is often time-consuming and usually not an efficient use of time.

It is shockingly common for developers to build the wrong thing, because of a misunderstanding of the requirements or worse, missing or assumed requirements. Of course, it is still possible to build exactly according to the description in a ticket, and still build the wrong thing at a business/strategy level, but the developer can't be faulted for that. However, an experienced developer might in such a situation raise their concerns to the product owner or whoever is requesting the work.

So that covers the first goal of the technical consultation: to be clear about WHAT needs to be done. The second goal is to work out, in some detail, HOW the work should be done.

Discuss the implementation strategy. What code needs to be modified? What code needs to be written from scratch? What existing code or library should be used? It may help to draw a diagram or two, work out key pieces of logic in pseudocode, or research between several possible approaches. If the implementation is unclear or requires experimentation, it may make sense to create a separate "spike" ticket and work on that first.

Usually, a ticket can be broken down into several parts or steps. These are typically called sub-tasks and should be worked out during the technical consultation.

The technical consultation is most fruitful as a discussion between two or three developers, but if needed, the discussion may be extended to include business collaborators, design collaborators, software testers, software architects, security experts, and others. This is the type of activity that pretty much must be done synchronously, either in person or on a call with screen sharing.

Now you're ready! There's a shared understanding of WHAT to build, and HOW to build it. You're all set to build the right thing, and build the thing right.
