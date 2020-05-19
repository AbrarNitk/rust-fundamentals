## Rust Installation

#### Important links
- Official [website](https://www.rust-lang.org)
- Rust [playground](https://play.rust-lang.org)
- Tools and editors [support](https://www.rust-lang.org/tools)
- Rust [learning](https://www.rust-lang.org/learn)
- Official [book](https://doc.rust-lang.org/book/)
- Rust by [example](https://doc.rust-lang.org/stable/rust-by-example/)
- Rust [blogs](https://blog.rust-lang.org)
- Rust [Documentation](https://doc.rust-lang.org/beta/)
- Rust lang [github](https://github.com/rust-lang)


#### Install `rustup`
- Rust is installed and managed by tool rustup(same as npm, pyenv for python virtualenv manager)
- Run `curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh`
- Official installation [link](https://www.rust-lang.org/tools/install)


#### Configure Path
- After running installation command all tools are installed inside `~/.cargo/bin` folder.
- To use all of them we have set this folder into system environment
- `export PATH="$HOME/.cargo/bin:$PATH"`

#### `rustup` update
- Updates all the tools inside the `~/.cargo/bin` folder and also update self.
- Run `rustup update`
- rustup [docs](https://github.com/rust-lang/rustup/blob/master/README.md)


#### Brief about rust tools(rustc, rustfmt, cargo)
- `rustc` is used for rust file compilation
- `rustfmt` is used for format the rust files
- `cargo` is rust package manager, It installs project dependencies of and compiles the project. It
   is same as maven for package manager.
- Cargo github [repository](https://github.com/rust-lang/cargo)
- Cargo official [document](https://doc.rust-lang.org/cargo)