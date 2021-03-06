# Code Index

rustc has a lot of important data structures. This is an attempt to give some
guidance on where to learn more about some of the key data structures of the
compiler.

Item            |  Kind    | Short description           | Chapter            | Declaration
----------------|----------|-----------------------------|--------------------|-------------------
`CodeMap` | struct | The CodeMap maps the AST nodes to their source code | [The parser](the-parser.html) | [src/libsyntax/codemap.rs](https://github.com/rust-lang/rust/blob/master/src/libsyntax/codemap.rs)
`ParseSess` | struct | This struct contains information about a parsing session | [The parser](the-parser.html) | [src/libsyntax/parse/mod.rs](https://github.com/rust-lang/rust/blob/master/src/libsyntax/parse/mod.rs)
`TraitDef` | struct | This struct contains a trait's definition with type information | [The `ty` modules](ty.html) |  [src/librustc/ty/trait_def.rs](https://github.com/rust-lang/rust/blob/master/src/librustc/ty/trait_def.rs)
`TyCtxt<'cx, 'tcx, 'tcx>` | type | The "typing context". This is the central data structure in the compiler. It is the context that you use to perform all manner of queries. | [The `ty` modules](ty.html) | [src/librustc/ty/context.rs](https://github.com/rust-lang/rust/blob/master/src/librustc/ty/context.rs)
