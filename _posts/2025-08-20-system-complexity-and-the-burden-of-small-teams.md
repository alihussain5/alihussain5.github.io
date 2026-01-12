---
title: System Complexity and the Burden of Small Teams
layout: post
---

I’ve worked in a number of different product orgs ranging in size from 6 to 400, and one of my learning from being in a team of 3 is just how resource-constraining it is. On a larger team, you are significantly more free to take on risks and experiment - no matter what, there is a contingent on the team and company whose responsibility it is to keep the lights on. The smaller the team, the more fluid that responsibility is, but it’s generally always there once you hit critical mass.

We don’t have the same luxury. Not that we’re not taking risks or experimenting, it’s actually all we’re doing, but we have to be significantly more calculated. Maintenance, infrastructure, dependencies, all become significant burdens. If we execute wrong and create too much of a burden for ourselves, our velocity is screwed. Because we don’t have the resources to both maintain and build, we’ll end up hiring to meet the demands of the system, start solving for acquired complexity instead of inherited complexity, and build an org to solve the problems we created for ourselves instead of the actual business. 

That’s one end of the extremes. The other end is an organization that refuses to take on any burden. This is an org that never scales. Burden is an inherent side-effect of thinking big, there’s no way to build sophisticated systems without also building complexity that has to be loved and cared for.

This isn’t a new concept and might feel pretty obvious. There is a sweet spot in the middle that allows us to take on enough day-to-day complexity that outweighs the complexity had we not.

This manifests across many mundane life decisions - making a grocery list takes effort but is easier than trying to keep everything in your head. Creating your own notation so that you can write grocery lists faster is an optimization you could make, but what if you have to share your grocery list with your significant other? You could teach them your notation. What if your grocery store will prestock your items for you if you send them your list ahead of time? You might think to revert back to using English, but your significant other has already forgotten English in favour of grocery notation (lol). Now you’ve started building a system, but you’re stuck building a solution to translate to-and-from your notation - an unnecessary complexity - before getting anything actually done.

Of course while I’m writing this I’m thinking about product and engineering burden, but this also applies to organizational complexity. Process is work, and that work is worth it sometimes and sometimes it isn’t.
