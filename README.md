# Summary
Currently this repo holds rustc 1.78 with modified codegen files/ported code from ERASan to incorporate raw pointer analysis in Rust drivers and other programs.
### Modified files include:
* /home/rust/localrust/compiler/rustc_codegen_ssa/src/mir/block.rs
* /home/rust/localrust/compiler/rustc_codegen_ssa/src/traits/builder.rs
* /home/rust/localrust/compiler/rustc_codegen_llvm/src/builder.rs
