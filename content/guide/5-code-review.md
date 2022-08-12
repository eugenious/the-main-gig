---
title: "5 - Code Review"
weight: 6
---

_Make sure all the ducks are lined up in a row._

Code reviews have become industry standard but it has not always been so! In the past, it was not uncommon for a developer to get assigned to implement a feature, disappear for a few weeks, and caffeine and some possibly sleepless nights later, present a demo of the finished product to others. The code itself, more often than not, would not even be looked at!

The mental model of what writing software is all about has changed dramatically: Not so much like Michaelangelo chipping away alone at a block of marble to make a masterpiece, but rather a group of dedicated athletes rowing together towards the finish line. When it comes to the highly complex work of telling a computer what to do, two minds are definitely better than one. Certainly, there are some superstar coding lone-rangers out there, but they are the exception, and very rare. The vast majority of code today is produced by teams.

All developers should be well-versed in both preparing merge requests (also called pull requests) for review, as well as reviewing other people's merge requests. Unfortunately it is often a topic that is not emphasized in the formal education of most developers.

## Lining your ducks in a row

Here, briefly, are some standard best practices for preparing a merge request for review.

The basics of a good merge request:

* accurate descriptions and commit messages
* a small changeset
* and, of course, excellent quality code

Some useful processes to have in place on your team are:
* A contributor's guide
* A merge request checklist

As for how many reviewers are needed, and who is allowed to be an approver, these probably need to be worked out per project. A good starting point for non-open source project teams is: two reviewers, and anybody on the team can be a reviewer.

Rather than trying to give a thorough treatment of what is involved in doing code reviews (many excellent resources already exist), here we'll point out some common antipatterns, pitfalls to avoid in doing code reviews on your team.

## Antipattern: Doing just a code review

If the only main gig practice that is done on your team is the code review, then it's likely to be painful. The review may uncover missed requirements, incorrect assumptions, or reveal a better implementation approach, all of which might require a dreaded rework. What time you thought you saved by cutting corners now comes back to haunt you. It's the age old adage: measure once cut twice.

Rework is to be strongly resisted. It means writing code again ("I thought I was already done!"); it means a second, or third, or fourth round of review by the reviewers ("It's all a blur now that I'm looking a this code for a fifth time!"); and it means delays and pressure to deliver, ("It's a hack, but we're out of time, we need to ship it now!").

Instead, aim to receive a perfect code review, which is a quick approval with a "good job" sticker. The more mature and experienced your team the more frequently this "code review nirvana" should be occurring. It doesn't mean perfect developers, but it does mean excellent collaboration throughout the code writing process, such that there are no surprises at the code review stage.

## Antipattern: Antagonistic code reviews

A code review can be bruising to your ego. Having someone scrutinize your work and criticize it is a bit frightening. The code reviewer should be sensitive to this, and always be kind and gentle when leaving comments. Be prompt to discuss synchronously in a real converation, rather than re-re-re-replying to a long and confusing comment thread.

The developer should see a code review for the positive experience that it should be. It's a fantastic learning opportunity, and one of the best ways to improve your craft and learn from others. Always thank your review for helping you to see where your work might be improved, or at least for the opportunity to defend and justify your choices.

## Antipattern: Code review as an unpleasant chore

Ever get stuck having to do four code reviews in a row? Then you know what I mean! It can seem like punishment. Just as a code review can be a learning opportunity for the developer, it can also be a learning and teaching opportunity for the reviewer as well. As the saying goes, to become a great writer, first you should read a lot. A code reviewer takes on the role of an editor, which is quite different than the role of a writer. As it is with crafting words, so it is with crafting code. Often senior developers are responsible for doing code reviews, but I'd advocate that all developers should be doing code reviews.

If for every code review, you learn one thing, and teach one thing, then you are doing well.
