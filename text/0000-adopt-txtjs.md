- Start Date: 2020-03-13
- RFC PR: (after opening the RFC PR, update this with a link to it and update the file name)
- Relevant Project: TxtJS

# Adopt TxtJS

## Summary

Adopt TxtJS into the official CreateJS suite.

## Motivation

TxtJS is solving the problem that font rendering is inconsistent across browsers and operating systems. It is a great tool for design projects.

Bringing TxtJs into the fold will increase exposure to the project, providing greater levels of community scrutiny to it, helping not just to keep it alive, but also to improve it.

It may also help raise the profile of CreateJS projects.

Note that TxtJs is already endorsed by the CreateJS project: https://createjs.com/tools

## Detailed design

1. Fork the project from https://github.com/ReCreateJS/txtjs into https://github.com/CreateJS/TxtJS
2. Request GitHub remove the 'fork' link, so it becomes an original repo.
3. Update TxtJS messaging
4. Update website to match CreateJS theme

> This is the bulk of the RFC.

> Explain the design in enough detail for somebody
familiar with the project to understand, and for somebody familiar with the
implementation to implement. This should get into specifics and corner-cases,
and include examples of how the feature is used. Any new terminology should be
defined here.

## How we teach this

We'd need to introduce documentation at a quality to at least match the rest of the CreateJS suite.

## Drawbacks

The project does vary somewhat from CreateJS projects.

> Why should we *not* do this? Please consider the impact on teaching CreateJS,
on the integration of this feature with other existing and planned features,
on the impact of the API churn on existing apps, etc.

> There are tradeoffs to choosing any path, please attempt to identify them here.

## Alternatives

> What other designs have been considered? What is the impact of not doing this?

> This section could also include prior art, that is, how other frameworks in the same domain have solved this problem.

## Unresolved questions

The original creator is not necessarily on board. Of course, we'd attribute them  However, the MIT license might warrant that
this is ok.

> Optional, but suggested for first drafts. What parts of the design are still
TBD?
