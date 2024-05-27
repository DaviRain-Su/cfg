# cfg

My computer config file

## RUST BINARY TOOLS

- [eza](https://github.com/eza-community/eza?tab=readme-ov-file)
- [du-dust](https://github.com/bootandy/dust)
- [ast-grep](https://github.com/ast-grep/ast-grep) 还未真实清楚怎么用

## Cargo TOOLS

- cargo-udeps 删除未使用的依赖项,cargo-udeps会扫描你的Cargo.toml文件，并检查在[dependencies]下列出的所有crate是否实际上在项目中使用。
  - `cargo install cargo-udeps`
  - `cargo +nightly udeps` # cargo-udeps需要夜间版编译器。
