# 2020-7-22

## Proposed Agenda
* Welcome new members
* Discuss build tooling and default conventions old PR: https://github.com/AssemblyScript/assemblyscript/pull/1134/files
* Discuss liking; compiling modules where imports are just typed checked and linked at runtime
  - Add bindings similar to wasm-bindgen.
  - Example of a WebGL binding: https://github.com/lume/glas
* Rick's VS extension
* Closure Update
  - Waiting on [Binaryen PR](https://github.com/WebAssembly/binaryen/pull/2586) to be merged.
  - https://github.com/AssemblyScript/assemblyscript/pull/1401
  - AIR - AssemblyScript Intermediate Representation; [Example](https://github.com/AssemblyScript/assemblyscript/blob/air/src/air.ts)
  - Pending PR for closure tests, but might be rewritten
* Plans for new six months
  - Reach out to more projects
  - AIR
  - as-wasm-bindgen, a simple tool to generate JS bindings that are type aware. [A starting point](https://github.com/AssemblyScript/assemblyscript/blob/master/src/definitions.ts#L373)
  - wit, witx support, [as-witx](https://github.com/jedisct1/as-witx)
  - Use wasm-gc opcodes and add polyfill in [binaryen pass.](https://github.com/WebAssembly/binaryen/issues/2935)
    - [wasm-gc](https://github.com/WebAssembly/gc)
    - [Prototype](https://github.com/WebAssembly/gc/issues/81)


# 2020-5-13

## Proposed Agenda
 - Discuss Closures implementation
   - Currently use a global to store the closure to be 
 - Discuss making meetings less frequent


# 2020-04-29

## Proposed Agenda
* Review action items
* Open Forum
* Discuss next action items

### Previous Action items

* Linting
 - Rick made VS extension 
 - Add a parseFile option for complier to be added soon to simplify linting.
* hex/base64 libs
 - Hex is stdlib
 - base64?
 - [SHA-256 lib](https://github.com/ChainSafe/as-sha256)
* Compare the performance of passing complex types through serialier and by writting directly into memory.
  - Future [borsh](https://github.com/near/borsh) implementation in AssemblyScript @willemneal
* ~~Decide where to keep this repo,~~ 


## New Action Items
- ~~create calendar @torch2424~~
- vtables PR @willemneal
- ~~Publish base58/64 @willemneal~~


## News
- [PR on object literal instatianation with optional fields.](https://github.com/AssemblyScript/assemblyscript/pull/1229) @torch2424 
- 0.10.0 release on the horizon.
- Web3 Foundation doesn't want to support crypto develompent without dedicated support.
- [Crypto Wasi on the horizon.](https://github.com/WebAssembly/WASI-crypto)
