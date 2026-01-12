---
title: Refactoring can be Oversimplification
layout: post
---

When faced with code that is difficult to understand, particularly in legacy systems, a common trope is that the correct next step is to refactor it and make it _simpler_. A trap teams fall into is thinking that they're one perfect code pattern away from having the perfectly understandable service that faces the same fate as soon as the author of said pattern changes teams.

software you didn't write will always be difficult to understand. Complexity is a combination of the code's history and a reflection of the complexity of the real world. The only way to avoid the burden of increasingly complex systems to to trust what's there does what it was written to do[^1].

[^1]: What it takes to trust code is a whole different topic

The only way to make sure everyone understands everything is to constantly refactor all your code and everyone contribute. Obviously this is not possible. A lot of software engineering is constantly molding the existing landscape to draw boundaries of what is relevant for your work. However, sometimes those boundaries are large and the only way to narrow it down is through a refactor.

So, when faced with these decisions, it's important our framing is appropriate. Why do we need to understand it? is the complexity because it was written poorly or because it attempts to model something very complex? Will we face the same issues as other parts of code inevitably get stale?

Each individual decision that was made to get a system to where it is was made intentionally. By focusing it all at a high level, we lose that context and inevitably repeat the same mistakes again. I cannot look at any system I've worked on and tell you why each piece does what it does. But I can go into each use case and discern why/how it was built and how we can evolve it.
