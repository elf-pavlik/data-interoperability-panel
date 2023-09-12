# Solid Data Interoperability Panel

[![Join the chat at https://gitter.im/solid/data-interoperability-panel](https://badges.gitter.im/solid/data-interoperability-panel.svg)](https://gitter.im/solid/data-interoperability-panel?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

## Purpose

We must be able to support data interoperability across applications while enabling secure collaboration and query using intuitive data boundaries.

Diversity in how the same data will be accessed and manipulated by different entities and applications increases the need for reliable mechanisms that protect against data corruption, data leakage, or broken workflows

Standard methods and mechanisms for interoperability, collaboration, and security of data in a Solid Pod must realize these needs, and it must be done without changing the fundamentals of Solid.

Read our stated [Problems and Goals](problems-and-goals.md) for an in-depth understanding of the panel's focus.

## Initiatives in Process

### Solid Application Interoperability

* **Specification** — [Source](https://github.com/solid/data-interoperability-panel/tree/master/proposals/specification) — [Rendered](https://solid.github.io/data-interoperability-panel/specification/)
* **Application Primer** — [Source](https://github.com/solid/data-interoperability-panel/tree/master/proposals/primer/application.bs) — [Rendered](https://solid.github.io/data-interoperability-panel/primer/application.html)
* **Authorization Agent Primer** — [Source](https://github.com/solid/data-interoperability-panel/tree/master/proposals/primer/authorization-agent.bs) — [Rendered](https://solid.github.io/data-interoperability-panel/primer/authorization-agent.html)
* **Resources**
  * [Application Interoperability Walkthrough — Part 1](https://solid-interop-public.s3.amazonaws.com/application-interoperability-walkthrough-part-1.mp4) (VIDEO)
  * [Application Interoperability Walkthrough — Part 2](https://solid-interop-public.s3.amazonaws.com/application-interoperability-walkthrough-part-2.mp4) (VIDEO)

#### Current targets

- Publish 1.0 Draft of Application Interoperability Specification
- Publish 1.0 Draft of Application Primer
- Publish 1.0 Draft of Authorization Agent Primer
- Complete Typescript library implementation
- Complete Java library implementation
- Complete Typescript Authorization Agent Service implementation

### Shape Trees

* **Specification** — [Source](https://github.com/shapetrees/specification) — [Rendered](https://shapetrees.org/TR/specification/index.html)
* **Library** — [Source](https://github.com/shapetrees/shapetree.js)
* **Test Suite** — [Source](https://github.com/shapetrees/test-suite)

#### Current targets

- Publish 1.0 Draft of Shape Trees Specification
- Publish 1.0 Draft of Shape Trees Primer
- Complete Typescript Shape Tree Implementation
- Complete Java Shape Trees Implementation
- Submit Server-side Shape Tree validation to solid/specification
- Integrate server-side Shape Tree validation into CSS

## Completed Initiatives

[Resource Metadata](https://github.com/solid/data-interoperability-panel/tree/master/archive/resource-metadata) — Resource Metadata was [submitted](https://github.com/solid/specification/pull/156) as a candidate proposal to the [`solid/specification`](https://github.com/solid/specification/). It was renamed to Auxiliary Resources during Editorial Review.

## Meetings

Solid Data Interoperability Panel meetings are held every other Monday at 12:00 UTC ([CG calendar](https://www.w3.org/groups/cg/solid/calendar)).

This bi-weekly schedule started on April 10th 2023; the latest meeting date can be found via [the minutes label](https://github.com/solid/data-interoperability-panel/issues?q=is%3Aissue+label%3Ameeting) or the [CG calendar](https://www.w3.org/groups/cg/solid/calendar).

Every meeting is also announced on [Gitter/Matrix](https://gitter.im/solid/data-interoperability-panel), with a link to its agenda. 

Conference call: https://meet.jit.si/solid-data-interoperability


## Process

Initiative proposals must be [submitted as issues](https://github.com/solid/data-interoperability-panel/issues/new), and receive support from members of the panel. At least three panelists (not including the panelist proposing the project) must support creation of the project, with no panel members actively rejecting it. Initiative proposals with support will be prioritized and undertaken by the panel.

Substantive changes submitted to active panel initiatives should be submitted as pull requests, and should receive at least two review approvals from panelists, with no one actively rejecting.

Panel members should work together to settle deadlocks. It may be helpful to request the perspective of a Solid Editor who would ultimately be responsible for accepting submitted candidate proposals to settle deadlocks.
