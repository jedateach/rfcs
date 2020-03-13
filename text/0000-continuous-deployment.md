- Start Date: 2020-03-12
- RFC PR: (after opening the RFC PR, update this with a link to it and update the file name)
- Relevant Project: CreateJS (all projects)

# Continuously Deploy CreateJS

## Summary

Use Travis to continuously package and release CreateJS to the npm registry on merges to master branch.

## Motivation

Releasing code can be automated. Humans are fallible and can make mistakes, including leaking secrets etc. Once set up, it will be simple for humans to rely on an automated process for releasing new versions of the code.

## Detailed design

Configure Travis to release new versions to npm

## How we teach this

> What names and terminology work best for these concepts and why? How is this
idea best presented? As a continuation of existing patterns, or as a
wholly new one?

> Would the acceptance of this proposal mean the CreateJS guides must be
re-organized or altered? Does it change how CreateJS is taught to new users
at any level?

> How should this feature be introduced and taught to existing users?

## Drawbacks

> Why should we *not* do this? Please consider the impact on teaching CreateJS,
on the integration of this feature with other existing and planned features,
on the impact of the API churn on existing apps, etc.

> There are tradeoffs to choosing any path, please attempt to identify them here.

## Alternatives

> What other designs have been considered? What is the impact of not doing this?

> This section could also include prior art, that is, how other frameworks in the same domain have solved this problem.

## Unresolved questions

> Optional, but suggested for first drafts. What parts of the design are still
TBD?
