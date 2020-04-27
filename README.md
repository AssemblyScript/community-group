![](https://avatars1.githubusercontent.com/u/28916798?s=64) AssemblyScript Community Group
=================

The Community Group provides all interested parties a place to discuss and collaborate with other community members.

**Related**

* [AssemblyScript Compiler](https://github.com/AssemblyScript/assemblyscript)
* [AssemblyScript Working Group](https://github.com/AssemblyScript/working-group)

**Contents**

* [Goals](#goals)
* [Guidelines](#guidelines)
* [Topics](#topics)

# Goals

* Enable everyone to share their ideas and projects
* Communicate core feature requests and use cases to aid in prioritizing the Working Group's efforts
* Avoid duplicating efforts amongst the broader ecosystem

# Guidelines

* Everyone working on or with AssemblyScript is welcome to participate!
* All participants must adhere to the [Code of Conduct](./CODE_OF_CONDUCT.md).

# Topics

Please note that the Community Group is farily new, so the following list is not exclusive. At this point in time, the majority of projects are platforms/runtimes that allow other third-party developers to develop, deploy, and execute modules written in AssemblyScript. This includes both trustful and trustless platforms.

* AssemblyScript DevX -- discussing missing language features and they way to implement them. Also we discuss the various approaches to interfacing AssemblyScript modules with the platform, e.g. do we choose eDSL or meta-programming approach;
* AssemblyScript libraries -- since we cannot import TypeScript libraries, common libraries like serialization, math, etc need to be reimplemented;
* AssemblyScript compiler hooks -- unlike Rust AssemblyScript does not have macros that would allow implementing basic code transformations that are important for eDSL or meta-programming. Many of these hooks are pretty common to most projects.
