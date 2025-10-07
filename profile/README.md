# The Water Engine

Welcome to the Water Engine! We are a small team of developers building a powerful yet easy-to-use suite of chess-related tools/apps.

## Mission
Our goal is to facilitate learning through doing, and to have fun and find success along the way. Iteration is paramount, failure is expected, recovery should be graceful.

### Philosophy
- Experiment freely: if you're on the fence about an implementation, just go for it!
- Keep it simple: focus on small, incremental improvements.
- Collaborate openly: share knowledge, review code, and support each other.

# Getting Started with the Water Engine

```shell
git clone https://github.com/Water-Engine/water.git
cd water
zig build run --release
```

This will build and run the engine with a default configuration.

# Getting started with the cactus framework

Cactus provides following packages:
- `cactus-cli` enables stress-testing of chess engines, offering multiple tournament formats and easy export of match results.
- `cactus-gui` allows you to host PvP, Bot vs Player, or Bot vs Bot matches, and provides tools for analyzing games.
- `libcactus` serves as the core library, powering both the CLI and GUI applications.  

for more info on the project check [README](https://github.com/Water-Engine/cactus/blob/main/README.md).

To directly install packages provided by `cactus` using `cargo` from Github run:
```
cargo install --git https://github.com/water-engine/cactus --path <package>
```
