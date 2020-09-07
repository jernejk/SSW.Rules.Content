---
type: rule
archivedreason: 
title: Do you know how to write a good pull request?
guid: d35b49bf-bdd1-48eb-bc1d-944cdc5be4dc
uri: do-you-know-how-to-write-a-good-pull-request
created: 2020-07-17T01:21:08.0000000Z
authors:
- id: 86
  title: Chris Clement
- id: 97
  title: Matt Goldman
related: []

---

As a software developer, it is very common to see a pull request. The quality of a pull request can vary - sometimes we have to deal with a cryptic pull request and sometimes we find a very well written pull request.

Having a great pull request message can help your peers to understand your pull request quickly so they can review your pull request faster and also give you better suggestions.

<!--endintro-->

While the pull request itself is valid and may offer a high value, you need to spend a bit of time to understand what is the context of this pull request and what does it change. Doing this step can take your time easily from 1 minute (if you just recently touched the code) to more than 10 minutes (if it has been a long time since you worked on it - or even if you have never touched the code).

Writing a great pull request can help your peers to understand your code better and therefore, they can give you better insights (or faster review turnaround time, that's great!).

There are a couple of things that you can do to improve your pull request:

1. Write a concise and self-explanatory title
2. Write a concise and descriptive body
3. Link the pull request to the associated issues / PBIs


<font color="#333333">      <br></font>

### 1. Write a concise and self-explanatory title


The key to writing a concise pull request is to base the pull request itself on a PBI / issue.

Example PBI title: Product Backlog Item 100359: "Desktop App | Exporting occasionally failed"


::: greybox
Pull request title: "Fix exporting"

:::



::: bad
Bad example - Pull request title does not tell what issues have been fixed and how

:::



::: greybox
Pull request title: "Fix desktop app exporting - prevent database concurrent access while exporting"

:::



::: good
Good example - Pull request title briefly describe the fix that it has

:::


The important information in the title are:



1. What the pull request will do
2. How the pull request achieved it




Having the "What" information allows the reviewers to quickly understand what this is about while having the "How" can help the reviewer to quickly understand how your pull request solved the problem. Sometimes we might want to put the "How" in the pull request body if it is too long or hard to explain in one sentence.

### 2. Write a concise and descriptive body


Pull request body is a medium for the developer to tell the reviewers what the pull request is about. Things that need to be kept in mind before writing a pull request body:



1. What the pull request is about and why did you raise a pull request
2. How did the pull request will achieve the feature/fix the bug/other goals it may have
3. (Optional) Put a screenshot if it will help the reviewer to understand the changes (e.g. front-end cosmetic change)
4. (Optional) What do you want the reviewers to do - this can be approvals (most of the case) or looking to get more feedback on a piece of code in the pull request.

<dl class="badImage">&lt;dt&gt;<img src="better-pr-bad-pr.png" alt="better-pr-bad-pr.png" style="width:730px;">&lt;/dt&gt;
   <dd>Bad example - Pull request with vague title and no description<br></dd></dl><dl class="goodImage">&lt;dt&gt;
      <img src="better-pr-good-pr.png" alt="better-pr-good-pr.png" style="width:730px;height:503px;"> 
   &lt;/dt&gt;<dd>Good example - Pull request with a good title and descriptive body<br></dd></dl> There is also a well-known pull request semantic like [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0-beta.2/) on how to write a pull request body, but we can still have a great pull request without using such semantic.

### 3. Link the pull request to the associated issues / PBIs




Since we already have a great title and body, the last thing to do is to associate this pull request to the related PBIs or issues.

Linking an issue to a pull request can serve as documentation on which development work that was done on a specific PBI/issue. It may help the team in the future to debug when and which changes were introduced and what was the original specification of that piece of work.
<dl class="image">&lt;dt&gt;
      <img src="better-pr-link-issues.png" alt="better-pr-link-issues.png" style="width:730px;height:504px;"> 
   &lt;/dt&gt;<dd>Figure: Linking a pull request to the related issue<br></dd></dl><dl class="image">&lt;dt&gt;
      <img src="better-pr-link-issues-linked.png" alt="better-pr-link-issues-linked.png" style="width:730px;height:504px;"> 
   &lt;/dt&gt;<dd>Figure: A pull request is now associated with the related issue<br></dd></dl>