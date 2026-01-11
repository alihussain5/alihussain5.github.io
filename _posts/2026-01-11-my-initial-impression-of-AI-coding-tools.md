---
layout: post
---

_This is a quick one, I'll have to find more dedicated time to truly capture all my thoughts on AI coding tools and its impact on our industry._

In an attempt to not be labeled a luddite, I've been trying to incorporate some of these modern tools into my daily programming workflow. I've actually been using Github Copilot for inline auto-completion for a while now, but have recently started using Claude Code more to help with heavier tasks.

It's been decent. I'm quite happy that I no longer have to type out entire object equality checks when writing tests, recreate the same base service template every time I'm building something new, or move code blocks and files around when refactoring. I understand that these could also be solved by getting better at using my IDE, but laziness prevails.

It's also led to a lot of frustration - almost any time I'm facing a problem that can't be solved with the equivalent of a Stack Overflow solution or by reading documentation. Unfortunately, it's difficult to know whether what's in front of you has a simple solution or not, and it's easy to get stuck in a cycle of thinking you're one prompt away from Claude solving it. I find myself constantly debating whether to acknowledge the sunken cost and get ready to solve it the old fashioned way.

I came across [this comment on Hacker News](https://news.ycombinator.com/item?id=46417518) that helped orient my thinking around these tools:

> AI coding tools are effective for many because, unfortunately, our work has become increasingly repetitive. When someone marvels at how a brief prompt can produce functioning code, it simply means the AI has delivered a more imaginative or elaborate specification than that person could envision, even if the resulting code is merely a variation of what has already been written countless times before. Maybe there's nothing wrong with that, as not everyone is fortunate enough to work on new problems and get to implement new ideas. It's just that repetitive work is bound to be automated away...

I believe novel work will not be automated away. There are non-novel pieces of that work that can be broken off (e.g. algorithm implementations, internal patterns). This has always existed as a fundamental of software engineering; identifying the simple/repeatable pieces and drawing boundaries around them. The number of these pieces has increased with these tools, as now you can get a model to adopt your niche internal patterns or recreate existing library functionality[^1] to specifically fit your use case.

[^1]: I worry about the effect this will have on the utilization and maintainence of OSS that would normally be supported by the developers using them. I also worry that simple and clean interfaces are no longer a prerequisite to working implementations and what that means for consistent, reliable development patterns

Additionally, I firmly believe in order to truly understand a system you need to have written it or have helped write it. To invert that statement, if you do not need to understand the internals of a system, you do not need to have contributed to it. This helps me draw a boundary of what work I will use AI tools for; which is only if it's non-novel and it's not important for me to understand how it works, or if I already know how it works. Things like singular isolated implementations with limited side effects, spotting bugs when using third party libraries, or repeating existing developer patterns that already exist in the codebase.

I'll probably keep using Claude Code for the forseeable future, while being aware of my understanding of the software I'm building and trying to keep my engineering skills from atrophying.
