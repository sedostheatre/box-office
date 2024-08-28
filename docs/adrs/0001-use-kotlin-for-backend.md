# Use Kotlin/Quarkus for Backend

## Status

proposed

## Context

We're starting out the system, need to decide on basic set up requirements, like infrastructure. 
We have a disparate tech stack within Sedos, including C# for the website, Python for various membership tools and a mix of other frameworks and smaller utilities.
We need a broadly supported tech stack to enable future development safely, as well as providing an interesting tech stack for contributors.

Various options were proposed, including

- C#
- Python/Django
- Kotlin/Quarkus/Spring Boot

Python has limited type safety, and is somewhat unfamiliar to some of those involved, and Django isn't great for an API led integration.
C# and Kotlin are both entirely capable, but a mild preference in the team leads to Kotlin as the languag opf choice.
Quarkus is a more interesting/likely easier to scale to zero framework, and any of the downsides of it being newer are lkikely offset by the fairly simple requirements we've got.

## Decision

Adopt Kotlin and Quarkus as default technologies.

## Consequences

We have a default tech stack for our backend code base.
