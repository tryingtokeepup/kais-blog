---
layout: blog
title: Labs Retrospective - Week 1
date: 2019-02-15T17:13:50.260Z
---
\# Part 1 - Individual Accomplishments this Week

Github Handle: \[tryingtokeepup](https://github.com/tryingtokeepup)

This was a ... interesting week. We really didn't have much opportunity to write up any actual code, as our codebase was basically setup for us.  This is completely new territory for me (along with my team), so I had to radically shift my view on what productive work is. 



For this week, I spent the majority of my time reading on GraphQL, Auth0, MongoDB, and what environmental variables we need to actually get the original site working. It went alright, but I have to be honest, it was quite painful not being able to do any actual code this week due to not being able to actually understand the technology base the old team was using. We also had tremendous difficulty even utilizing the site after we made a development branch off of the main branch, due to not having the right environmental variable structure that the previous team had, not being able to communicate with that previous team, and having the docs (while very good compared to what I am used to) be incomplete in explaining what Auth0 is actually looking for in our codebase.

I think Auth0 was our biggest stumbing block.😕

\## Tasks Pulled

Since our project requires us to add on new functionality to an already existing app, my goal this week was to understand the existing code. As such, all of my pull requests this week either adds comments to existing code or updates READMEs in order to better help my teammates:

\* Ticket 1: Added comments to Readme.md  \* \[Github](https://github.com/Lambda-School-Labs/labs-team-home/pull/247)  \* \[Trello](https://trello.com/c/oyd8ltxC/37-add-comments-to-readme)\* Ticket 2: Even more comments!  \* \[Github](https://github.com/Lambda-School-Labs/labs-team-home/pull/247)  \* \[Trello](https://trello.com/c/oyd8ltxC/37-add-comments-to-readme)\* Ticket 3: Actually did something useful - redirected our repo to the right backend  \* \[Github](https://github.com/Lambda-School-Labs/labs-team-home/pull/248)  \* \[Trello](https://trello.com/c/jTXWoQ2d/17-learn-graphql-apollo-prisma-kai)\* Ticket 4: Last pull, env variable update  \* \[Github](https://github.com/Lambda-School-Labs/labs-team-home/pull/271)    \* \[Trello](https://trello.com/c/jTXWoQ2d/17-learn-graphql-apollo-prisma-kai)

\## Detailed Analysis





!\[Cute dog](/assets/doggie_2.jpg)\_Doggie test\_

Yikes, this whole week was difficult for me. Need that dog above to keep me sane, for real. But Ticket 4 was me finally breaking down and asking the original team for help. I should probably screen shot our convo on zoom, but we as a team basically decided that enough was enough, and wasting another day (after using up 3 days of dev time) on trying to blindly get Auth0 was not possible. So I went ahead and contacted the previous team for some help deploying with Auth0, and they immediately sent their old env variables, even though that was supposed to be an internal secret. 

Goes to show you that sometimes, just asking for a little help can help solve your most intractable problems. I think we are still having a little issue with that, but I think that now, we can at least get something up on our personal development machines.

\# Part 2 - Milestone Reflections

So, I think our Milestone this week was to work on TDD
