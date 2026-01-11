---
layout: post
---

This is a personal reflection over my career as I've gained understanding of what it takes to build useful product. I've worked on a number of software products and an underlying theme is _how do we get people's fragmented workflows into a tidy product where they can achieve their goals faster_. Almost always, that fragmented workflow is heavily reliant on Excel. This leads to a neverending battle with Excel and replicating the unmaintainable and confusing systems it can enable.

Looking back, a big learning wasn't at all how to get people out of Excel - we definitely tried that - but it was the refusal to acknowledge that Excel and other workflows outside of whatever product we were building were valid. Personally, I was arrogant and took the stance that everything done outside of our app was easily[^1] reproducible with modern tech and would always be superior. This led to a place where the boundaries of our product were strictly defined and flexibility wasn't a consideration.

[^1]: A common theme in early career software engineers - the inability to comprehend the full complexity of the real world and non-engineer's ability to navigate it.

We quickly learned that our app really didn't cover everything particularly well, and so folks continued to use their own personal workflows (again, mostly in Excel). Without the affordance to augment their workflows, we ended up with a huge fragmentation where very little was done in-app[^2] and there was no cohesive end-to-end product. We doubled down on the product and tried to shove as much as possible in there, but it was of no use because we still couldn't match our user's workflows. It's important to acknowledge the limits of what/how fast we can build, and creating escape gaps to ensure that whoever uses our product can use it as a supplement to their existing world. As a product evolves, there will be less need for those external workflows, but you can't just skip to that end result.

[^2]: This also has the nasty side-effect of giving us false confidence that we've captured everything the user is doing and stopped paying attention to the truly valuable work

An example that comes to mind is my use of [https://www.copilot.money/](Copilot Money). I use copilot for expense tracking. It's a nice app and I'm a happy user. However, it's functionality is not really anywhere near what I need in my expense workflow. Once my transactions are consolidated across my accounts and tagged appropriately, I leverage the CSV export functionality to put it into Excel and do everything else I need to do. Without this functionality, using the product would probably make my expense tracking experience actively worse.
