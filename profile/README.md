# Sogouda

♥ Create lightweight desktop apps using HTML/CSS/[TS](https://www.typescriptlang.org/) ♥

[Sogouda](#sogouda) is a framework for creating lightweight desktop apps using the familiar web development stack.
This means that, out of the box, Sogouda apps can be developed using:

* [x] HTML
* [x] CSS
* [x] JavaScript

Furthermore, plugins are available to add support for:

* [ ] TypeScript
* [ ] JSX
* [ ] TSX
* [ ] LESS

## Packages

### [Rust](https://www.rust-lang.org/learn)

* [`sogouda_core`](#core-library) - The core library (written in [Rust](https://www.rust-lang.org/learn)).

### JavaScript/[TypeScript](https://www.typescriptlang.org/)

* [`sogouda`](#javascripttypescript-api) - A high-level library for [Sogouda](#sogouda) written in [TypeScript](https://www.typescriptlang.org/).
* [`@sogouda/bindings`](#javascripttypescript-bindings) - [TypeScript](https://www.typescriptlang.org/) bindings for [`sogouda`](#core-library).

## Core Library

The core library, [`sogouda_core`](#core-library), is written in [Rust](https://www.rust-lang.org/learn) to enhance compatibility, performance, and security.
Bindings for [`sogouda_core`](#core-library) are available for different programming languages.

* [Source code](https://github.com/sogouda/sogouda_core)
* [Package](https://crates.io/crates/sogouda_core)

## Bindings

Bindings are provided to use [Sogouda](#sogouda) with various programming languages.

### JavaScript/[TypeScript](https://www.typescriptlang.org/) Bindings

The bindings, [`@sogouda/bindings`](https://npmjs.org/package/@sogouda/bindings), are written in [Rust](https://www.rust-lang.org/learn) to enhance compatibility, performance, and security.
Type definitions are written in [TypeScript](https://www.typescriptlang.org/) and compiled into a [`.d.ts`](https://github.com/sogouda/node-bindings#project-layout) file to accompany [`index.node`](https://github.com/sogouda/node-bindings#project-layout).

* [Source code](https://github.com/sogouda/node-bindings)
* [Package](https://npmjs.org/package/@sogouda/bindings)


## JavaScript/[TypeScript](https://www.typescriptlang.org/) API

Sogouda exposes a [high-level JavaScript/TypeScript API](https://github.com/sogouda/node-sogouda/) written in [TypeScript](https://www.typescriptlang.org/).
This makes designing apps feel a lot more familiar to developers coming from Electron or other similar frameworks.
Type definitions are created in [TypeScript](https://www.typescriptlang.org/) and compiled into a `.d.ts` file to accompany the distributable files.

* [Source code](https://github.com/sogouda/node-sogouda)
* [Package](https://npmjs.org/package/sogouda)

### Supported Runtimes

* [x] Node.js
* [ ] Deno
* [ ] bun
