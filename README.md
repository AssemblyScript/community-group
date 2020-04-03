# AssemblyScript Community Group
> TODO: This repo to be moved to a collectively owned organization, e.g. https://github.com/AssemblyScript

Majority of the projects in this community group are platforms/runtimes that allow other third-party developers to develop, deploy, and execute modules written in AssemblyScript. This includes both trustful and trustless platforms. This repository with its PRs and issues is used to coordinate these projects on common components and discussions.

### Goals

* As a community, we want to discuss and priotize missing language features that we then would communicate to the core developers of AssemblyScript;
* We want to avoid duplicating effort of writing common AssemblyScript components like libraries and compiler hooks;
* We want to have shared responsibility for security-critical components of AssemblyScript.

### Common Topics

* AssemblyScript DevX -- discussing missing language features and they way to implement them. Also we discuss the various approaches to interfacing AssemblyScript modules with the platform, e.g. do we choose eDSL or meta-programming approach;
* AssemblyScript libraries -- since we cannot import TypeScript libraries, common libraries like serialization, math, etc need to be reimplemented;
* AssemblyScript compiler hooks -- unlike Rust AssemblyScript does not have macros that would allow implementing basic code transformations that are important for eDSL or meta-programming. Many of these hooks are pretty common to most projects.
