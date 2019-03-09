# JavaScript Shared Interfaces documentation effort
>  Stage 0

## Champion

Daniel Ehrenberg (@littledan)

## Description

["JavaScript Shared interfaces"](https://github.com/littledan/js-shared-interfaces/) is a documentation effort to explain how cross-environment ("isomorphic") JavaScript code can be written. My hope is that this can help convergence between different platforms over time.

## Required Resources

We will need a lot of help writing, expanding the current content in the following directions:
- Adding documentation about more JavaScript environments
- Deepening the coverage, including deviations in semantics between environments

## Who would be responsible?

I'm not sure; I'd like to not be the only person responsible for this. That's why I'd like to work with the Foundation.

## How would success be measured?

Ideally, all of the following would start to happen over time; we can talk to readers to find out whether these goals are being met.
- Programmers find this to be a useful resource for developing code that works across environments.
- Specification authors find this to be a useful resource to understand how their work affects multiple environments.
- JavaScript embeddings/environment maintainers find this to a be a useful guide for what interfaces to implement, based on what other environments share.

## Why this proposal is important

JavaScript is getting used in a bunch of different ways, and it's a tax on the ecosystem to have the differences be undocumented. A lot of the most popular modules on npm exist largely to paper over these differences, and the cost of this will grow over time as the number of environments and their capabilities grows.

## Unresolved Question

- How can this be maintained over time? It will be a continual effort.
- How should this be exposed to developers in the most friendly way?

## What is necessary to complete this proposal

- The js-shared-interfaces repo should be transferred to some kind of Foundation-related organization.
- There should be a reasonable first draft published, where we are comfortable with the contents and coverage of the scope.
- We should have a solid plan for maintaining the documentation over time and making sure it doesn't go out of date.
